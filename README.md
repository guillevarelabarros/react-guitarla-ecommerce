# 🎸 GuitarLA – E-Commerce App

![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.2.2-3178C6?logo=typescript&logoColor=white)
![Material UI](https://img.shields.io/badge/Material%20UI-v5-007FFF?logo=mui&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.0-646CFF?logo=vite&logoColor=white)
![useReducer](https://img.shields.io/badge/State%20Management-useReducer-4CAF50?logo=react&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue)

---

**Live Demo:**  
[https://guitarla-ecommerce-app.netlify.app](https://guitarla-ecommerce-app.netlify.app)

A modern and responsive e-commerce web application for guitar sales, built
with  
**React**, **TypeScript**, and **Material UI**.  
Features a dynamic shopping cart powered by **useReducer**, theme toggling  
(light/dark), and persistent cart storage using **localStorage**.  
Designed with reusable components, clean architecture, and responsive layouts  
for all devices.

---

## 🚀 Features

✅ Add and remove guitars from the cart  
✅ Increase or decrease item quantity with limits  
✅ Real-time cart total calculation  
✅ Persistent cart using localStorage  
✅ Light/Dark theme toggle with MUI  
✅ Responsive Material UI components  
✅ Accessible keyboard-friendly design  
✅ Strongly typed with TypeScript for scalability

---

## 🧠 Tech Stack

- ⚛️ **React 18** + **TypeScript**
- 🎨 **Material UI (MUI)** for styling and theming
- 🔄 **useReducer** for global state management
- 💾 **localStorage** for persistence
- ⚡ **Vite** for fast builds and hot reloading
- 🧱 **Custom CSS** for animations and layout enhancements

---

## 🗂️ Project Structure

```
src/
├── components/ # UI components (Header, GuitarCard)
├── data/ # Static guitar catalog (db.ts)
├── reducers/ # Cart reducer logic (add, remove, update)
├── types/ # TypeScript interfaces (Guitar, CartItem)
├── theme.ts # MUI theme configuration (light/dark)
├── App.tsx # Main application logic
├── main.tsx # Theme provider and app entry point
└── index.css # Custom global styles and animations

```

## 📸 Screenshots

### 🖼️ Product Catalog

![Catalog Screen](public/img/screen1.png)

### 🛒 Shopping Cart

![Cart Screen](public/img/screen2.png)

---

## 💡 What I Learned

- Implemented **state management with useReducer** for scalable e-commerce
  logic.
- Created **reusable and type-safe components** in React with TypeScript.
- Applied **Material UI theming** with persistent light/dark mode.
- Built **responsive layouts** without external frameworks.
- Managed **localStorage state synchronization** for cart persistence.

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/guillevarelabarros/react-guitarla-ecommerce.git
cd react-guitarla-ecommerce

# Install dependencies
yarn install

# Start development server
yarn dev
```

## 👨‍💻 Author

Guille Varela Barros 🔗 LinkedIn

💻 GitHub

“Clean design meets clean code — every string counts 🎶”
