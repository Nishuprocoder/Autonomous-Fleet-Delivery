# Autonomous Fleet Delivery System

A modern web application for managing and monitoring autonomous delivery fleets.

## Features

- Real-time fleet tracking
- Route optimization
- Delivery status monitoring
- Driver management
- Analytics dashboard
- Real-time notifications

## Tech Stack

### Frontend
- React.js
- Material-UI
- Redux for state management
- React Router for navigation
- Axios for API calls

### Backend
- Node.js
- Express.js
- MongoDB
- Socket.IO for real-time updates
- JWT for authentication

## Project Structure

```
autonomous-fleet-delivery/
├── frontend/               # React frontend application
│   ├── public/            # Static files
│   └── src/              # Source files
│       ├── components/   # Reusable components
│       ├── pages/        # Page components
│       ├── services/     # API services
│       ├── store/        # Redux store
│       └── utils/        # Utility functions
│
├── backend/              # Node.js backend application
│   ├── src/             # Source files
│   │   ├── controllers/ # Route controllers
│   │   ├── models/      # Database models
│   │   ├── routes/      # API routes
│   │   ├── services/    # Business logic
│   │   └── utils/       # Utility functions
│   └── config/          # Configuration files
│
└── docs/                # Documentation
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm run install-all
   ```
3. Start the development servers:
   ```bash
   npm start
   ```

## Environment Variables

Create `.env` files in both frontend and backend directories with the following variables:

### Backend (.env)
```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

### Frontend (.env)
```
REACT_APP_API_URL=http://localhost:5000
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request 