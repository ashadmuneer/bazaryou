
# Bazaryo - Fashion E-commerce Platform

Welcome to the repository for **Bazaryo**, a fashion e-commerce platform built using modern web technologies. This platform allows users to browse, select, and purchase fashionable items online, with features for authentication, product management, and payment integration.

## Demo

You can view the live version of the application here: [Bazaryo](https://ashad.online)

## 🔍 Project Screenshots

### 🛠️ Admin Dashboard
![Admin Dashboard](https://res.cloudinary.com/dkvp2mun2/image/upload/v1746737739/adminpanale_hiooji.png)

### 🔐 Login Page
![Login Page](https://res.cloudinary.com/dkvp2mun2/image/upload/v1746737739/Screenshot_2025-05-09_021958_liispv.png)

### 🏠 Home Page
![Home Page](https://res.cloudinary.com/dkvp2mun2/image/upload/v1746737739/Screenshot_2025-05-09_022056_ok8fkx.png)


## Features

- **User Authentication**: User login and registration with JWT (JSON Web Tokens) for secure authentication.
- **Product Management**: Users can view, filter, and search for products, including categories such as clothing, accessories, and footwear.
- **Shopping Cart**: Users can add products to their shopping cart and proceed to checkout for a smooth purchasing experience.
- **Payment Integration**: Integrated PayPal for secure online payments.
- **Admin Dashboard**: Admin users can add, update, and remove products from the inventory.
- **Responsive Design**: The platform is fully responsive and adapts to different screen sizes including mobile, tablet, and desktop.
- **Image Hosting**: Uses Cloudinary to store and display high-quality product images.

## Tech Stack

### Frontend
- **React.js**: The main JavaScript library used for building the user interface.
- **Redux**: For state management, particularly for managing the shopping cart and user authentication state.
- **Tailwind CSS**: A utility-first CSS framework for styling the application.
- **React Router**: Used for navigation between different pages (home, product details, cart, checkout).
- **Axios**: For making API requests to the backend.

### Backend
- **Node.js & Express.js**: Backend built with Node.js and Express.js to handle API requests and business logic.
- **MongoDB**: NoSQL database used to store product details, user information, and order history.
- **JWT Authentication**: For secure user authentication, using JSON Web Tokens for user sessions.
- **Cloudinary**: For storing and serving images such as product photos.
- **PayPal API**: Integrated for handling online payments.

## Setup Instructions

### Prerequisites

Before getting started, make sure you have the following installed:

- **Node.js**: Recommended version 16 or higher.
- **MongoDB**: Either locally or through a cloud provider like MongoDB Atlas.
- **PayPal Developer Account**: For setting up payment integration.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ashadmuneer/backendbazaryou.git
   git clone https://github.com/ashadmuneer/bazaryou.git

   ```

2. Install the required dependencies for the frontend:

   ```bash
   cd bazaryou
   npm install
   ```

3. Install the required dependencies for the backend:

   ```bash
   cd backendbazaryou
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the **backend** directory and add the necessary environment variables, such as the MongoDB connection string, PayPal credentials, and JWT secret.
   - Example:

     ```
     MONGO_URI=your_mongo_db_connection_string
     PAYPAL_CLIENT_ID=your_paypal_client_id
     PAYPAL_SECRET=your_paypal_secret
     JWT_SECRET=your_jwt_secret
     ```

5. Start the backend server:

   ```bash
   cd backendbazaryou
   npm run dev
   ```

6. Start the frontend development server:

   ```bash
   cd bazaryou
   npm run dev
   ```

7. Open your browser and go to `http://http://localhost:5173` to view the platform locally.

## Additional Features

- **Product Filtering**: Users can filter products by categories such as clothing, shoes, and accessories.
- **Product Search**: A search bar allows users to find specific products quickly.
- **Order History**: Logged-in users can view their past orders and track their current order status.
- **Admin Panel**: Admin users have access to a dashboard where they can manage product listings and view customer orders.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

Thank you for visiting **Bazaryo**! If you have any questions, suggestions, or just want to connect, feel free to reach out via email or through the platform’s contact form.

