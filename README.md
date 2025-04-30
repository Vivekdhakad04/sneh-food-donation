# Sneh Food Donation Platform

A full-stack web application for managing food donations, connecting donors with organizations, and coordinating volunteer efforts.

## 🌟 Features

- **User Authentication**
  - Registration and login for donors, organizations, and volunteers
  - Role-based access control
  - Secure password handling with JWT authentication

- **Food Donation Management**
  - Donors can list available food items
  - Organizations can view and accept donations
  - Real-time status tracking
  - Aadhar verification for security

- **Volunteer Coordination**
  - Volunteer registration and profile management
  - Task assignment and tracking
  - Performance monitoring

- **Admin Dashboard**
  - User management
  - Donation tracking
  - Volunteer management
  - Analytics and reporting

## 🚀 Tech Stack

### Frontend
- React.js
- Material-UI
- React Router
- Axios
- Framer Motion
- React Toastify

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Cloudinary (for file uploads)
- Multer (for file handling)

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- Git

### Frontend Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/sneh-food-donation.git

# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

### Backend Setup
```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create .env file with the following variables
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=30d
PORT=5000
FRONTEND_URL=http://localhost:5173
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

# Start development server
npm run dev
```

## 🔧 Environment Variables

### Frontend (.env)
```
VITE_API_URL=http://localhost:5000
```

### Backend (.env)
```
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=30d
PORT=5000
FRONTEND_URL=http://localhost:5173
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

## 📚 API Documentation

### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login user
- `GET /api/auth/me` - Get current user

### Food Donations
- `POST /api/food-donations` - Create a new donation
- `GET /api/food-donations` - Get all donations
- `GET /api/food-donations/:id` - Get donation by ID
- `PUT /api/food-donations/:id` - Update donation status

### Volunteers
- `POST /api/volunteers/register` - Register as volunteer
- `GET /api/volunteers/profile` - Get volunteer profile
- `PUT /api/volunteers/profile` - Update volunteer profile

### Organizations
- `GET /api/organizations` - Get all organizations
- `POST /api/organizations` - Create new organization
- `GET /api/organizations/:id` - Get organization by ID

## 🚀 Deployment

### Frontend (Vercel)
- Automatic deployment from GitHub
- Environment variables set in Vercel dashboard
- Custom domain configuration

### Backend (Render)
- Manual deployment with render.yaml
- Environment variables set in Render dashboard
- Automatic SSL configuration

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Your Name - Vivek Dhakad

## 🙏 Acknowledgments

- Special thanks to my teammates(Abhishek,Tanishq and Tamanna)
