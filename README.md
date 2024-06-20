# Full Stack Notes App

## Overview

This project is a Full Stack Notes App built using the MERN stack (MongoDB, Express, React JS, Node JS). The app is designed for personal note-taking and includes features such as user authentication (Login & Sign Up), CRUD functionalities for notes, pinning important notes to the top, and efficient search capabilities.

## Features

- User Authentication (Login & Sign Up)
- Add, Edit, and Delete Notes
- Pin Important Notes to the Top
- Search Through Notes

## Technologies Used

- **MongoDB**: For database management
- **Express**: For back-end server and API
- **React JS**: For front-end user interface
- **Node JS**: For back-end runtime environment

## Installation

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed and running

### Steps

1. **Clone the Repository**

   ```sh
   git clone https://github.com/nishchintmakode/notes.git
   cd notes-app
   ```

2. **Backend Setup**

   ```sh
   cd backend
   npm install
   ```

3. **Frontend Setup**

   ```sh
   cd ../frontend
   npm install
   ```

4. **Environment Variables**

   - Create a `.env` file in the `backend` directory with the following variables:
     ```
     MONGO_URI=<your-mongodb-uri>
     JWT_SECRET=<your-jwt-secret>
     ```

5. **Running the Application**
   - Start the backend server
     ```sh
     cd backend
     npm start
     ```
   - Start the frontend development server
     ```sh
     cd ../frontend
     npm start
     ```

## Usage

- Navigate to `http://localhost:3000` in your browser to use the application.
- Sign up or log in to your account.
- Add, edit, or delete notes as needed.
- Pin important notes to the top for easy access.
- Use the search bar to quickly find notes.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact [nishchintsmakode@gmail.com](mailto:nishchintsmakode@gmail.com).
