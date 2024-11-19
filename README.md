# 🚗 Car Management System

A full-stack web application for managing car listings, featuring a Vue.js frontend and Node.js/Express backend with JWT authentication, advanced search capabilities, and image handling.

## 🌟 Features

### Frontend Features
- **Modern UI/UX**
  - Responsive design with Tailwind CSS
  - Dynamic routing with Vue Router
  - State management with Vuex
  - Form validation and error handling
  - Real-time search and filtering

### Backend Features
- **🔐 Authentication & Authorization**
  - JWT-based authentication
  - Role-based access control
  - Secure password hashing
  - Token refresh mechanism

- **🚙 Car Management**
  - CRUD operations for car listings
  - Multi-image upload with validation
  - Advanced filtering and search
  - Pagination and sorting
  - Tag-based categorization

## 🛠 Tech Stack

### Frontend
- Vue.js 3
- Vite (Build Tool)
- Tailwind CSS
- Vuex (State Management)
- Vue Router

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Multer (Image Processing)
- Swagger/OpenAPI
- Jest (Testing)
- Mongoose (ODM)

## 📋 Prerequisites

- Node.js (v14 or higher)
- MongoDB (v4.4 or higher)
- npm or yarn
- Git

## 💻 Installation & Setup

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/car-management-system.git
cd car-management-system
```

2. **Backend Setup**
```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create .env file
echo "PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@<cluster>/<database>
JWT_SECRET=<your_secret_key>" > .env

# Start the server
npm start
```

3. **Frontend Setup**
```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

## 🚀 Usage

### Frontend Access
- Development: `http://localhost:5173`
- Production: Build with `npm run build`

### Backend API Access
- Local: `http://localhost:5000`
- API Documentation: `http://localhost:5000/api/docs`

## 📁 Project Structure

```
car-management-system/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── views/
│   │   ├── router/
│   │   ├── store/
│   │   └── assets/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── utils/
│   ├── tests/
│   └── package.json
```

## 🔌 API Endpoints

### Authentication
- POST `/api/auth/register` - User registration
- POST `/api/auth/login` - User login

### Car Management
- GET `/api/cars` - List all cars
- GET `/api/cars/:id` - Get car details
- POST `/api/cars` - Create new car listing
- PATCH `/api/cars/:id` - Update car listing
- DELETE `/api/cars/:id` - Delete car listing

## 🔐 Frontend Routes

| Route | Description |
|-------|-------------|
| `/` | Home page |
| `/login` | User login |
| `/register` | User registration |
| `/car/create` | Create new car listing |
| `/car/:id/` | Edit car listing |


## 🧪 Testing

### Backend Testing
```bash
cd backend
npm test
```

### Frontend Testing
```bash
cd frontend
npm run test
```

## 📦 Deployment

### Backend Deployment
```bash
cd backend
npm run build
npm start
```

### Frontend Deployment
```bash
cd frontend
npm run build
```
The `dist` folder will contain the built application ready for deployment.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 👨‍💻 Author

Kuldeep Raj Gour  
Email: kuldeepgour002@gmail.com

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Vue.js team for the frontend framework
- Express.js team for the backend framework
- MongoDB team for the database
- All contributors who help improve this project