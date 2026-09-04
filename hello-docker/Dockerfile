FROM node:20-alpine

# Set working directory
WORKDIR /app

# Copy application files and set ownership to non-root user
COPY --chown=node:node . .

# Switch from root to non-root user (built into official Node images)
USER node

# Execute application
CMD ["node", "hello.js"]
