# Frontend Challenge: Advanced CRUD Operations Dashboard

## 🚀 Overview
Welcome to the Frontend Challenge! This challenge is designed to assess your ability to build an advanced CRUD operations dashboard using **Next.js**, **Shadcn UI**, **NextAuth.js**, and **Zustand**. Your mission? Create an intuitive and engaging dashboard where users can manage products with advanced features like filtering, sorting, pagination, and more.

## 📌 Tech Stack
- **Next.js** (frontend framework)
- **TypeScript** (strictly required for type safety)
- **Shadcn UI** (for a clean and modern UI)
- **NextAuth.js** (for authentication)
- **Zustand** (for global state management)
- **Axios** (for API calls)
- **React Hook Form** (optional but recommended for form handling)
- **React Query** (optional but recommended for API state management)

## ✨ Features to Implement

### 🔑 Authentication
#### Login Page:
- Users can log in using email and password.
- Use **NextAuth.js** for authentication.
- Redirect users to the dashboard after a successful login.
- Handle authentication errors gracefully.

### 📊 Dashboard
#### Products Table:
- Display a table of products with the following columns:
  - Name
  - Description
  - Price
  - Category
  - Quantity
  - Status (**Available**/**Out of Stock**)
  - Actions (**Edit, Delete, View Details**)
- Add **pagination** to the table.
- Add **filtering** by:
  - Price (**low to high, high to low**)
  - Status (**Available/Out of Stock**)
- Add **search functionality** by product name.
- Add **hover effects** and interactive elements to make the table engaging.

### ➕ Add Product:
- A button to open a modal for adding a new product.
- The form should include fields for:
  - Name
  - Description
  - Image (**URL or file upload**)
  - Price
  - Category
  - Quantity
  - Status (**Available/Out of Stock**)
- Validate the form inputs before submission.

### ✏️ Edit Product:
- Clicking the **Edit** button should open a modal with the product details pre-filled.
- Allow users to update the product details.
- Validate the form inputs before submission.

### 🗑️ Delete Product:
- Clicking the **Delete** button should show a confirmation dialog.
- Delete the product after confirmation.

### 🔍 View Product Details:
- Clicking the **View Details** button should open a modal with detailed information about the product.

## 🔗 API Endpoints (Mocked)
Since this is a frontend-only challenge, you can mock the API endpoints using a tool like **Mock Service Worker (MSW)** or a simple **JSON file**.

| Method | Endpoint            | Description            |
|--------|---------------------|------------------------|
| POST   | `/api/products`     | Create a new product  |
| PUT    | `/api/products/:id` | Update a product      |
| GET    | `/api/products`     | Get all products      |
| GET    | `/api/products/:id` | Get a product by ID   |
| DELETE | `/api/products/:id` | Delete a product      |

## 🎯 Submission Guidelines
1. Push your code to a **public GitHub repository**.
2. Deploy your code on **Vercel** and provide a **live demo**.
3. Share the **repository link** in your application.
4. Ensure your code is **well-structured, clean, and documented**.

## 🚀 Bonus Points
- ✅ Use **TypeScript** for type safety and better code quality.
- ✅ Implement **Axios Interceptors** for handling API errors globally.
- ✅ Use **React Query** for managing API states (**loading, error, success**).
- ✅ Write **reusable components** (e.g., a reusable table component).
- ✅ Follow **SOLID principles** in your code structure.
- ✅ Add **animations** to make the UI more engaging.
- ✅ Organize the code into **feature-based folders** (e.g., `features/products`, `features/auth`).
- ✅ Use **GitHub branches** for different features (e.g., `feature/auth`, `feature/products`).

## ⏳ Time Limit
This challenge should take around **2 days** to complete. If you need an extension, feel free to reach out.

---

🎉 **Good luck! We can't wait to see what you build!** 🚀

