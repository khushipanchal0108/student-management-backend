# Student Management System - Backend  

A Node.js and Express-based REST API for managing student data.  

## Features  
- User authentication (JWT-based)  
- CRUD operations for student records  
- Attendance tracking  
- Role-based access control (Admin, Teacher, Student)  
- API endpoints for announcements and notifications  

## Installation  

1. Clone the repository:  
   ```sh
   git clone https://github.com/yourusername/student-management-system-backend.git
   cd student-management-system-backend
   ```
2. Install dependencies:  
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:  
   ```
   PORT=5000  
   MONGO_URI=your_mongodb_connection_string  
   JWT_SECRET=your_secret_key  
   ```
4. Run the server:  
   ```sh
   npm start
   ```

## Tech Stack  
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- JWT for authentication  

## API Endpoints  
| Method | Endpoint            | Description                     |  
|--------|---------------------|---------------------------------|  
| POST   | `/api/auth/login`   | User login                      |  
| POST   | `/api/auth/register` | Register a new user             |  
| GET    | `/api/students`     | Get all students                |  
| POST   | `/api/students`     | Add a new student               |  
| PUT    | `/api/students/:id` | Update student details          |  
| DELETE | `/api/students/:id` | Delete a student record         |  

## Contributing  
Contributions are welcome. Please open an issue before submitting a pull request.  

## License  
This project is licensed under the MIT License.  
