﻿# [SkillAcademy](https://skillacademy-five-rho.vercel.app/) :- Unlocking Potential, Unleashing Success

Introducing my application SkillAcademy a Learning Management System (LMS) project – a complete solution built from scratch. Features include easy authentication (including Google login), user and course management, lecture management, admin dashboard, and a secure payment gateway.

### Experience the project presentation in action! [Click here](https://www.linkedin.com/posts/vikas-singh-varma-9b001a231_skillacademy-javascript-react-activity-7183393033516703744-9j0z?utm_source=share&utm_medium=member_desktop)  to watch Now.



## Features
### Authentication 
* Standard authentication
* Authentication with Google (Continue with Google)
* and Forgot Password Reset Password via email

### User Management
* The user has a personal profile section where they can view, edit, and manage their details

### Course Management
* Only the admin can create, update, and delete courses, while only enrolled users can consume the courses.

### Lecture Management
* Only the admin can add lectures to a course, update lectures, and delete lectures. Enrolled users are only permitted to consume the content.

### Admin Dashboard
#### * Comprehensive overview:
* Access detailed information about user activity, course performance, and financial transactions on one dashboard

### Payment Gateway
* Integration with a secure payment gateway for course enrollment

## Technologies Used

### Client Side 
* **React** :- for building the website.
* **Tailwind-CSS & DaisyUi** :- for Styling the website look good.
* **React-Router** :- for navigating between different pages on the website.
* **Redux-toolkit** :- for manage website's data and state
* **React-icons** :- for adds icons to the website for visual appeal.
* **React-hot-toast** :- for shows pop-up messages on the website.
* **React-chartjs-2 & Chart.js** :- for integrate charts on the admin dashboard, providing a visual representation of data.
* **Firebase** :- for users log in securely with Continue with Google.

### Server Side
* **Node.js & Express.js** :- for the core of the backend development.
* **MongoDB & Mongoose** :- database management for storing user data. 
* **JWT & Bcrypt** :- for Ensuring secure user authentication.
* **Multer & Cloudinary**: for Handling file uploads and storage. 
* **nodeMailer** :- for send emails.
* **Cookie-parser , cors , crypto and Many More**.

## Configuration 
***Configure your application using the following environment variables:***

### Client Side
***VITE_BASE_URL*** = set your backend Server url

#### ***Firebase Configuration***
* ***VITE_FIREBASE_API_KEY*** = firebase api key.
* ***VITE_AUTH_DOMAIN***= firebase auth domain.
* ***VITE_PROJECT_ID*** = firebase project id.
* ***VITE_STORAGE_BUCKET*** = firebase storage bucket. 
* ***VITE_MESSAGING_SENDER_ID*** = firebase messaging sender id.
* ***VITE_APP_ID*** = firebase app id.

### Server side 
* ***FRONTEND_URL*** = set your frontend url.
* ***PORT*** = port number.
* ***MONGO_URI*** = MongoDB connection URI.
* ***JWT_SECRET*** =  Set to a secure string for generating json web tokens.
* ***JWT_EXPIRY*** = token expiry.
* ***CONTACT_US_EMAIL*** = set  your cantact email.

####  ***Cloudinary Configuration***

* ***CLOUDINARY_CLOUD_NAME*** = Set to your Cloudinary cloud name.
* ***CLOUDINARY_API_KEY*** = Set to your Cloudinary API key.
* ***CLOUDINARY_API_SECRET*** = Set to your Cloudinary API secret.
* ***
####  ***SMTP Configuration***
* ***SMTP_SERVICE_NAME*** = set your SMTP service name.
* ***SMTP_HOST*** = set your SMTP host name.
* ***SMTP_PORT*** = set your SMTP port number.
* ***SMTP_USERNAME*** = set your SMTP username.
* ***SMTP_PASSWORD*** = set your SMTP Password.
* ***SMTP_FROM_EMAIL*** = set your SMTP FROM email address.

####  ***Payment Gateway Configuration***
***In this project i used Razorpay payment Gateway***
* ***RAZORPAY_KEY_ID*** = set your payment gateway key.
* ***RAZORPAY_SECRET*** = payment gateway seceret.
* ***RAZORPAY_PLAN_ID*** = payment gateway plan id.


## Installation
* Clone the repository 
### Server side 
* change directory to **LMS server** folder
* Install dependencies using **npm install**
* Set up environment variables **.env**
* Run the application using **npm run start** 
### Client side
* change directory to **frontend LMS** folder
* Install dependencies using **npm install**
* Set up environment variables **.env**
* Run the application using **npm run dev** 

## Usage

* Access the application through the provided URL
* Use the provided authentication methods to log in
* Explore available courses and enroll, All the courses accessable by purchasing subscription and the subscription valid for one year.
* Instructors can create and manage courses, mange lectures and all action perform via the admin dashboard.




***Made by 😎❤️ [Vi369](https://www.linkedin.com/in/vikas-singh-varma-9b001a231/)*** click and visit.


