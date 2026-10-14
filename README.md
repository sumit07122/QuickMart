# ⚡ QuickMart – 10-Minute Online Grocery Store

A responsive, modern online grocery store web page built for a **Frontend Web Development Assignment** using strictly **HTML5, CSS3, and Bootstrap 5**.

---

## 🎓 Project Highlights (For Viva / Study)

This project strictly utilizes the frontend fundamentals taught in class:

1. **HTML5 Semantic Structure**:
   * `<header>` with Bootstrap Navbar, search bar, and cart badge.
   * `<main>` containing promotional banners, product catalog grid, and shopping cart sidebar.
   * `<section>` tags dividing products into clear categories (*Groceries & Dairy*, *Snacks & Munchies*, *Drinks & Personal Care*).
   * `<aside>` for the sticky shopping cart bill calculation.
   * `<footer>` containing student info, category links, and sample items.

2. **Bootstrap 5 Components**:
   * **Navbar**: `navbar navbar-expand-lg bg-white sticky-top`
   * **Grid System**: `container`, `row`, `col-lg-8` (products), `col-lg-4` (cart)
   * **Cards**: `card`, `card-img-top`, `card-body`
   * **Badges**: `badge bg-warning`, `badge bg-success`
   * **Modal**: Clean Bootstrap modal (`#orderSuccessModal`) triggered via `data-bs-toggle="modal"` on checkout.

3. **Custom CSS (`style.css`)**:
   * Applied Google Font **Poppins**.
   * Smooth page scrolling (`scroll-behavior: smooth`).
   * Subtle card hover lift animations (`transform: translateY(-5px)`).
   * Uniform image dimensions (`object-fit: cover`).

---

## 💻 How to Run Locally

1. Open terminal inside this folder:
   ```bash
   python -m http.server 3000
   ```
2. Open your web browser and visit:
   👉 **[http://localhost:3000](http://localhost:3000)**

---

## 🚀 How to Deploy to Vercel

1. Push this repository to GitHub:
   ```bash
   git push -u origin main
   ```
2. Go to [vercel.com](https://vercel.com) and log in with GitHub.
3. Click **Add New...** ➔ **Project** ➔ Import `QuickMart`.
4. Click **Deploy**. Your site will be live instantly with a free `.vercel.app` URL!

---

## 📁 Clean File Structure
```text
├── index.html        # Core HTML5 & Bootstrap 5 webpage
├── style.css         # Lightweight custom styles & animations (~70 lines)
├── vercel.json       # Vercel deployment configuration
├── .vercelignore     # Ignored files for clean deployments
├── .gitignore        # Git ignore rules
├── package.json      # Project details
└── README.md         # Documentation & study guide
```
