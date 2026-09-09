# 🌿 Paradise Nursery - Shopping Cart Web Application

Paradise Nursery is a React-based e-commerce application designed for browsing and purchasing indoor plants. The application utilizes **Redux Toolkit** for efficient global state management, allowing real-time cart updates, item subtotal calculations, continuous shopping capabilities, and seamless navigation.

---

## 🚀 Features

- **Interactive Plant Catalog:** Explore plants organized by distinct categories (_Air Purifying_, _Aromatic Fragrant_, _Insect Repellent_, _Medicinal_, and _Low Maintenance_).
- **Global State Management:** Managed via **Redux Toolkit** (`CartSlice.jsx`) for adding, removing, and updating item quantities across components.
- **Real-time Navigation & Badges:** Live total item count badge on the navigation bar updates instantly as products are added or updated.
- **Dynamic Cart Management:**
  - Subtotal calculation per item type.
  - Overall cart total calculation.
  - Increment and decrement quantity handlers with automated removal when quantity reaches 0.
- **Responsive & Intuitive UI:** Clear visuals and action feedback (e.g., disabling the "Add to Cart" button once an item is added).

---

## 🛠️ Tech Stack

- **Frontend:** React.js, HTML5, CSS3
- **State Management:** Redux Toolkit, React-Redux
- **Build Tool:** Vite
- **Deployment:** GitHub Pages (`gh-pages` / GitHub Actions)
