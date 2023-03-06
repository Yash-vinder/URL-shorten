# URL-shorten

This is a simple URL shortening web application created using React and Node.js.

# Features
Shorten long URLs to a short and easy-to-remember URL
Track the number of clicks on each shortened URL
View a list of all shortened URLs and their click counts
Delete shortened URLs from the list

# Installation
Clone the repository to your local machine
Navigate to the root directory of the project
Install dependencies for the server using npm init -y
Navigate to the client directory and install dependencies for the client using npm install

# Usage
Start the server by running node index.js in the urlbackend directory of the project
Start the client by running npm start in the urlfrontend directory
Open your web browser and go to http://localhost:3000 to use the URL shortener

# Dependencies
# Server
cors 
dotenv 
express 
mongoose 
shortid

cors: Cross-origin resource sharing (CORS) allows AJAX requests to skip the Same-origin policy and access resources from remote hosts. Comes in handy while connecting the Node.js server to the Client (frontend) side.
dotenv: This loads environment variables from a .env file into process.env.
express: A Node.js framework that provides broad features for building web and mobile applications.
mongoose: An object modeling tool that aids in connecting and querying the MongoDB database.
shortid: Generates non-sequential short unique ids

# Client
axios
bootstrap

axios: is a promised-based HTTP client for JavaScript. It has the ability to make HTTP requests from the browser and handle the transformation of request and response data.
bootstrap: a powerful, feature-packed frontend toolkit for styling our application and helps create an elegant responsive layout.


Fork the repository
Create a new branch for your changes
Make your changes and commit them with descriptive commit messages
Push your changes to your forked repository
Create a pull request to the original repository with a clear description of your changes





