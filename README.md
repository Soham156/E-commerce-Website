# 🛍️ My Personal eCommerce Project

Welcome to **MyShop** – a personal eCommerce web application built for practicing full-stack development. The platform allows users to browse products, add them to cart, place orders, and manage their profile. Admins can manage inventory, orders, and users efficiently.

🔗 **Live Website:** [https://e-commerce-website-1mjs.onrender.com](https://e-commerce-website-1mjs.onrender.com)

---

## 🚀 Features

### 🧑‍💻 User Side:

- User registration & login with JWT authentication
- Product browsing with categories and search
- Add to cart & checkout functionality
- Order placement and payment (integration pending or done)
- View past orders and order details
- Profile management
- Secure payment integration using **Braintree**

### 🛠️ Admin Panel:

- Dashboard with order and user statistics
- Product CRUD operations
- Order management and delivery status update
- Manage user roles and accounts

---

## ⚙️ Tech Stack

### Frontend:

- React.js
- Redux Toolkit
- Tailwind CSS / Bootstrap
- Axios

### Backend:

- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT Authentication
- Braintree Payments

---

## 🌐 Deployment

- Frontend: [Render](https://render.com/)
- Backend: [Render](https://render.com/)
- Database: MongoDB Atlas

---

## 🧪 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/Soham156/E-commerce-Website.git

# Install dependencies
npm install

# Set up environment variables
cp .env

# Start the development server
npm run dev
```

Make sure to configure your `.env` file with:

```
MONGO_URI=<Your MongoDB URI>
JWT_SECRET=<Your Secret>
BRAINTREE_MERCHANT_ID=<Your Merchant ID>
BRAINTREE_PUBLIC_KEY=<Your Public Key>
BRAINTREE_PRIVATE_KEY=<Your Private Key>
```

---

## 🙋‍♂️ Author

**Soham Chaudhari**  
[GitHub](https://github.com/Soham156) | [LinkedIn](https://www.linkedin.com/in/soham-chaudhari-174b4b287/)

---

## 📌 License

This project is licensed under the MIT License – feel free to use and contribute.

---

## 💡 Future Improvements

- Add product reviews and ratings
- Add wishlist functionality
- Improve mobile responsiveness
- Unit and integration tests
