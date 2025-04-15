FROM node:18-alpine

WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Expose ports
EXPOSE 19000
EXPOSE 19001
EXPOSE 19002

# Start the application
CMD ["npm", "start"] 