# Creators Platform API

This is the backend API for the Creators Platform, a MERN stack application.

## Deployment

The API is configured to be deployed on Render.

### Environment Variables

Required environment variables for production:

- `MONGO_URI`: Your MongoDB Atlas connection string.
- `JWT_SECRET`: Secret key for JWT authentication.
- `CLIENT_URL`: The URL of your frontend application.
- `NODE_ENV`: Set to `production`.

### Start Script

Run the following command to start the server:

```bash
npm start
```

## Features

- User Authentication (JWT)
- Creator Profiles
- Content Management
- Multi-tenant isolation (Tenant ID)
