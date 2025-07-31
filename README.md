# 🍽️ Food Ordering Web Application

![Food Ordering Web App](https://github.com/user-attachments/assets/06f6422f-2fa0-4b6f-a6b1-ff1fce770392)

A modern web application for ordering food online, built with a focus on user experience and seamless ordering process.

## 🚀 Features

- **User Authentication** - Secure signup and login functionality
- **Menu Browsing** - Browse food items by categories
- **Cart Management** - Add/remove items and adjust quantities
- **Order Tracking** - Real-time order status updates
- **Responsive Design** - Works on desktop, tablet, and mobile devices
- **Admin Dashboard** - Manage menu, orders, and user accounts

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript, React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Integration**: Stripe/Razorpay
- **Deployment**: Netlify/Vercel (Frontend), Heroku (Backend)

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB Atlas account or local MongoDB installation

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/food-ordering-web.git
   cd food-ordering-web
   ```

2. **Install dependencies**
   ```bash
   # Install server dependencies
   cd server
   npm install
   
   # Install client dependencies
   cd ../client
   npm install
   ```

3. **Environment Setup**
   - Create a `.env` file in the server directory
   - Add your environment variables:
     ```
     PORT=5000
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. **Running the Application**
   ```bash
   # Start the server
   cd server
   npm start
   
   # In a new terminal, start the client
   cd ../client
   npm start
   ```

   The application will be available at `http://localhost:3000`



## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 🙏 Acknowledgments

- [React Icons](https://react-icons.github.io/react-icons/)
- [React Router](https://reactrouter.com/)
- [Axios](https://axios-http.com/)

---



