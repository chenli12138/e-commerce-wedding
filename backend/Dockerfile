# strapi/Dockerfile
FROM node:18

# Set working directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy application files
COPY . .

# Expose port 1337
EXPOSE 1337

# Start the Strapi server
CMD ["npm", "run", "develop"]
