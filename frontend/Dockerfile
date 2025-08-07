FROM node:18-alpine
WORKDIR /app
# Copy package files for caching
COPY . .
# Install dependencies
RUN npm install

# Expose port 5173 (Vite default)
EXPOSE 5173
# Run Vite dev server
CMD ["npm", "run", "dev", "--", "--host", "0.0.0.0"]




