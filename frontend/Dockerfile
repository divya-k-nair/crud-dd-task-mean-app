# Stage 1: Build Angular app
FROM node:20 AS build

WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy all frontend source code
COPY . .

# Build Angular app for production
RUN npm run build -- --configuration production


# Stage 2: Serve with Nginx
FROM nginx:alpine

# Copy build output (auto-detect folder)
COPY --from=build /app/dist/angular-15-crud /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

