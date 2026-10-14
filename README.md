# ⚡ QuickMart – 10-Minute Online Grocery Store

An online grocery store website with delivery tracking, category navigation, shopping cart breakdown, and order placement modal.

## 🚀 Live Localhost View
The project is currently running locally at:
👉 **[http://localhost:3000](http://localhost:3000)**

To run it anytime locally in terminal:
```bash
python -m http.server 3000
```
Then open your browser at `http://localhost:3000`.

---

## 🌐 Deploy to Vercel (Step-by-Step)

You can deploy this website to Vercel in less than 2 minutes using either of these two methods:

### Method 1: Deploy via GitHub (Recommended)
1. Initialize Git and commit the files:
   ```bash
   git init
   git add .
   git commit -m "Initial QuickMart commit ready for Vercel"
   ```
2. Push your repository to your GitHub account (`https://github.com/new`).
3. Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
4. Click **"Add New..."** ➔ **"Project"**.
5. Select your repository and click **"Import"**.
6. Leave the default settings (Framework Preset: *Other*, Root Directory: `./`).
7. Click **"Deploy"**! 🎉 Your site will be live on a `*.vercel.app` URL with free SSL and global CDN.

---

### Method 2: Deploy directly via Vercel CLI
If you have Vercel CLI installed:
```bash
cmd /c npx vercel
```
1. Follow the interactive prompts (Link to existing project: `N`, Project name: `quickmart`, Directory: `./`).
2. When asked to deploy to production, run:
   ```bash
   cmd /c npx vercel --prod
   ```

---

## 📁 Project Structure
```text
├── index.html        # Main application structure and content
├── style.css         # Complete styling, animations, responsive design
├── vercel.json       # Vercel deployment routing and caching headers
├── .vercelignore     # Ignored files for clean deployments
├── .gitignore        # Git ignore rules
└── package.json      # Project metadata
```
