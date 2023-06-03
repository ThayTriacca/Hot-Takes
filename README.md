# Hot Takes
#### Build a Secure API for a Review App
<br>
<br>

![NodeJs](https://camo.githubusercontent.com/f3dc139d1f72935e63051e92a842c47c4b040004e3c4edf5430fbf8b3e1a6dd4/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e6f64652e6a732532302d2532333333393933332e7376673f267374796c653d666f722d7468652d6261646765266c6f676f3d6e6f64652e6a73266c6f676f436f6c6f723d7768697465)
![Express](https://camo.githubusercontent.com/eb95d456aab20b058cd38bcc21566f9d74d7ba56ca462ad6cb32387f0fd6893c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f457870726573732d3832383238323f7374796c653d666f722d7468652d6261646765266c6f676f3d65787072657373266c6f676f436f6c6f723d7768697465)
![MongoDB](https://camo.githubusercontent.com/930dd5089fa8e22c12dc4cc798c2b1c2999b131dc4b10547b815ad38b6523a63/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d6f6e676f64622d3531413334393f7374796c653d666f722d7468652d6261646765266c6f676f3d6d6f6e676f6462266c6f676f436f6c6f723d7768697465)
<br>

## About the project

The Secure Sauce API project provides a secure API for a pre-made front-end app. The app allows users to upload their favorite sauces, browse other sauces, and rate them. The back-end is developed in Node.js using Express and MongoDB.

## Project Purpose 

The purpose of this project was to create the back-end of the application, which includes building the API and implementing CRUD operations. The project focused on the following skills:

- Implementing a data model
- Storing data securely using a NoSQL database (MongoDB)
- Enabling users to interact with the database through CRUD operations
- Ensuring the security of user data and protecting it against web attacks

## External FrontEnd Repository
The frontend repository for this project has already been created and can be accessed [here](https://github.com/OpenClassrooms-Student-Center/Web-Developer-P6). Please refer to the frontend repository for detailed information on the frontend implementation.

# Project Setup
## Backend Setup
1. Clone this repository to your local machine.
2. Open a terminal and navigate to the project's root directory.
3. Install the project dependencies by running the command: npm install.
4. Configure the MongoDB connection by setting the MONGODB_URL environment variable. Use the following format as an example: 
```NodeJs
mongodb+srv://<username>:<password>@cluster0.dllcwvg.mongodb.net/
``` 
5. Save the MongoDB connection URL to the MONGODB_URL environment variable. This URL should include your MongoDB username, password, and cluster information.
6. Start the backend server by running the command: npm start.
7. The backend server should now be running on http://localhost:3000.

## Frontend Setup
1. Download the front-end repository from the provided [external link](https://github.com/OpenClassrooms-Student-Center/Web-Developer-P6).
2. Open a terminal and navigate to the frontend directory.
3. Install the project dependencies by running the command: npm install.
4. Start the frontend server by running the command: npm start.
5. The frontend server should now be running on http://localhost:4200.
