# Node.js API with MongoDB

This project is a simple Node.js Express API that connects to a MongoDB database and retrieves user data. The GET endpoint /users/:id returns user details if the user exists and their age is greater than 21. Invalid ObjectId formats and missing users are gracefully handled.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/raviteja096/Centivo.git
   cd nodejs-mongo-api
2. Install dependencies:
   ```bash
   npm install
3. Update the MongoDB connection string in index.js (for local MongoDB or MongoDB Atlas).

4. Start the server:
   ```bash
   npm start
5. Test the endpoint at http://localhost:3000/users/<userId>
