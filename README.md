
# LearnDash

LearnDash is a fully functional ed-tech platform built using the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS). It aims to provide a seamless and interactive learning experience for students while allowing instructors to showcase their expertise and connect with learners globally.

## Frontend Features

### For Students

- Homepage: Brief introduction to the platform and Links to the course list and user details.
- Course List: Displays all available courses with descriptions and ratings.
- Wishlist: Shows courses added to the student’s wishlist.
- Cart Checkout: Allows users to complete course purchases.
- Course Content: Provides course materials, including videos and related content.
- User Details: Displays account information (name, email, etc.).
- User Edit Details: Allows students to edit their account details.

### For Instructors

- Dashboard: Overview of the instructor’s courses and ratings and feedback for each course.
- Insights: Detailed metrics (views, clicks) for instructor’s courses.
- Course Management Pages: Create, update, and delete courses and manage course content and pricing.
- View and Edit account: Instructor’s account information.

## Backend Features

- User Authentication and Authorization: Sign up and log in using email and password. OTP verification and forgot password functionality.
- Course Management: Instructors can CRUD courses. Students can view and rate courses.
- Payment Integration: Razorpay integration for secure payment handling.
- Cloud-Based Media Management: Cloudinary used for storing and managing media (images, videos, documents).
- Markdown Formatting: Course content stored in Markdown format for easy rendering on the frontend.

## Tech Stack

### Frontend
- ReactJS: Building dynamic and responsive user interfaces.
- Redux: State management for a seamless experience.
- HTML/CSS: Structuring and styling the application.
### Backend:
- Node.js: Primary backend framework.
- MongoDB: Flexible and scalable database.
- Express.js: Web application framework.
- JWT: JSON Web Tokens for authentication.
- Bcrypt: Password hashing for security.
- Mongoose: ODM library for MongoDB.

## Environment Variables

To run this project, you will need to add the following environment variables to your
- server's .env file

`MAIL_HOST`
`MAIL_USER` 
`MAIL_PASS`

`JWT_SECRET`
`FOLDER_NAME`

`RAZORPAY_KEY`
`RAZORPAY_SECRET`

`CLOUD_NAME`
`API_KEY`
`API_SECRET`

`MONGODB_URL`
`PORT`

- client's .env file

`REACT_APP_BASE_URL`
`REACT_APP_RAZORPAY_KEY`


## Run Locally

Clone the project

```bash
  git clone https://github.com/SanidhyaDiwakar/LearnDash
```

Go to the server folder

```bash
  cd server
```

Install dependencies

```bash
  npm install
```
Go to the main folder

```bash
  cd ..
```

Install dependencies

```bash
  npm install
```

Run the project

```bash
  npm run dev
```

