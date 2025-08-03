# Intern-Portal
 Full Stack Job Portal App using ReactJS, Express, NodeJS and MongoDB.
Intern-Portal
Full Stack Job Portal App using ReactJS, Express, NodeJS and MongoDB.

#📌 **Features**

###For Applicants
Browse and search job postings.
Filter jobs by category.
View detailed job descriptions.
Apply to jobs and track application status.


###For Companies
Create and manage company profiles.
Post new job openings.
View and manage applications.


###Authentication
Secure user login and registration.
Session handling using JWT.

##Tech Stack

###Frontend
React (with Vite bundler)
Tailwind CSS
Axios for API requests

###Backend
Node.js & Express
MongoDB (with Mongoose ODM)
Cloudinary for media uploads


###Project Structure
jobportal-yt-main/ │ ├── backend/ # Express.js backend │ ├── controllers/ # Business logic │ ├── models/ # MongoDB models │ ├── routes/ # API endpoints │ ├── middlewares/ # Authentication & file handling │ ├── utils/ # Helper functions (DB, Cloudinary) │ ├── package.json # Backend dependencies │ └── index.js # Server entry point │ └── frontend/ # React frontend ├── src/ # React source code │ ├── components/ # UI components │ └── assets/ # Images and static files ├── package.json # Frontend dependencies └── vite.config.js # Vite configuration

###Prerequisites
Node.js (v16+ recommended)
MongoDB (local or Atlas)
Cloudinary account (for file uploads)
