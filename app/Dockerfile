FROM node:16

# Create app directory inside container
WORKDIR /app

# Copy package.json if you had dependencies (optional now)
# COPY package*.json ./

# Copy all app files to container
COPY . .
# Install dependencies (none for now, skip if not using package.json)
# RUN npm install

# Expose port 3000
EXPOSE 3000

# Start the app
CMD ["node", "index.js"]
