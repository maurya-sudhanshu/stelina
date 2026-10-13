<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3F1D0B,45:9A3412,100:F59E0B&height=210&section=header&text=Stelina%20%7C%20Code%20Global&fontSize=40&fontColor=FFFFFF&fontAlignY=38&desc=Air%20Fresheners%20%26%20Home%20Fragrance%20E-commerce%20Website&descAlignY=60&descSize=15" width="100%" alt="Stelina and Code Global air freshener website banner" />

<p>
  <img src="https://img.shields.io/badge/HTML5-Frontend-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-Interactions-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Responsive-E--commerce-9A3412?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Responsive e-commerce" />
</p>

**A multi-page storefront for showcasing air fresheners and home-fragrance products, with product discovery, product details, cart, checkout, and customer pages.**

</div>

---

## 🛍️ Project Overview

**Stelina** is a static, multi-page e-commerce storefront project for the **Code Global Air Fresheners** website. The repository contains HTML pages for product browsing, product details, shopping cart, checkout, account login, contact, and about information.

The pages use shared static assets and frontend libraries to deliver a branded shopping experience. This repository appears to focus on the frontend templates; any live payment, inventory, or order-processing behavior depends on external services or additional backend integration.

## ✨ Pages & Features

- 🏠 **Home page** — primary storefront and product discovery.
- 🧴 **Product listing** — browse products in a grid layout.
- 🔎 **Product details** — individual product information page.
- 🛒 **Shopping cart** — cart interface.
- 💳 **Checkout page** — checkout form and order details interface.
- 👤 **Login page** — customer account entry interface.
- ℹ️ **About page** — brand and business information.
- ✉️ **Contact page** — customer inquiry page.
- 🚫 **404 page** — custom not-found page.
- 📰 **Blog layout** — blog page with a right sidebar.
- 🔍 **SEO metadata** — page title, description, Open Graph metadata, and canonical URL are included in the homepage markup.

## 🧰 Frontend Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,jquery,bootstrap&theme=dark" alt="HTML, CSS, JavaScript, jQuery and Bootstrap" />

<br/>

<img src="https://img.shields.io/badge/HTML5-Markup-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-Styles-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
<img src="https://img.shields.io/badge/JavaScript-Interactions-F7DF1E?style=flat-square&logo=javascript&logoColor=111827" alt="JavaScript" />
<img src="https://img.shields.io/badge/jQuery-Plugins-0769AD?style=flat-square&logo=jquery&logoColor=white" alt="jQuery" />

</div>

The pages reference bundled CSS and JavaScript assets, including carousel, lightbox, popup, mobile-menu, and UI helper libraries.

## 📁 Repository Structure

```text
stelina/
├── assets/
│   ├── css/                 # Stylesheets and UI plugin styles
│   ├── js/                  # JavaScript and frontend plugins
│   ├── images/              # Product, banner, and UI images
│   └── fonts/               # Icon fonts
├── index.html               # Home/storefront page
├── gridproducts.html        # Product listing page
├── productdetails-fullwidth.html
├── shoppingcart.html        # Cart page
├── checkout.html            # Checkout page
├── login.html               # Login page
├── about.html               # About page
├── contact.html             # Contact page
├── inblog_right-siderbar.html
├── 404page.html             # Not-found page
├── robots.txt               # Crawler instructions
└── shoppingcart.zip         # Archived shopping-cart-related files
```

## 🚀 Run Locally

This repository is a static HTML/CSS/JavaScript site, so a Node.js build step is not required for basic preview.

### Option 1: Open the HTML file

1. Clone or download the repository.
2. Open `index.html` in a browser.

Some JavaScript plugins or relative asset paths may work more reliably when served over HTTP rather than opened as a local file.

### Option 2: Use Visual Studio Code

1. Open the project folder in VS Code.
2. Install the **Live Server** extension if needed.
3. Right-click `index.html` and select **Open with Live Server**.

### Option 3: Start a simple local server

If Python is installed, run this from the project directory:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## 🛠️ Customization

- Update product content and page copy in the relevant HTML files.
- Replace or optimize product and banner images inside `assets/images/`.
- Adjust site appearance in the stylesheets under `assets/css/`.
- Update scripts under `assets/js/` where interactions need to change.
- Keep navigation links, product URLs, canonical URLs, and SEO metadata consistent across pages.

## 🔐 Production Notes

- A checkout page alone does not provide secure payment processing. Integrate a trusted payment provider and validate orders on a backend before accepting real payments.
- Do not place API keys, credentials, or other secrets in frontend JavaScript.
- Validate all form inputs and handle customer data securely.
- Check that product imagery and fonts are optimized for performance.
- Verify page titles, canonical links, image alt text, and metadata before deployment.
- Update the canonical URL and Open Graph values for the final production domain.

## 🌐 Project Repository

<div align="center">

<a href="https://github.com/maurya-sudhanshu/stelina">
  <img src="https://img.shields.io/badge/GitHub-View%20Source%20Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="View source code" />
</a>

</div>

---

<div align="center">

**Stelina · Code Global Air Fresheners**

<sub>A product-focused storefront built with HTML, CSS, and JavaScript.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3F1D0B,45:9A3412,100:F59E0B&height=100&section=footer" width="100%" alt="Footer decoration" />

</div>
