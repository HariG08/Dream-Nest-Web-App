# 🏠 Home Rentals Web Application

A user-friendly web app designed to simplify the process of finding and listing rental properties. Built with a modern tech stack, this platform ensures a smooth experience for both tenants and property owners.

## 🚀 Features

- 🔐 **User Authentication**  
  Secure login and signup using JWT to ensure authorized access.

- 🏘️ **Property Listings**  
  Property owners can easily add, edit, or remove rental listings with images and key details.

- 🔎 **Search & Filter**  
  Renters can browse through listings and apply filters based on location, price, and property type.

- 📱 **Responsive Design**  
  Fully optimized for all screen sizes – mobile, tablet, and desktop.

- 🔄 **State Management with Redux**  
  Efficient state handling ensures consistent UI and smooth data flow across components.

## 🛠️ Tech Stack

**Frontend:**
- React JS
- Material UI
- Redux

**Backend:**
- Node JS
- Express JS
- MongoDB
- JWT (for Authentication)

## 💡 How It Works

1. **User Registration & Login:**  
   New users can sign up and log in securely using JWT-based authentication.

2. **Browse Listings:**  
   Logged-in users can explore available rental properties, use filters, and view property details.

3. **Post a Property:**  
   Owners can add new listings by filling in property details and uploading images.

4. **Manage Listings:**  
   Owners can update or delete their posted properties at any time.

## 📸 Screenshots

*(You can add screenshots of the homepage, listing page, login screen, etc.)*

## 📦 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/yourusername/home-rentals-app.git
cd home-rentals-app

# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install

# Create .env file for backend with your MongoDB URI and JWT secret

# Start backend
npm run dev

# Start frontend
cd ../client
npm start
