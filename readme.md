Todo Application Using MERN
=========================================

### A todo list made using MERN stack with user authentication.

<br>
<p>
<img alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white" /> <img alt="Nodejs" src="https://img.shields.io/badge/-Express-43853d?style=flat-square&logo=Express&logoColor=white" /> <img alt="Nodejs" src="https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=React&logoColor=white" /> <img alt="Nodejs" src="https://img.shields.io/badge/-Node.js-43853d?style=flat-square&logo=Node.js&logoColor=white" />
</p>

# Screenshots
![Add To Do](./assests//images/Screenshot_add-todo.jpg)
![Sign-Up Page](./assests/images/Screenshot_signup.jpg)
![Login Page](./assests//images/Screenshot_login.jpg)
![Update Profile](./assests/images/Screenshot-profile-update.jpg)

# Features
--------------

- User authentication with persistent Todos
- Responsive TailwindCSS design
- RESTful API
- Body / Params type checking

# Installation
Run the following command to clone the repository
```
# Clone
https://github.com/indiragothi/ToDo-App-For-Rise11
```
# Configuration
Create ```.env``` file inside ```backend``` directory and copy the following code

```
MONGO_URI=Your mongodb URI
GMAIL_USERNAME=your gmail address 
GMAIL_PASSWORD=password created inside 'App Password' section under google accounts setting
PORT=8000
JWT_SECRET=a random secret key eg. thisisasecretkey
```
# Run the App
Go to ```backend``` and ```frontend``` directory and start the server
```
cd backend
nodemon server
```
```
cd frontend
npm start
```
# Technologies Used

Review-System utilizes the following technologies:
- **Node.js:** JavaScript runtime for server-side development.
- **Express.js:** Web application framework for Node.js, facilitating API development.
- **React.js** Frontend library for building the user interface.
- **MongoDB:** NoSQL database for storing review data.
- **JWT:** JSON Web Tokens for authentication and authorization.
- **Tailwind CSS:** Utility-first CSS framework for styling components.
- **Redux:** State management library for handling application state.
- **Other Node.js packages:** Various npm packages for additional functionalities.
 