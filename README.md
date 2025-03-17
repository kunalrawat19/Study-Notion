# StudyNotion

## Overview
StudyNotion is a full-stack EdTech platform designed to create a comprehensive learning ecosystem for students and instructors. The platform enables seamless user authentication, intuitive course browsing, and secure buying/selling of courses, fostering an engaging online learning experience.

## Features
- **User Authentication:** Secure login and registration using JWT authentication.
- **Course Management:** Students can browse, purchase, and access courses, while instructors can create and list courses.
- **Payment Integration:** Razorpay integration for seamless and secure transactions.
- **Security Measures:** Password hashing, JWT-based authentication, and cookie-based session management.
- **Media & Data Handling:** Cloudinary integration for efficient multimedia storage and retrieval.
- **State Management:** Implemented Redux for a smooth and scalable user experience.

## Tech Stack
- **Frontend:** React.js, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT & Cookies
- **Payment Gateway:** Razorpay
- **Cloud Storage:** Cloudinary

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/studynotion.git
   cd studynotion
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   RAZORPAY_KEY=your_razorpay_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```
4. Run the development server:
   ```sh
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.





