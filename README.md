# Task Management System

## Live Links
- [Server Link](https://task-manegement-server.vercel.app/)

## Description
A comprehensive task management system built with Node.js and Express.js for the backend, and React for the frontend. This application allows users to efficiently manage their tasks, track progress, and organize their work.

## Features
- User Authentication & Authorization
- Task Creation, Update, and Deletion
- Task Status Management
- Task Priority Levels
- Task Categories/Labels
- User Dashboard
- Responsive Design
- Secure API Integration

## Technologies Used

### Backend
- Node.js
- Express.js
- MongoDB
- JSON Web Token (JWT)
- Cors
- Dotenv
- Express Rate Limit
- Mongoose

### Frontend
- React.js
- Tailwind CSS
- DaisyUI
- React Router DOM
- Axios
- React Icons
- React Hot Toast
- Firebase Authentication

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/task-management-system.git
```
2. Install dependencies
```bash
npm install
```
3. Run the server
```bash
npm run start
```

## API Endpoints

### Auth Routes
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | /api/auth/register | Register new user |
| POST   | /api/auth/login | User login |

### Task Routes
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /api/tasks | Get all tasks |
| POST   | /api/tasks | Create new task |
| PUT    | /api/tasks/:id | Update task |
| DELETE | /api/tasks/:id | Delete task |

### User Routes
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /api/users/profile | Get user profile |
| PUT    | /api/users/profile | Update user profile |

## Error Handling
The application includes comprehensive error handling:
- Input validation
- Authentication errors
- Database errors
- Server errors

## Security Features
- JWT Authentication
- Password Hashing
- Rate Limiting
- CORS Configuration
- Environment Variables
- Input Sanitization

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Contact
- Your Name: [Your Full Name]
- Email: [your.email@example.com]
- LinkedIn: [Your LinkedIn Profile]
- Project Link: [https://github.com/yourusername/task-management-system](https://github.com/yourusername/task-management-system)

## Acknowledgments
- Thanks to all contributors who have helped with this project
- Special thanks to the open-source community
- [Any other acknowledgments]
