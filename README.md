# Hirred - MERN Stack Job Portal App

Hirred is a dynamic and user-friendly job portal application designed to streamline the recruitment process. Built entirely with the MERN stack, the platform connects job seekers and recruiters with advanced features such as job filtering, application tracking, and user profile management.

## Features

### For Students (Job Seekers)
- Create and manage user profiles.
- Browse and filter job listings by category, location, or job type.
- Apply to jobs with a single click.
- Track the status of job applications.

### For Recruiters
- Post job openings with detailed descriptions.
- Manage job postings through an intuitive dashboard.
- View and update the status of applications.

### General Features
- Secure authentication and authorization.
- Responsive design for optimal user experience.
- Fast and efficient performance.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js and Express.js
- **Database**: MongoDB
- **Version Control**: Git and GitHub

## Installation

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/hirred.git
   cd hirred
   ```

2. **Install dependencies:**
   - For the frontend:
     ```bash
     cd frontend
     npm install
     ```
   - For the backend:
     ```bash
     cd backend
     npm install
     ```

3. **Set up the environment variables:**
   - Backend:
     Create a `.env` file in the `backend` folder and add the following:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret_key
     ```

4. **Start the application:**
   - Run MongoDB server:
     ```bash
     mongod
     ```
   - Start the backend:
     ```bash
     cd backend
     npm run dev
     ```
   - Start the frontend:
     ```bash
     cd frontend
     npm run dev
     ```

5. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`.

## Folder Structure

```
Hirred/
├── backend/       # Backend code (Node.js and Express.js)
│   ├── models/    # Mongoose models
│   ├── routes/    # API routes
│   └── controllers/ # Request handlers
├── frontend/      # Frontend code (React.js)
│   ├── src/
│   │   ├── components/ # React components
│   │   ├── pages/      # Application pages
│   │   └── assets/     # Static assets (e.g., images, styles)
├── README.md      # Project documentation
└── package.json   # Project metadata
```

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch.
4. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [MongoDB](https://www.mongodb.com/)
- [React.js](https://reactjs.org/)
