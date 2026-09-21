# 💰 Tip Calculator

A responsive **order and tip calculator** built with **React, TypeScript, Vite and Tailwind CSS**.

The application allows users to add products to an order, manage quantities, select a tip percentage and automatically calculate the final amount.

🔗 **Live Demo:**  
https://fabulous-hummingbird-87b824.netlify.app/

---

## ✨ Features

- Add products to the order
- Increase product quantities
- Remove products from the order
- Select different tip percentages
- Automatic subtotal calculation
- Automatic tip calculation
- Automatic total calculation
- Responsive interface
- Reusable React components
- Custom Hook for order management
- Optimized derived calculations with `useMemo`

---

## 🛠️ Technologies

- React
- TypeScript
- Vite
- Tailwind CSS
- HTML5
- Git & GitHub
- Netlify

---

## ⚡ React concepts

This project helped me practice and reinforce several React concepts:

- Component-based architecture
- State management
- Props
- Custom Hooks
- Derived state
- `useMemo`
- Conditional rendering
- Array methods such as `map`, `filter` and `reduce`
- TypeScript interfaces and types

The order management logic is separated from the UI through a **Custom Hook**, helping keep the components cleaner and the application easier to maintain.

`useMemo` is used for derived calculations such as the subtotal, tip amount and total, avoiding unnecessary recalculations when their dependencies have not changed.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/lorenamp25/tip-calculator-react.git
```

Move into the project:

```bash
cd tip-calculator-react
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

---

## 🌐 Deployment

The application is deployed on **Netlify**.

👉 https://fabulous-hummingbird-87b824.netlify.app/

---

## 👩‍💻 Author

**Lorena**

Frontend Developer focused on building modern and user-friendly web applications with React and TypeScript.

🌐 [Portfolio](https://lorenamp25.github.io/PORTFOLIO/)  
💻 [GitHub](https://github.com/lorenamp25)
