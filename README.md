# Amazon Clone
   
An Amazon-like e-commerce web application that mimics the core functionality of the Amazon platform, including product listings, shopping cart, user authentication, and order management.

## Features      

- **User Authentication:** Sign up, log in, and log out functionalities. 
- **Product Listings:** Display of products with details such as price, description, and images.
- **Search & Filtering:** Search bar and filters to browse products.
- **Shopping Cart:** Add, update, and remove products from the cart.
- **Order Placement:** Place orders and view order history.
- **Admin Panel:** Manage products, users, and orders.
  
## Demo  

[Live Demo](#)  https://amanbanjara.github.io/amazon.com-clone/

![Screenshot](screenshot.png) (Add a screenshot of your app)

## Tech Stack

- **Frontend:** React, Redux, CSS/Bootstrap
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Deployment:** AWS/Heroku/Netlify

## Installation

1. Clone the repository:
   ```bash
   git clone  https://amanbanjara.github.io/amazon.com-clone/
   cd amazon-clone
   ```

2. Install dependencies:
   ```bash
   npm install
   cd client && npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     PORT=5000
     MONGO_URI=your-mongodb-uri
     JWT_SECRET=your-jwt-secret
     ```

4. Run the application:
   ```bash
   # Run backend
   npm run server

   # Run frontend
   cd client && npm start
   ```

5. Access the application:
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend: [http://localhost:5000](http://localhost:5000)

## Folder Structure

```
amazon-clone/
├── client/            # React frontend
├── models/            # Mongoose schemas
├── routes/            # Express routes
├── controllers/       # Request handlers
├── middlewares/       # Authentication and error handling
├── utils/             # Utility functions
└── .env               # Environment variables
```

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, reach out to:
- **aman:** Your Name
- **neatsot@gmail.com:** your.email@example.com
- **GitHub:** [amanbanjara(https://github.com/amanbanjara)
