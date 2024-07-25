<img width="100" height="100" style="border-radius: 50%; display: block;" alt="image" src="https://github.com/user-attachments/assets/e235ad8d-fa98-46b6-8f59-46391d5e0af5">


# FormsPro

FormsPro is a versatile platform designed for users to effortlessly create a wide range of forms tailored to their needs, accessed securely through unique codes. It offers a comprehensive dashboard that provides valuable insights into form responses, empowering businesses and individuals alike to gather and analyze data effectively. With a strong emphasis on security, FormsPro ensures robust data protection measures at every level. It employs industry-standard practices to safeguard user information, including encrypted data transmission and secure storage protocols. Forms created on FormsPro are equipped with advanced security features to prevent unauthorized access and ensure the integrity of collected data, making it a reliable choice for anyone prioritizing data security and form confidentiality.

## Features

- **Login/Signup Authentication using JWT**
  - Secure authentication for users.

- **Form Creation and Access**
  - Users can create forms and share unique codes to allow others to access and fill them.

- **Dashboard with Insights**
  - Comprehensive dashboard to view form responses and analyze data.

- **Responsive Design**
  - Mobile-friendly and accessible from any device.

- **File Uploads using Cloudinary**
  - Securely upload and store files.

- **Email Notifications using SMTP**
  - Send notifications to users about form updates and responses.

## Technologies Used

- ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) 
  - For database management.
- ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) 
  - For building the backend API.
- ![React.js](https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black) 
  - For building the frontend user interface.
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) 
  - For server-side scripting.
- ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white) 
  - For authentication.
- ![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white) 
  - For file uploads.
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) 
  - For responsive and visually appealing design.


## Demo
[<img src="https://www.shutterstock.com/image-vector/live-demo-icon-badge-label-600nw-2258199591.jpg" alt="FormsPro Demo" width="100px" />](https://formspro.vercel.app)




## Contributors

We acknowledge the exceptional teamwork and collaboration among all contributors involved in this project. The successful outcome of our endeavor is a testament to the collective effort and dedication of each team member.

- Bhavya S. Patel

## Setup Instructions

### Prerequisites

- Node.js and npm installed on your system.
- MongoDB installed and running.

### Backend Setup

#### Clone the Repository

```sh
git clone https://github.com/bhavu2412/form_school.git
cd formspro/backend
```
```sh
cd backend
npm install
```

Set Up Environment Variables
Create a .env file in the backend directory and add the following:
```sh
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
SMTP_HOST=your_smtp_host
SMTP_PORT=your_smtp_port
SMTP_USER=your_smtp_user
SMTP_PASS=your_smtp_pass
```

Run the Backend Server

```sh

npm start
```
Frontend Setup
Navigate to the Frontend Directory
```sh
cd frontend
```
Install Dependencies
```sh

npm install
```
Set Up Environment Variables

Create a .env file in the frontend directory and add the following:
```sh
REACT_APP_API_URL=http://localhost:5000
```
Run the Frontend Server

```sh
npm start
```
Running the Application
Start the Backend Server
```sh
cd backend
npm start
```
Start the Frontend Server
```sh
cd frontend
npm start
```
You can now access your FormsPro application at http://localhost:3000.

# Learn More

## React Documentation

React is a JavaScript library for building user interfaces. Learn more about React and its concepts:

- [React Documentation](https://reactjs.org/docs/getting-started.html)

## Express Documentation

Express.js is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications:

- [Express Documentation](https://expressjs.com/)

## MongoDB Documentation

MongoDB is a document-oriented NoSQL database used for high volume data storage. Learn more about MongoDB and its features:

- [MongoDB Documentation](https://docs.mongodb.com/)

## Node.js Documentation

Node.js is an open-source, cross-platform JavaScript runtime environment for executing JavaScript code server-side:

- [Node.js Documentation](https://nodejs.org/en/docs/)

## JavaScript Documentation

JavaScript is a high-level, interpreted programming language that conforms to the ECMAScript specification. Learn more about JavaScript:

- [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
