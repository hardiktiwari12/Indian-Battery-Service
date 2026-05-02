# Indian Battery Service

This is a complete modern full-stack web application project for an Indian Battery Service business.

## Project Structure

```
Indian-Battery-Service/
├── backend/
│   ├── config/
│   │   └── db.js               # Database connection setup
│   ├── controllers/
│   │   └── userController.js   # User-related logic
│   ├── models/
│   │   └── User.js             # User model
│   ├── routes/
│   │   └── userRoutes.js       # User routes
│   ├── middleware/
│   │   └── authMiddleware.js    # Authentication middleware
│   ├── .env                     # Environment variables
│   ├── server.js                # Main server file
│   └── package.json             # Backend dependencies
├── frontend/
│   ├── public/                  # Static files
│   ├── src/
│   │   ├── components/          # React components
│   │   ├── pages/               # Next.js pages
│   │   ├── styles/              # CSS styles
│   │   └── utils/               # Utility functions
│   ├── .env.local               # Frontend environment variables
│   ├── next.config.js           # Next.js configuration
│   ├── package.json             # Frontend dependencies
│   └── README.md                # Project information
└── README.md                    # Overall project documentation
```

## Setup Instructions

1. Clone the repository.
2. Navigate to the `backend` and `frontend` folders to set up each with `npm install`.
3. Create environment variable files with necessary configurations.
4. Start the backend server and frontend application.

## License

Specify your license information here.