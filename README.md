# URL-Shortener

This is a simple URL shortener application built using Express, Node.js, Nodemon, and MongoDB. It allows users to shorten long URLs into short and easy-to-share links.

## Installation

1. Clone the repository:
   
   ```
   git clone https://github.com/your-username/url-shortener.git
   ```
   
2. Install the dependencies:

   ```
   cd url-shortener
   npm install
   ```
   
3. Configure the MongoDB connection:
   -Make sure you have MongoDB installed and running on your system.
   -Open the `config.js` file and update the MongoDB URI to point to your MongoDB server.
   
## Usage

1. Start the Application

   ```
   npm start
   ```
   This will start the server on http://localhost:8001.
   
   1. Open your web browser and navigate to http://localhost:8001 to access the URL shortener application.
   2. Shorten a URL:
      -Enter a long URL into the provided input field on the homepage.
      -Click the "Shorten" button to generate a shortened URL.
      -The shortened URL will be displayed below the input field.
   3. Access a shortened URL:
      -Copy the shortened URL and share it with others.
      -When someone accesses the shortened URL, they will be redirected to the original long URL.
