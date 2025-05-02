
# OAMK Web Programming Project

## 📄 About the Project

This project is part of a course at **Oulu University of Applied Sciences (OAMK)**. It showcases the creation of a modern, responsive website using popular web technologies such as **HTML5**, **CSS3**, **JavaScript**, and **Bootstrap 5.1.3**.

The primary goal is to provide a practical example of building a user-friendly website with a clean design and interactive features. The project includes multiple pages, such as a home page, contact page, and portfolio, to demonstrate various functionalities.

This README file serves as a guide to the folder structure, project setup, and customization options. Whether you're a beginner or an experienced developer, this project offers valuable insights into web development.

> **Note:** This website is created solely for the purpose of the project assigned by **Oulu University of Applied Sciences (OAMK)**. It is a static project, and features like registration or login pages are non-functional and included only for demonstration purposes.

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

The project is organized into the following folders and files:

```
OAMK-Web-Programming-Project/
 ├── assets/
 │   ├── css/               # Folder for all CSS files (stylesheets)
 │   ├── images/            # Folder for images used in the project
 │   ├── js/                # Folder for JavaScript files (scripts)
 ├── *.html                 # All main HTML pages of the website
 └── README.md              # Project documentation file
```

This structure ensures everything is well-organized and easy to manage.

---

## 📄 HTML Structure

The project uses **Bootstrap v5.1.3** to create a responsive and mobile-friendly layout. Below is an example of the basic HTML structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>OAMK Web Programming Project</title>
  <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
  <header>
  <!-- Website header with navigation and logo -->
  </header>

  <main>
  <!-- Main content goes here -->
  </main>

  <footer>
  <!-- Footer with additional links or information -->
  </footer>

  <script src="assets/js/main.js"></script>
</body>
</html>
```

This structure ensures the website is clean, easy to read, and well-organized.

---

## 📄 HTML Pages Included

The project includes a variety of HTML pages to provide a complete website experience. Below is the list of pages and their purposes:

- **`index.html`** – The main home page that welcomes users and provides an overview of the website.  
- **`about-us.html`** – A page to share information about the organization, team, or purpose of the website.  
- **`service.html`** – A detailed page showcasing the services offered.  
- **`portfolio.html`** – A gallery-style page to display projects, work samples, or achievements.  
- **`single-portfolio.html`** – A detailed view of a specific portfolio item or project.  
- **`contact-us.html`** – A page with a contact form and other ways to reach out, such as email or phone.  
- **`blog.html`** – A page listing blog posts or articles in a structured format.  
- **`single-blog.html`** – A detailed page for reading a specific blog post or article.  
- **`errors-404.html`** – A custom error page displayed when a user visits a non-existent URL.  
- **`faq.html`** – A Frequently Asked Questions page to address common queries.  
- **`pricing.html`** – A page to display pricing plans or packages for services or products.  
- **`testimonial.html`** – A page to showcase customer reviews or testimonials.  
- **`coming-soon.html`** – A placeholder page for upcoming features or launches.  
- **`sign-in.html`** – A login page for users to access their accounts.  
- **`sign-up.html`** – A registration page for new users to create accounts.  
- **`reset-password.html`** – A page to help users reset their forgotten passwords.  
- **`README.md`** – The documentation file that explains the project structure and usage.

These pages are designed to provide a complete and user-friendly experience for visitors.

---

## 🎨 Customization

### Favicon  

To personalize the website, you can set a custom favicon. Add the following code in the `<head>` section of your HTML files:

```html
<link rel="shortcut icon" href="assets/images/favicon.png" type="image/x-icon">
```

Replace `favicon.png` with the file name of your own favicon image. The favicon is the small icon displayed in the browser tab.

### Logo  

To update the website logo, replace the image in the following code snippet:

```html
<div class="brand-logo">
  <a href="index.html"><img src="assets/images/logo/logo-white.svg" alt="logo"></a>
</div>
```

You can use image formats like `.svg`, `.png`, or `.jpg`. Make sure the logo file is placed in the correct folder.

---

## ✍️ Fonts Used

The project uses **Google Fonts** to enhance typography and make the text visually appealing:

- **Syne** – Used for headings, titles, and prominent text.  
- **Inter** – Used for body text, paragraphs, and smaller details.  

To customize or replace these fonts, update the following code in the `<head>` section of your HTML files:

```html
<link href="https://fonts.googleapis.com/css2?family=Inter&family=Syne&display=swap" rel="stylesheet">
```

You can explore other fonts on the [Google Fonts website](https://fonts.google.com).

---

## 🎨 CSS Files Overview

The project includes several CSS files to style the website and ensure it looks modern and professional:

- **`bootstrap.min.css`** – The core Bootstrap framework for responsive design.  
- **`font-awesome.css`** – A library of icons for buttons, navigation, and other elements.  
- **`magnific-popup.css`** – Styles for creating popups and lightboxes.  
- **`animate.min.css`** – Predefined animation effects for elements.  
- **`slick.css`** – Styles for carousels and sliders.  
- **`style.css`** – The main custom stylesheet for the website's unique design.

These CSS files work together to create a visually appealing and user-friendly interface.

---

## 📜 JavaScript Files

The project uses several JavaScript files to add interactivity and dynamic features to the website:

- **`jquery-3.6.0.min.js`** – A lightweight JavaScript library for simplifying DOM manipulation.  
- **`bootstrap.min.js`** – JavaScript components from Bootstrap, such as modals and dropdowns.  
- **`gsap.js`** – A powerful library for creating animations.  
- **`slick.min.js`** – A plugin for creating responsive carousels and sliders.  
- **`wow.js`** / **`aos.js`** – Libraries for adding scroll-based animations.  
- **`main.js`** – Custom JavaScript code specific to this project.

These scripts ensure the website is interactive, engaging, and easy to navigate.

---

## 🖼️ Credits

This project uses resources and tools from the following sources:

- **Bootstrap 5** – A popular framework for responsive web design: <https://getbootstrap.com>  
- **Unsplash / Pexels** – Free stock images for visual content.  
- **FontAwesome** – A library of icons: <https://fontawesome.com>  
- **Animate.css** – A library for CSS animations.  
- **Slick Carousel** – A plugin for creating carousels and sliders.  
- **GSAP** – A JavaScript library for animations.  
- **WOW.js** / **AOS.js** – Libraries for scroll animations.

These resources help make the project modern, functional, and visually appealing.

---

## 🙏 Thanks

Thank you for exploring this web programming project! It was created as part of a course at **Oulu University of Applied Sciences (OAMK)**. If you have any questions, suggestions, or feedback, feel free to reach out to the developer or refer to the documentation.

---

**© OAMK Web Programming Project 2025 – All rights reserved.**
