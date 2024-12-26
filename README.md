# Mentor-Mentee Connection Platform

A vanilla JavaScript platform that connects mentors and mentees, facilitating meaningful professional relationships through a clean and intuitive interface.

## 🚀 Live Demo
[Platform Demo](https://mentor-mentee-platform-git-main-akshama2003s-projects.vercel.app/)

## ✨ Features

- User authentication with secure registration and login
- Comprehensive profile management for mentors and mentees
- Advanced user discovery with filtering capabilities
- Real-time connection request system
- Responsive design that works across all devices
- Pure vanilla implementation without external dependencies

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage for data persistence
- Custom form validation
- Responsive CSS Grid and Flexbox

## 🔧 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/mentor-mentee-platform.git
   cd mentor-mentee-platform
   ```

2. **Project Structure**
   ```
   mentor-mentee-platform/
   ├── index.html
   ├── style.css
   ├── script.js
   
   ```

3. **Local Development**
   - Open `index.html` in your preferred browser
   - No build process required
   - For local development, use a local server:
     ```bash
     python -m http.server 8000
     # or
     php -S localhost:8000
     ```

## 📋 Pages Description

### User Registration and Login
- Secure authentication system
- Input validation for all fields
- Password strength requirements
- Error handling and user feedback

### Profile Setup
- Role selection (mentor/mentee)
- Skills and interests input
- Bio and personal information
- Profile picture upload capability

### User Discovery
- Advanced filtering system
- Role-based search
- Skills matching
- Interest alignment

## 💡 Usage

1. **Registration**
   - Navigate to the signup page
   - Fill in required information
   - Verify email (if implemented)
   - Complete profile setup

2. **Profile Management**
   - Access profile through dashboard
   - Update information as needed
   - Add/remove skills and interests
   - Manage visibility settings

3. **Finding Connections**
   - Use discovery page filters
   - Send connection requests
   - Manage received requests
   - Track ongoing mentorships

## 🔒 Security Features

- Password hashing
- Input sanitization
- XSS protection
- CORS headers
- Form validation

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Configuration

### LocalStorage Schema
```javascript
{
  "users": [
    {
      "id": "unique-id",
      "role": "mentor/mentee",
      "skills": [],
      "interests": [],
      "connections": []
    }
  ]
}

📞 Support

For support, email chauhanaskhama@gmail.com 
