# StudyNotion-Backend

This repository is the backend of *StudyNotion*. StudyNotion is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. The backend is developed using Node.js and Express.js, and MongoDB as the primary database.

## Features and Functionalities of the Back-end:

1. User authentication and authorization: Students and instructors can sign up and log in to the platform using their email addresses and password. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
2. Course management: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
3. Payment Integration: Students will purchase and enrol on courses by completing the checkout flow that is followed by Razorpay integration for payment handling.
4. Cloud-based media management: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
5. Markdown formatting: Course content in document format is stored in Markdown format, which allows for easier display and rendering on the front end.


## List of API endpoints and their functionalities:

1. /api/auth/signup (POST) - Create a new user (student or instructor) account.
2, /api/auth/login (POST) – Log in using existing credentials and generate a JWT token.
3. /api/auth/verify-otp (POST) - Verify the OTP sent to the user's registered email.
4. /api/auth/forgot-password (POST) - Send an email with a password reset link to the registered email.
5. /api/courses (GET) - Get a list of all available courses.
6. /api/courses/:id (GET) - Get details of a specific course by ID.
7. /api/courses (POST) - Create a new course.
8. /api/courses/:id (PUT) - Update an existing course by ID.
9. /api/courses/:id (DELETE) - Delete a course by ID.
10. /api/courses/:id/rate (POST) - Add a rating (out of 5) to a course.


## Frameworks, Libraries, and Tools used:

- Node.js: Node.js is used as the primary framework for the back end.
- MongoDB: MongoDB is used as the primary database, providing a flexible and scalable data storage solution.
- Express.js: Express.js is used as a web application framework, providing a range of features and tools for building web applications.
- JWT: JWT (JSON Web Tokens) are used for authentication and authorization, providing a secure and reliable way to manage user credentials.
- Bcrypt: Bcrypt is used for password hashing, adding an extra layer of security to user data.
- Mongoose: Mongoose is used as an Object Data Modeling (ODM) library, providing a way to interact with MongoDB using JavaScript.


