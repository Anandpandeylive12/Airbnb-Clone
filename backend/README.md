# Airbnb Backend

This is the backend API for an Airbnb-like application.  
It is built with Node.js, Express, and MongoDB.

## Features

- User authentication (signup, login, logout)
- Listing management (add, update, delete, search, rate)
- Booking management (create, cancel)
- Image upload (Cloudinary + Multer)
- JWT-based authentication

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```
2. Create a `.env` file with your environment variables:
   ```
   PORT=6000
   MONGODB_URL=your_mongodb_url
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```
3. Start the server:
   ```
   npm run dev
   ```

## Folder Structure

- `controllers/` - Route handlers
- `model/` - Mongoose models
- `routes/` - API routes
- `middleware/` - Express middleware
- `config/` - Configuration files

## API Endpoints

See the route files for details.
