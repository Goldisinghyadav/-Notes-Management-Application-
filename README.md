# Notes Management Application

A simple web application for managing notes with user authentication, built using Node.js, Express, MongoDB, and EJS.

## Features
- User registration and login
- Create, edit, view, and delete notes
- File upload support
- Authentication middleware
- Clean and responsive EJS views

## Folder Structure
```
├── middleware/         # Custom middleware (auth, upload)
├── models/             # Mongoose models (User, Note)
├── routes/             # Express route handlers
├── uploads/            # Uploaded files
├── Views/              # EJS templates
├── package.json        # Project metadata and dependencies
├── server.js           # Main server file
```

## Getting Started
1. **Clone the repository:**
   ```sh
   git clone https://github.com/Goldisinghyadav/-Notes-Management-Application-.git
   cd -Notes-Management-Application-
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Add your MongoDB URI and any other required variables:
     ```env
     MONGODB_URI=your_mongodb_connection_string
     SESSION_SECRET=your_secret
     ```
4. **Run the application:**
   ```sh
   node server.js
   ```
   The app will be available at `http://localhost:3000` by default.

## License
This project is licensed under the MIT License.
