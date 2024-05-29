# StudyNotion

## Overview
**StudyNotion** is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. Built using the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS), StudyNotion aims to provide a seamless and interactive learning experience for students and a platform for instructors to showcase their expertise.

## Features
- **For Students**: Course browsing, wishlist, purchase, and content consumption.
- **For Instructors**: Course creation, management, and analytics.
- **For Admin** (future scope): Platform management and insights.

## System Architecture
StudyNotion consists of three main components: the front end, the back end, and the database. It follows a client-server architecture.

- **Front-end**: Built with ReactJS for dynamic and responsive user interfaces.
- **Back-end**: Built with NodeJS and ExpressJS for robust server-side applications.
- **Database**: MongoDB for flexible and scalable data storage.

## Front-end Details
The front end is designed using Figma for clean and minimal UI. It includes:

- **Student Pages**: Homepage, Course List, Wishlist, Cart Checkout, Course Content, User Details, and User Edit Details.
- **Instructor Pages**: Dashboard, Insights, Course Management, and Profile Management.
- **Admin Pages**: (future scope) Platform Dashboard, Insights, and User Management.

### Technologies Used
- **ReactJS**: For building the UI.
- **CSS & Tailwind**: For styling.
- **Redux**: For state management.
- **VSCode**: For development.

## Back-end Details
The back end uses a monolithic architecture with Node.js and Express.js. It provides functionalities such as:

- User authentication and authorization.
- Course management.
- Payment integration with Razorpay.
- Cloud-based media management with Cloudinary.
- Markdown formatting for course content.

### Technologies Used
- **Node.js**: Runtime environment.
- **Express.js**: Web application framework.
- **MongoDB**: NoSQL database.
- **JWT**: For authentication.
- **Bcrypt**: For password hashing.
- **Mongoose**: For database modeling.

## API Design
The platform's API follows REST principles. Here are some key endpoints:

- **Authentication**: `/api/auth/signup`, `/api/auth/login`, `/api/auth/verify-otp`, `/api/auth/forgot-password`
- **Courses**: `/api/courses`, `/api/courses/:id`, `/api/courses/:id/rate`

### Sample API Requests
- **GET /api/courses**: Fetch all courses.
- **POST /api/courses**: Create a new course.
- **PUT /api/courses/:id**: Update a course.
- **DELETE /api/courses/:id**: Delete a course.

## Deployment
The platform will be deployed using various cloud-based services:

- **Front-end**: Deployed on Vercel.
- **Back-end**: Hosted on Render or Railway.
- **Media Files**: Stored on Cloudinary.
- **Database**: Hosted on MongoDB Atlas.

## Future Enhancements
Potential improvements include:

1. **Gamification Features**: Badges, points, and leaderboards.
2. **Personalized Learning Paths**: Tailored learning experiences.
3. **Social Learning Features**: Group discussions and collaborative projects.
4. **Mobile App**: For convenient access.
5. **Machine Learning Recommendations**: Personalized course suggestions.
6. **VR/AR Integration**: Enhanced immersive learning experiences.

## Conclusion
StudyNotion is designed to provide an immersive learning experience for students and a platform for instructors to connect with learners globally. With its robust architecture and planned enhancements, StudyNotion aims to revolutionize the ed-tech space.

## Getting Started
To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/StudyNotion.git
