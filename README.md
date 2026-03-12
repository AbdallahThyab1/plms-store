# 🛒 PLMS - Premium Electronics Store

> **A clean and responsive e-commerce website for electronics built with pure HTML & CSS.**  
> *Browse laptops, PCs, displays, mobiles, and more - all in one place.*

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://plms-ps.netlify.app/) [![Portfolio](https://img.shields.io/badge/Portfolio-Visit-blue?style=for-the-badge)](https://your-portfolio.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/abdallah-thyab-dev/)

---

## 📌 Overview

PLMS is a fully responsive electronics store website that showcases various product categories with a clean and modern design.

- **Problem solved:** Provides a structured and visually appealing interface for an electronics e-commerce platform
- **Built for:** Electronics shoppers and beginners learning HTML/CSS layout techniques
- **What makes it different:** Pure CSS implementation with consistent styling across 10+ pages, no frameworks or JavaScript dependencies

---

## 🎬 Demo

> 🌐 [Try the live demo](https://plms-ps.netlify.app/)  
> *Explore all pages and responsive design*


---

## ✨ Features

- ✅ **10+ Pages** — Complete multi-page website structure
- ✅ **Fully Responsive** — Works perfectly on mobile, tablet, and desktop
- ✅ **Clean Navigation** — Consistent header and footer across all pages
- ✅ **Product Categories** — Laptops, PCs, Displays, Mobiles, and Offers
- ✅ **User System** — Register page and User Profile page
- ✅ **Shopping Cart** — Cart page layout included
- ✅ **Support Page** — Customer support interface

---

## 📱 Pages Included

| Page | File | Description |
|------|------|-------------|
| 🏠 Home | `index.html` | Main landing page |
| 💻 Laptops | `laptop-page.html` | Laptop products showcase |
| 🖥️ PC Gaming | `pc-page.html` | Gaming PCs category |
| 📺 Displays | `display-page.html` | Monitors and displays |
| 📱 Mobiles | `mobile-page.html` | Smartphones section |
| 🏷️ Offers | `offer-page.html` | Special deals and offers |
| 🆘 Support | `support-page.html` | Customer support center |
| 📝 Register | `register-page.html` | User registration form |
| 🛒 Cart | `cart-page.html` | Shopping cart layout |
| 👤 User Profile | `user-page.html` | User account page |

---

## 🏗️ Architecture & Technical Decisions

### Project Structure

The project follows a modular CSS approach with separate stylesheets for each page to maintain clean code organization.

```
PLMS/
├── *.html (10+ pages)
├── styles/
│ ├── style-header-footer.css (Global styles)
│ ├── laptop-style.css
│ ├── pc-style.css
│ ├── display-style.css
│ ├── mobile-style.css
│ ├── offer-style.css
│ ├── support-style.css
│ ├── register-style.css
│ ├── cart-style.css
│ └── user-style.css
└── README.md
```

### Key Technical Decisions

**Why pure HTML & CSS without frameworks?**
> Using vanilla CSS demonstrates fundamental understanding of layout, positioning, and responsive design. It also keeps the project lightweight and fast-loading with zero dependencies.

**Why separate CSS files per page?**
> This approach makes maintenance easier and prevents style conflicts. Each page has its own dedicated stylesheet while sharing common header/footer styles.

**Responsive design approach**
> Media queries are used strategically to ensure optimal viewing experience across all devices. The layout adapts smoothly from mobile to desktop.

**Typography & Icons**
> Google Fonts (Inter) provides clean, modern typography. Font Awesome icons enhance visual communication without adding image bloat.

---

## 🛠️ Tech Stack

| Layer | Technology | Why |
|-------|------------|-----|
| Markup | HTML5 | Semantic structure |
| Styling | CSS3 | Custom styling without frameworks |
| Icons | Font Awesome | Professional icons library |
| Fonts | Google Fonts (Inter) | Clean, modern typography |
| Hosting | Netlify | Easy deployment |

---

## 🚧 Challenges & How I Solved Them

### Challenge 1: Consistent header/footer across 10+ pages
**Problem:** Updating navigation links would require editing every HTML file  
**Solution:** Created a single `style-header-footer.css` file for global styles; navigation structure is copied consistently  
**Result:** Visual consistency maintained across all pages

### Challenge 2: Responsive product grids
**Problem:** Product layouts needed to work on mobile, tablet, and desktop  
**Solution:** Used CSS Grid with media queries to adjust column counts based on screen size  
**Result:** Smooth responsive behavior without JavaScript

### Challenge 3: Maintaining color scheme consistency
**Problem:** Colors needed to be consistent across all pages  
**Solution:** Defined CSS variables in the header stylesheet for primary colors  
**Result:** Easy color management and updates

---

## 📈 What I Learned

- **Planning file structure matters** — Organizing 10+ pages requires thoughtful architecture from the start
- **Reusable CSS saves time** — Common styles belong in shared files, not duplicated
- **Responsive design is essential** — Mobile traffic requires careful layout planning
- **Consistency is key** — Navigation and branding must feel seamless across all pages
- **Pure CSS is powerful** — Modern CSS can handle complex layouts without frameworks

---

## 🗺️ Roadmap

- [x] Multi-page structure
- [x] Responsive design
- [x] Product categories
- [ ] JavaScript interactivity
- [ ] Product filtering
- [ ] Shopping cart functionality
- [ ] User authentication

---

## 📞 Contact

**Abdallah Thyab** - Computer Engineer & Web Developer

- 📧 Email: [1abdallahthyab@gmail.com](mailto:1abdallahthyab@gmail.com)
- 📱 Phone: +970 598786853
- 💼 LinkedIn: [Abdallah Thyab](https://www.linkedin.com/in/abdallah-thyab-dev/)
- 🐙 GitHub: [AbdallahThyab1](https://github.com/AbdallahThyab1)

---

## 📄 License

© 2025 PLMS. All rights reserved.
