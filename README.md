<H1 align ="center" > Work Finder </h1>
<h5  align ="center"> 
Work Finder is a full-stack job portal web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The platform allows users to register, search for jobs, and apply directly. The system also supports two separate login portals: one for recruiters to post job opportunities and manage listings, and another for students to search for jobs and manage applications. </h5>
<br/>

  * [Configuration and Setup](#configuration-and-setup)
  * [Key Features](#key-features)
  * [Technologies used](#technologies-used)
      - [Frontend](#frontend)
      - [Backend](#backend)
      - [Database](#database)
  * [📸 Screenshots](#screenshots)
  * [Author](#author)
 


## Configuration and Setup

In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine.

- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the Frontend on one terminal and the Backend on the other terminal)

In the first terminal

```
$ cd Frontend
$ npm install (to install frontend-side dependencies)
$ npm run  start (to start the frontend)
```

In the second terminal

- cd Backend and Set environment variables in config.env under ./config
- Create your mongoDB connection url, which you'll use as your MONGO_URI
- Supply the following credentials

```
#  ---  Config.env  ---

NODE_ENV = development
PORT =5000
URI =http://localhost:3000
MONGO_URI =
JWT_SECRET_KEY =
CLOUD_NAME=dlbtwfubs
API_KEY=
API_SECRET=
``
# --- Terminal ---

$ npm install (to install backend-side dependencies)
$ npm start (to start the backend)
```

##  Key Features

-Dual Login Portals: Separate portals for recruiters and students.</br>
-Recruiter Portal: Allows recruiters to post job listings, manage job vacancies, and view applications.</br>
-Student Portal: Allows students to search for jobs, view detailed descriptions, and apply directly for jobs.
-User Authentication: Secure login and registration with JWT token authentication.
-Job Search: Students can search for jobs based on keywords, location, and other criteria.
-Job Application: Students can apply for jobs directly through the portal.
-State Management with Redux: Redux is used to manage global state across the application, enabling better state handling for job search results, user authentication status, and job applications.
-Responsive Design: Optimized for both desktop and mobile devices.

<br/>

## Technologies Used
This project was created using the following technologies:

Frontend
React.js - JavaScript library for building user interfaces, particularly for single-page applications.
React Router - Used for handling routing between pages.
Redux - State management library for managing global state across the application.
React-Redux - Official React bindings for Redux to manage state in the frontend.
Axios - For making API calls to the backend.
React Hooks - For managing state and lifecycle methods in functional components.
CSS - For styling the user interface.
React Icons - For adding icons to the UI.
Backend
Node.js - JavaScript runtime environment to build scalable network applications.
Express.js - Web framework for Node.js to handle HTTP requests and routing.
Mongoose - For modeling MongoDB data and performing database operations.
JWT (jsonwebtoken) - For secure user authentication and session management.
Bcryptjs - For password hashing and encryption.
Nodemailer - For sending emails (e.g., notifications for recruiters when students apply).
Dotenv - For managing environment variables.
Multer - Middleware for handling file uploads, if any.
Cors - Middleware to allow cross-origin requests.
Database
MongoDB - NoSQL database to store user, job, and application data.
 
 ##  Screenshots 
 

![1](https://github.com/user-attachments/assets/b282b26c-a635-4738-ac77-43dfa2c28f8d)
---- -
![2](https://github.com/user-attachments/assets/7075aa1a-9959-4171-bc5b-e01a1d36e3d4)
--- - 
![3](https://github.com/user-attachments/assets/a729ae3b-bdb6-4f29-9e29-afaa8c02553a)

--- - 
![4](https://github.com/user-attachments/assets/0040b56b-ad77-4ff2-a7d9-d197e41bf14e)

--- - 
![5](https://github.com/user-attachments/assets/6e25d23e-7d85-4928-8205-b02a33a709e8)

--- - 
## Author
- Portfolio: [Akash](https://gregarious-hummingbird-f1cf08.netlify.app/)
- Github: [Akash](https://github.com/akashkus121/blog2)
- Linkedin: [Akashkushwaha](https://www.linkedin.com/in/akash-kushwaha-35b812227/)
- Email: [908akashkushwaha@gmail.com](mailto:908akashkushwaha@gmail.com)

## License

MIT License

Copyright (c) 2024 Akash Kushwaha

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
