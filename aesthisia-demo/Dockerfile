
# Pull node image
FROM node:14

# Copy the current directory contents into the container
COPY . .

# Install npm
RUN apt update
RUN apt install nodejs npm -y
RUN npm i

# Exposing port
EXPOSE 3000

# Default command to run when container starts
CMD ["npm", "start"]

