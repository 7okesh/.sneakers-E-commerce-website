# 👟 Sneakers E-Commerce Website (Nike Store)

A sleek, responsive, and modern front-end e-commerce web application for sneakers built with pure **HTML5**, **CSS3**, and vanilla **JavaScript (ES6+)**.

[![Deploy to GitHub Pages](https://github.com/7okesh/.sneakers-E-commerce-website/actions/workflows/deploy.yml/badge.svg)](https://github.com/7okesh/.sneakers-E-commerce-website/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://7okesh.github.io/.sneakers-E-commerce-website/)

---

## 📖 Table of Contents

- [Features](#-features)
- [Sneaker Collection](#-sneaker-collection)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Getting Started Locally](#-getting-started-locally)
- [Deployment via GitHub Pages](#-deployment-via-github-pages)
  - [Fixing Action Deployment](#fixing-github-pages-action-deployment)
- [Author](#-author)

---

## ✨ Features

- **Dynamic Interactive Slider**: Smooth 5-item sliding carousel displaying flagship models (`Air Force`, `Air Jordan`, `Blazer`, `Crater`, `Hippie`).
- **Product Detail Section**:
  - Live price and description synchronization when selecting products.
  - Interactive **Color Picker** updating sneaker images on the fly.
  - Interactive **Size Selector** (42, 43, 44) with active visual states.
- **Checkout Modal**:
  - Pop-up payment form with fields for customer details, shipping address, and card information.
  - Dismissible close button and modal overlay.
- **Value Proposition Highlights**:
  - Free shipping on all orders.
  - 30-day hassle-free returns.
  - Gift cards & customer contact support.
- **Gallery & Story Sections**: Curated "New Season" imagery and brand narrative.
- **Responsive Styling & Typography**: Custom layout using Google Font *Lato* with smooth CSS transitions.

---

## 👟 Sneaker Collection

| Model | Price (INR) | Color Options |
| :--- | :--- | :--- |
| **Air Force** | ₹9,990 | Black, Dark Blue |
| **Air Jordan** | ₹11,599 | Light Gray, Green |
| **Blazer** | ₹8,689 | Light Gray, Green |
| **Crater** | ₹10,284 | Black, Light Gray |
| **Hippie** | ₹7,892 | Gray, Black |

---

## 🛠 Technologies Used

- **HTML5**: Semantic web structure and accessible layout.
- **CSS3**: Modern layout (Flexbox), CSS positioning, animations, and custom styling.
- **JavaScript (ES6+)**: Dynamic DOM manipulation, state handling, and event listeners for slider and modal transitions.
- **GitHub Actions & GitHub Pages**: Continuous integration and automated deployment pipeline.

---

## 📁 Project Structure

```text
.sneakers-E-commerce-website/
├── .github/
│   └── workflows/
│       └── deploy.yml        # Automated GitHub Pages CI/CD pipeline
├── img/                      # Product and icon asset images
│   ├── air.png
│   ├── air2.png
│   ├── jordan.png
│   ├── jordan2.png
│   ├── blazer.png
│   ├── blazer2.png
│   ├── crater.png
│   ├── crater2.png
│   ├── hippie.png
│   ├── hippie2.png
│   └── ...
├── app.js                    # Core interactive logic (slider, modal, selectors)
├── index.html                # Main application page
├── style.css                 # Application styles and responsive design
└── README.md                 # Project documentation
```

---

## 🚀 Getting Started Locally

To run this project on your local machine:

### Option 1: Using Python
```bash
# From the repository directory
python -m http.server 5500
```
Then open [http://localhost:5500](http://localhost:5500) in your web browser.

### Option 2: Using Node.js (`npx serve`)
```bash
npx serve .
```

### Option 3: Direct Open
Simply double-click `index.html` or open it with any modern web browser.

---

## 🌐 Deployment via GitHub Pages

This project is configured with a GitHub Actions workflow in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) that automatically builds and deploys changes pushed to the `main` branch.

### Setup GitHub Pages Deployment

GitHub requires you to enable Pages once in your repository settings. You have two easy ways to deploy:

#### Option A: Deploy via GitHub Actions (Recommended)
1. Go to your repository on GitHub: **Settings** > **Pages**
   - Direct link: `https://github.com/7okesh/.sneakers-E-commerce-website/settings/pages`
2. Under **Build and deployment** > **Source**, click the dropdown and select **GitHub Actions**.
3. Go to the **Actions** tab and re-run the latest workflow (or push a new commit).

#### Option B: Deploy directly from the `gh-pages` branch
1. Go to: `https://github.com/7okesh/.sneakers-E-commerce-website/settings/pages`
2. Under **Build and deployment** > **Source**, keep **Deploy from a branch**.
3. Under **Branch**, select **`gh-pages`** and folder **`/ (root)`**, then click **Save**.

---

### 🌐 Live Website URL
Once either option completes, your website will be live at:
```text
https://7okesh.github.io/.sneakers-E-commerce-website/
```

---

## 👤 Author

- **Lokesh Prajapati**
- GitHub: [@7okesh](https://github.com/7okesh)
