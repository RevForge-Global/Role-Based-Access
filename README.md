
# Role-Based Access Control System

A full-stack RBAC system built with React.js, Node.js, Express, and MongoDB.

## Roles & Permissions

| Role | Permissions |
|------|-------------|
| Super Admin | Full access — delete anything, manage users |
| Moderator | Delete any post or comment, cannot manage users |
| Regular User | Create posts & comments, edit/delete own content only |
| Guest | View/read only |

## Setup

### Backend
cd backend
npm install
node server.js

### Frontend
cd frontend
npm install
npm start

## Environment Variables
MONGO_URI=mongodb://localhost:27017/rbac_system
JWT_SECRET=your_secret_key
PORT=5000
