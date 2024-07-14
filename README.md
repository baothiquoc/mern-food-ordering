# MERN Food Ordering

A full-stack food ordering application built using the MERN stack (MongoDB, Express.js, React, Node.js).

### Demo: https://youtu.be/7YezMvqI0_g

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [Database Setup](#database-setup)
- [Auth0 Setup](#auth0-setup)
- [Deployment](#deployment)
- [Environment Variables](#environment-variables)
- [Additional Resources](#additional-resources)

## Introduction
This project is a comprehensive food ordering application. Users can browse restaurants, view menus, add items to the cart, and place orders. The application includes authentication via Auth0, image hosting with Cloudinary, and payment processing using Stripe.

## Technologies Used
- **Frontend**: React, Vite, Shadcn
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Auth0
- **Payment Processing**: Stripe
- **Image Hosting**: Cloudinary
- **Deployment**: Render

## Setup Instructions

### Backend Setup
1. Clone the backend repository:
   ```sh
   git clone https://github.com/baothiquoc/mern-food-ordering.git
   cd backend
2. Install dependencies:
    ```sh
    npm install
3. Set up enviroment variables:
    Create a `.env` file in the root of the backend directory and add ypur enviroment variables.
4. Start the backend server:
    ```sh
    npm run dev
### Frontend Setup
1. Clone the frontend repository:
    ```sh
    git clone https://github.com/baothiquoc/mern-food-ordering.git
    cd fontend
2. Install dependencies:
    ```sh
    npm install
3. Set up environment variables:
    Create a `.env` file in the root of the frontend directory and add your environment variables.
4. Start the frontend server:
    ```sh
    npm run dev
### Database Setup
1. Set up MongoDB:
    Follow the instructions on [MongoDB](https://mongodb.com) to create your database.
### Auth0 Setup
1. Create an Auth0 account at [Auth0](https://auth0.com).
2. Follow the Auth0 setup instrucitons to configure your application.
### Deployment
1. Deploy the backend to Render:
    Forllow the instructions on [Render](https://render.com) to deploy your backend application.
2. Deploy the frontend to Render:
    Follow the instructions on [Render](https://render.com) to deploy your frontend application.
## Environment Variables
Create a `.env` file in the root of both your backend and frontend directories and add the following environment variables:

### Backend Environment Variables
    MONGODB_CONNECTION_STRING=<Your MongoDB Connection String>
    AUTH0_AUDIENCE=<Your Auth0 Audience>
    AUTH0_ISSUER_BASE_URL=<Your Auth0 Issuer Base URL>
    CLOUDINARY_CLOUD_NAME=<Your Cloudinary Cloud Name>
    CLOUDINARY_API_KEY=<Your Cloudinary API Key>
    CLOUDINARY_API_SECRET=<Your Cloudinary API Secret>
    FRONTEND_URL=http://localhost:5173
    STRIPE_API_KEY=<Your Stripe API Key>
    STRIPE_WEBHOOK_SECRET=<Your Stripe Webhook Secret>
### Frontend Environment Variables
    VITE_API_BASE_URL=http://localhost:3000

    VITE_AUTH0_DOMAIN=<Your Auth0 Domain>
    VITE_AUTH0_CLIENT_ID=<Your Auth0 Client ID>
    VITE_AUTH0_CALLBACK_URL=http://localhost:5173
    VITE_AUTH0_AUDIENCE=<Your Auth0 Audience>
    
## Additional Resources
- [React/Vite/Shadcn Installation](https://ui.shadcn.com/docs/installation)
- [Stripe Test Cards](https://stripe.com/docs/testing#international-cards)
- [Stripe CLI](https://stripe.com/docs/stripe-cli?locale=en-GB)
- [Cloudinary](https://cloudinary.com/)
- [MongoDB](https://mongodb.com)










