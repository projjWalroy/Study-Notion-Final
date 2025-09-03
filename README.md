# Study Notion Final — EdTech Platform

A modern, responsive **MERN stack** web application designed to facilitate online learning, course management, and student engagement.

## Overview

**Study Notion Final** is an educational technology platform that enables instructors to create, manage, and deliver courses, while providing students with a seamless interface to enroll, learn, and track their progress.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Authentication**: JWT (JSON Web Tokens)  
- **Payment Integration**: Razorpay  
- **State Management**: Redux Toolkit  
- **Form Handling**: React Hook Form  
- **Data Visualization**: Chart.js  
- **Deployment**: Vercel (Frontend), Heroku (Backend)  

## Features

- **User Authentication**: Secure login and registration with JWT.  
- **Course Management**: Instructors can create, update, and delete courses.  
- **Student Dashboard**: Students can enroll in courses, track progress, and view grades.  
- **Payment Gateway**: Integrated Razorpay for course purchases.  
- **Responsive Design**: Optimized for both desktop and mobile devices.  
- **Data Visualization**: Charts and graphs to track learning progress.  

## Project Structure

```

Study-Notion-Final/
├── public/               # Static assets
├── server/               # Backend API
│   ├── controllers/      # Route handlers
│   ├── models/           # Mongoose models
│   ├── routes/           # API routes
│   └── server.js         # Entry point
├── src/                  # Frontend source code
│   ├── components/       # Reusable components
│   ├── pages/            # React pages
│   ├── redux/            # Redux slices
│   ├── utils/            # Utility functions
│   └── App.js            # Main React component
├── .gitignore            # Git ignore file
├── package.json          # Project metadata and dependencies
└── tailwind.config.js    # Tailwind CSS configuration

````

## Installation

### Prerequisites

- Node.js (v14 or higher)  
- npm or yarn  
- MongoDB Atlas account (for cloud database)  

### Backend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/projjWalroy/Study-Notion-Final.git
   cd Study-Notion-Final
````

2. Navigate to the `server` directory and install dependencies:

   ```bash
   cd server
   npm install
   ```

3. Create a `.env` file in the `server` directory and add your environment variables:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   RAZORPAY_KEY_ID=your_razorpay_key_id
   RAZORPAY_KEY_SECRET=your_razorpay_key_secret
   ```

4. Start the backend server:

   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the `client` directory and install dependencies:

   ```bash
   cd client
   npm install
   ```

2. Create a `.env` file in the `client` directory and add your environment variables:

   ```env
   REACT_APP_API_URL=http://localhost:5000/api
   ```

3. Start the frontend development server:

   ```bash
   npm start
   ```

The application should now be running at `http://localhost:3000`.

## Running Tests

* **Backend**:

```bash
cd server
npm test
```

* **Frontend**:

```bash
cd client
npm test
```

## Deployment

* **Frontend**: Deployed on Vercel. Visit [Frontend Live](https://studynotion-frontend-sable.vercel.app)
* **Backend**: Deployed on Heroku. Ensure your Heroku app is connected to MongoDB Atlas with the correct environment variables.

## Contribution

Contributions are welcome!

1. Fork the repository.

2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add new feature"
   ```

4. Push to your fork:

   ```bash
   git push origin feature/your-feature
   ```

5. Open a Pull Request.

Please follow existing code style and include appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, contact:

* GitHub: [@projjWalroy](https://github.com/projjWalroy)
* Email: [projjwal.roy1@gmail.com](mailto:projjwal.roy1@gmail.com)

