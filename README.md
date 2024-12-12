
# Grocery WebApp  

## Overview  
This project is a full-stack Grocery web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). It allows users to browse, search, and purchase groceries online. The app includes features like user authentication, product catalog, shopping cart, and a secure checkout process.



## Features  

### Frontend  
1. **Product Catalog**  
   - Display products with images, titles, descriptions, and prices.  
   - Search, filter, and sort products for easy browsing.  

2. **Shopping Cart and Checkout**  
   - Add, update, and remove items from the shopping cart.  
   - Multi-step checkout process (shipping, payment, order review).  

3. **User Authentication**  
   - User registration and login system.  
   - Profile management (view/edit personal details, addresses, and payment methods).  

4. **Responsive Design**  
   - Mobile-friendly and responsive user interface.  

---

### Backend  
1. **API Endpoints**  
   - RESTful APIs for user management, product catalog, cart, and order processing.  
   - Secure and optimized responses.  

2. **Authentication and Authorization**  
   - User authentication with JWT.  
   - Route protection for restricted features.  

3. **Database Management**  
   - MongoDB schemas for users, products, carts, and orders.  

4. **Payment Gateway Integration**  
   - Integration with Stripe (or other payment providers).  

5. **Error Handling and Logging**  
   - Proper error responses for API requests.  
   - Logging for debugging and monitoring.  



## Tech Stack  

### Frontend  
- **React.js**  
- **Bootstrap 4** (for UI components)  

### Backend  
- **Node.js**  
- **Express.js**  

### Database  
- **MongoDB**  

### Additional Tools  
- **JWT** (for authentication)  



## Installation  

### Prerequisites  
- Node.js  
- MongoDB  

### Steps  
1. **Clone the repository**  
   ```bash  
   git clone https://github.com/your-username/grocery-webapp.git  
   cd grocery-webapp  
   ```  

2. **Install dependencies**  

   **For Backend**  
   ```bash  
   cd backend  
   npm install  
   ```  

   **For Frontend**  
   ```bash  
   cd frontend  
   npm install  
   ```  

3. **Setup Environment Variables**  
   Create a `.env` file in the `backend` directory and add the following:  
   ```env  
   MONGO_URI=your-mongodb-connection-string  
   JWT_SECRET=your-secret-key  
   STRIPE_SECRET_KEY=your-stripe-secret-key  
  

4. **Run the Application**  
   **Backend**  
   ```bash  
   cd backend  
   npm run dev  
   ```  
   **Frontend**  
   ```bash  
   cd frontend  
   npm start  
   ```  



## API Endpoints  

### User Management  
- `POST /api/users/register` - Register a new user.  
- `POST /api/users/login` - Authenticate user and return token.  

### Product Catalog  
- `GET /api/products` - Retrieve all products.  
- `GET /api/products/:id` - Retrieve a single product by ID.  

### Cart  
- `POST /api/cart` - Add items to the cart.  
- `GET /api/cart` - View items in the cart.  

### Orders  
- `POST /api/orders` - Place an order.  
- `GET /api/orders/:id` - View order details.  



## Folder Structure  


grocery-webapp  
│  
├── backend/  
│   ├── models/         # Mongoose schemas  
│   ├── routes/         # API routes  
│   ├── controllers/    # Business logic  
│   ├── config/         # Database and app configurations  
│   ├── server.js       # Entry point  
│  
├── frontend/  
│   ├── src/  
│   │   ├── components/ # React components  
│   │   ├── pages/      # Page views  
│   │   ├── utils/      # Helper functions  
│   │   └── App.js      # Main app file  
│  
├── README.md           # Documentation  
└── .env                # Environment variables  


## Future Enhancements  
- Add a recommendation system for products.  
- Implement coupon code functionality.  
- Introduce an admin panel for product and order management.  


## Contributions  
Feel free to fork the project, make your changes, and submit a pull request!  



## License  
This project is licensed under the MIT License.  

Feel free to modify the content to match your specific repository setup and functionality.

Demo Link:
Link: https://drive.google.com/drive/folders/1CiKX-ZAeRmRh_RmiE67Dh0iQJg7cc0NA?usp=drive_link 



