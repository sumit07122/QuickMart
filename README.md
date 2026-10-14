# ⚡ QuickMart – 10-Minute Online Grocery Store

A responsive, multi-page online grocery store website built for a **Frontend Web Development Assignment** using strictly **HTML5, CSS3, and Bootstrap 5**.

---

## 🚀 Live Localhost View
The project is running locally at:
👉 **[http://localhost:3000](http://localhost:3000)**

To run it anytime locally in your terminal:
```bash
python -m http.server 3000
```

---

## 🌐 Deploy to Vercel (1-Click)
Since this repository is on GitHub:
1. Go to [vercel.com](https://vercel.com) and log in with GitHub.
2. Click **Add New...** ➔ **Project**.
3. Import **`QuickMart`** and click **Deploy**.
4. Your website will be live with a free `.vercel.app` URL and global edge CDN!

---

## 📄 Multi-Page Project Structure

This project features 5 interconnected webpages sharing a responsive Bootstrap navbar and footer:

1. **[index.html](file:///c:/Users/hp/OneDrive/Desktop/html/index.html)** — **Home Page**
   * Responsive sticky navbar with brand logo, delivery address badge, and search bar.
   * Flash Deals countdown banner (`GLA100`).
   * Vibrant Hero section with custom 3D delivery scooter graphic (`images/hero-delivery.jpg`).
   * Category filter pills with live interactive filtering.
   * 8 featured product cards with discount pills, star ratings, and `+ ADD` actions.
   * Live shopping cart sidebar with bill breakdown & checkout modal.

2. **[categories.html](file:///c:/Users/hp/OneDrive/Desktop/html/categories.html)** — **All Categories & Catalog**
   * Full 12-product catalog (*Groceries & Dairy*, *Snacks & Munchies*, *Cold Drinks*, *Personal Care*).
   * Category filter tabs and live search bar.
   * Interactive add-to-cart toast notifications.

3. **[deals.html](file:///c:/Users/hp/OneDrive/Desktop/html/deals.html)** — **Student Deals & Offers**
   * GLA University exclusive discount coupon cards with 1-click **Copy Code** functionality (`GLA100`, `STUDENT20`, `MIDNIGHT50`, `HOSTELBOGO`).
   * Curated student combos (Late Night Study Pack, Breakfast Bundle, Weekend Binge Pack, Hostel Hygiene Kit).

4. **[cart.html](file:///c:/Users/hp/OneDrive/Desktop/html/cart.html)** — **Full Shopping Cart & Checkout**
   * Interactive item quantity table with subtotal calculations.
   * Campus hostel delivery address form.
   * Payment method selection (UPI / QR Code, Cash on Delivery, GLA Smart Card).
   * Order Summary with working coupon code box and live order timeline modal.

5. **[about.html](file:///c:/Users/hp/OneDrive/Desktop/html/about.html)** — **About & Assignment Info**
   * QuickMart story and the 10-minute delivery model (4-step visual workflow).
   * Technical stack breakdown (HTML5, CSS3, Bootstrap 5.3, Bootstrap Icons).
   * Student academic profile card and feedback form.

---

## 📁 Repository Files
```text
├── index.html              # Home page
├── categories.html         # Categories & product catalog
├── deals.html              # Student coupons & combos
├── cart.html               # Dedicated cart & checkout page
├── about.html              # About & academic submission
├── style.css               # Clean custom styling & animations
├── images/
│   └── hero-delivery.jpg   # 3D electric delivery scooter image
├── vercel.json             # Vercel routing & cache headers
├── .vercelignore           # Ignored files for deployment
├── .gitignore              # Clean git ignore configuration
├── package.json            # Project metadata
└── README.md               # Project guide & documentation
```
