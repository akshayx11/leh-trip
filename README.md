# 🏔️ Ladakh Road Expedition 2026 Dashboard

A high-fidelity, responsive static web application designed to plan, track, and manage your upcoming adventure road trip to Ladakh (July 3 – July 10, 2026). 

This dashboard is fully optimized for mobile devices and laptops, making it the perfect offline-ready companion to access while on the road.

---

## 🌟 Key Features

1. **Interactive Route Timeline**: Navigate day-by-day (Day 1 to 8) to view exact route segments, travel distances, estimated driving times, altitude peaks, road ratings, and must-see sightseeing stops with direct Google Maps routes.
2. **Dynamic Gear & Packing Checklist**: Pre-populated checklists split into 5 crucial categories (Documents, Clothing, Electronics, Health/Medical, and Vehicle). Add custom items dynamically. Track your progress with animated percentage metrics.
3. **Expedition Budget & Expense Planner**: Full-featured ledger to add and delete individual expenses (Fuel, Hotel, Food, Permits, Misc). Configure trip budget limits, traveler counts, and view real-time calculations like **Cost Per Person** and **Remaining Balance**.
4. **Acclimatization (AMS) & Altitude Tracker**: Interactive SVG altitude profile chart highlighting elevation levels at each destination with click tooltips and active altitude warnings.
5. **Logistics & Stays**: Strategic lists detailing critical fuel stations, night stays status, and direct link to LAHDC Inner Line Permit portal.
6. **Browser Sync**: All checklist and budget data persists locally in your browser's `localStorage` (works completely offline!).

---

## 🚀 How to Host on GitHub Pages

This project is fully structured for zero-configuration static hosting on GitHub Pages. Follow these steps to put it online:

### Step 1: Create a GitHub Repository
1. Log in to your account at [GitHub](https://github.com).
2. Create a new repository named `ladakh-trip-2026` (or any name you prefer).
3. Leave it empty (do **not** initialize it with a README, license, or `.gitignore`).

### Step 2: Push Your Local Files to GitHub
Open your terminal in this project directory and run the following commands:

```bash
# Initialize a Git repository
git init

# Add all files to staging
git add .

# Create the initial commit
git commit -m "Initialize Ladakh Expedition dashboard"

# Rename default branch to main
git branch -M main

# Link to your remote GitHub repository (replace with your username and repo name)
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/ladakh-trip-2026.git

# Push your code to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

#### Option A: Zero-Config Standard Deployment (Recommended)
1. Go to your repository page on GitHub.
2. Click on the **Settings** tab.
3. On the left sidebar, click on **Pages**.
4. Under **Build and deployment** -> **Source**, select **Deploy from a branch**.
5. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
6. GitHub will generate a URL for your site (e.g., `https://yourusername.github.io/ladakh-trip-2026/`) within a few seconds!

#### Option B: Automatic Actions Deployment (Using our workflow)
We have included a pre-configured GitHub Actions workflow under `.github/workflows/deploy.yml` which deploys your code on every push:
1. Go to your repository settings -> **Pages**.
2. Under **Build and deployment** -> **Source**, select **GitHub Actions**.
3. That's it! Every time you run `git push`, GitHub Actions will build and deploy the page automatically.

---

*Enjoy your lifetime expedition to the Land of High Passes! Stay hydrated and drive safely!* 🏔️🚗
