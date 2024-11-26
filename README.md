# GV Mart

**GV Mart** is an online marketplace inspired by popular e-commerce platforms. Built as a final year project, this application provides a functional and secure e-commerce experience. It features user registration and authentication, secure payments, media storage, and an admin panel for managing inventory.

---
## My Role 
In this project, my role was to develop the frontend and contribute to the backend by designing the backend workflow.

## Features

1. **User Registration and Authentication**
   - **Secure Sessions**: JWT-based session tokens ensure secure user authentication and session management.

2. **Message Notifications**
   - **SendGrid Integration**: Sends order confirmations and other important messages to users.

3. **Media Storage**
   - **Cloudinary Integration**: Handles product images and media files efficiently.

4. **Payment Gateway**
   - **Paytm Integration**: Enables secure and seamless payment processing.

5. **Admin Panel(RBAC)**
   - Inventory management is simplified through an admin interface where the owner can add, update, or remove products.
   - Currently, three demo items are added for demonstration.
   - The admin can edit user roles, update user details, and delete users.
   - A table displays user roles and details for easy management.
   - The table includes a search functionality to quickly find specific users.
   - It also features a filter option to narrow down users based on certain criteria.

---

## Technologies Used

### Backend
- Node.js and Express.js

### Frontend
- React.js (or specify if a different framework/library is used)

### Database
- MongoDB

### Third-Party Integrations
- **SendGrid**: For email notifications.
- **Cloudinary**: For image and media storage.
- **Paytm**: For payment processing.
- **JWT (JSON Web Tokens)**: For secure session handling.

---

## Setup and Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd gv-mart
```

### 1. Install Dependencies
```bash
npm install
```

### 2. Install Dependencies
```bash
SENDGRID_API_KEY=your_sendgrid_api_key
CLOUDINARY_URL=your_cloudinary_url
PAYTM_MERCHANT_KEY=your_paytm_merchant_key
JWT_SECRET=your_jwt_secret

```
### 3. Run the Application
```bash

npm start

```

## Project Structure

```plaintext
gv-mart/
├── /admin       # Admin panel for inventory management
├── /api         # API routes for managing users, products, and orders
├── /client      # Frontend codebase
├── /config      # Configuration files for SendGrid, Cloudinary, and Paytm
├── .env         # Environment variables (not included in the repo)
├── package.json # Dependencies and scripts

```
## Features in Progress


- **More Products**: Expand the inventory with additional items.

---

## Future Enhancements


- Add more **payment options** to the platform.
- Expand **inventory management** to include bulk operations and advanced filtering.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contributions

Contributions to the project are welcome! Feel free to raise issues, suggest features, or create pull requests.

