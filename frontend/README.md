# MakeMyTrip Frontend

React frontend for the MakeMyTrip application with Tailwind CSS styling.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm start
```

3. Build for production:
```bash
npm run build
```

## Pages & Components

- **Home** - Displays all community posts
- **Login** - User login page
- **Register** - User registration page
- **Dashboard** - User's personal dashboard with posts
- **Navbar** - Navigation component
- **PostForm** - Form to create new posts
- **PostList** - Display posts with edit/delete functionality

## Environment

Update API base URL in `src/services/api.js` if needed:
```javascript
const API_BASE_URL = 'http://localhost:5000/api';
```

## Features

- User authentication with JWT
- Protected routes
- Create, read, update, delete posts
- Responsive design with Tailwind CSS
- Form validation
