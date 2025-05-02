
# OAMK Web Programming Project

## 📄 About the Project

This repository contains the **OAMK Web Programming Project**, developed as part of a course at **Oulu University of Applied Sciences (OAMK)**. The project demonstrates the use of **HTML5**, **CSS3**, **JavaScript**, and **Bootstrap 5.1.3** to create a fully responsive website.

This README provides details about the folder structure, setup instructions, and customization options.

---

## Table of Contents

1. [About the Project](#about-the-project)
2. [Folder Structure](#folder-structure)
3. [HTML Structure](#html-structure)
4. [HTML Pages Included](#html-pages-included)
5. [Customization](#customization)
    - [Favicon](#favicon)
    - [Logo](#logo)
6. [Fonts Used](#fonts-used)
7. [CSS Files Overview](#css-files-overview)
8. [JavaScript Files](#javascript-files)
9. [Credits](#credits)
10. [Thanks](#thanks)

---

## 📁 Folder Structure

The project folder is organized as follows:

```
OAMK-Web-Programming-Project/
 ├── assets/
 │   ├── css/               # Stylesheets
 │   ├── images/            # Image assets
 │   ├── js/                # JavaScript files
 │
 ├── *.html                 # All main HTML pages
 └── README.md              # Project documentation (this file)
```

---

## 📄 HTML Structure

The project uses **Bootstrap v5.1.3** for its layout. A basic HTML structure looks like this:

```html
<!doctype html>
<html lang="en">
<head>
     <meta charset="utf-8">
     <title>OAMK Web Programming Project</title>
     <meta name="viewport" content="width=device-width, initial-scale=1">
     <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>

<header> ... </header>

<main> ... </main>

<footer> ... </footer>

<script src="assets/js/main.js"></script>
</body>
</html>
```

---

## 📄 HTML Pages Included

The project includes the following HTML pages:

- `index.html` – Home Page  
- `about-us.html` – About Us  
- `service.html` – Services  
- `portfolio.html` – Portfolio  
- `single-portfolio.html` – Single Portfolio  
- `contact-us.html` – Contact Page  
- `blog.html` – Blog Overview  
- `single-blog.html` – Blog Details  
- `errors-404.html` – Error Page  
- `faq.html` – Frequently Asked Questions  
- `pricing.html` – Pricing Page  
- `testimonial.html` – Testimonials  
- `coming-soon.html` – Coming Soon  
- `sign-in.html` – Sign In Page  
- `sign-up.html` – Sign Up Page  
- `reset-password.html` – Reset Password Page  
- `privacy.html` – Privacy Policy  
- `terms.html` – Terms and Conditions  
- `license.html` – License Information  
- `README.md` – Project Documentation

---

## 🎨 Customization

### Favicon  

Set the favicon in the `<head>` section:

```html
<link rel="shortcut icon" href="assets/images/favicon.png" type="image/x-icon">
```

### Logo  

Replace the logo in the following section:

```html
<div class="brand-logo">
  <a href="index.html"><img src="assets/images/logo/logo-white.svg" alt="logo"></a>
</div>
```

You can use `.svg`, `.png`, or `.jpg` formats.

---

## ✍️ Fonts Used

The project uses **Google Fonts**:

- Syne
- Inter

You can update or replace them in `index.html` or `style.css`:

```html
<link href="https://fonts.googleapis.com/css2?family=Inter&family=Syne&display=swap" rel="stylesheet">
```

---

## 🎨 CSS Files Overview

The following CSS files are included:

- `bootstrap.min.css` – Bootstrap framework  
- `font-awesome.css` – FontAwesome icons  
- `magnific-popup.css` – Popup styles  
- `animate.min.css` – Scroll animations  
- `slick.css` – Carousel styles  
- `style.css` – Main template styling

---

## 📜 JavaScript Files

The project uses these JavaScript files:

- `jquery-3.6.0.min.js` – Core jQuery  
- `bootstrap.min.js` – Bootstrap functionality  
- `gsap.js` – GSAP animation library  
- `slick.min.js` – Slick carousel  
- `wow.js` / `aos.js` – Scroll animations  
- `main.js` – Template’s custom JS

---

## 🖼️ Credits

The project uses resources from:

- **Bootstrap 5** – <https://getbootstrap.com>  
- **Unsplash / Pexels** – Free images  
- **FontAwesome** – <https://fontawesome.com>  
- **Animate.css**, **Slick Carousel**, **GSAP**, **WOW.js**, **AOS.js**

---

## 🙏 Thanks

Thank you for exploring this web programming project created for academic purposes at OAMK. For questions or feedback, feel free to contact the developer or refer to the included documentation.

---

**© OAMK Web Programming Project 2025 – All rights reserved.**
