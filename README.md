# SocialMedia 

## Deployed Link
[https://social-media-iwu0.onrender.com/auth](https://social-media-iwu0.onrender.com/auth)

## Table of Contents
- [Setup Instructions](#setup-instructions)
- [Run the Project](#run-the-project)
- [Deploy the Project](#deploy-the-project)
- [Prerequisites](#prerequisites)
- [Dependencies](#dependencies)
- [Assumptions and Limitations](#assumptions-and-limitations)
- [Special Instructions](#special-instructions)

---

## Setup Instructions
Clone the repository:
`git clone <repository-url>`

Navigate to the project directory:
`cd project-directory`

Install server and frontend dependencies:
`npm install && npm install --prefix frontend`

## Run the Project
To start the development server, run:
`npm run dev`

## Deploy the Project
For production deployment, build and run the project:
`npm run build && npm start`

## Prerequisites
- Node.js and npm installed.
- MongoDB setup and running if the app uses a database.

## Dependencies
- Core dependencies:
  - `bcryptjs` for password hashing
  - `cloudinary` for image handling
  - `cookie-parser` for handling cookies
  - `dotenv` for environment variable management
  - `express` as the web server
  - `jsonwebtoken` for JWT handling
  - `mongoose` for MongoDB integration
  - `socket.io` for real-time communication
- Dev dependencies:
  - `cross-env` for setting environment variables across platforms
  - `nodemon` for live-reloading in development

## Assumptions and Limitations
- Assumes MongoDB is accessible and correctly configured.
- Requires Node.js 14.x or higher.

## Special Instructions
Ensure environment variables are configured in a `.env` file in the root directory.
Use `npm run dev` for development and `npm start` for production.
