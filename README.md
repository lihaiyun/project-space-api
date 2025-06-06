# project-space-api

Backend Web API built with Node.js and Express, using MongoDB for data storage and Cloudinary for image management.

## Technologies

- **Node.js** & **Express**: Backend server and routing
- **MongoDB**: NoSQL database
- **Cloudinary**: Image hosting and management
- **JWT (JSON Web Token) Cookie**: Authentication mechanism

## Prerequisites

- Node.js (v14+)
- MongoDB instance (local or cloud)
- Cloudinary account

Frontend Web App repo: [https://github.com/lihaiyun/project-space-app](https://github.com/lihaiyun/project-space-app)

## Installation

```bash
npm i
```

## Setup
Copy `.env.example` to `.env` and update the environment variables as needed.

You need to set up a MongoDB database, either locally or using the cloud [MongoDB Atlas](https://www.mongodb.com/atlas).  
Update the `MONGODB_URI` variable in your `.env` file with your database connection string.
You can use the [MongoDB Compass](https://www.mongodb.com/products/compass) app to test the database connection.

For `APP_SECRET`, you can generate a secure value using an online tool like [uuidtools.com/v4](https://www.uuidtools.com/v4).

Get your Cloudinary credentials (`CLOUDINARY_CLOUD_NAME`, `CLOUDINARY_API_KEY`, `CLOUDINARY_API_SECRET`) from your [Cloudinary account](https://cloudinary.com/).

## Run

```bash
npm run dev
```

## Deployment
This Web API can be deployed to [Render](https://render.com/).

To deploy, push your repository to GitHub and connect it to Render.
