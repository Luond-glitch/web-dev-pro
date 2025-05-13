# 🖥️ Multi-Page Responsive Website

This project is a fully responsive multipage website built using **HTML5**, **CSS3**, and **JavaScript**, showcasing a simple layout with interactivity and form handling. The site includes a homepage with an image slider, an about page, and a contact form with client-side validation.

## 📄 Table of Contents
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [License](#-license)

## 🌐 Live Demo
🔗 [View Live Website](https://luond-glitch.github.io/web-dev-pro/)  


---

## ✅ Features
- Fully responsive design (mobile, tablet, desktop)
- HTML5 semantic structure
- CSS3 styling with Flexbox and media queries
- JavaScript:
  - Image slider (automatic)
  - Client-side form validation
- Simple and clean navigation across three pages

---

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript (Vanilla)
- Git & GitHub for version control
- GitHub Pages / Netlify / Vercel for deployment

---

## 📁 Project Structure
📘 Project Documentation
Project Title:
Responsive Multipage Website Using HTML5, CSS3, and JavaScript

1. Introduction
This project demonstrates fundamental front-end web development skills by building and deploying a responsive multipage website. It is designed to display content across three main pages: Home, About, and Contact. The site also integrates interactivity using JavaScript, such as a dynamic image slider and form validation.

2. Objective
To design, code, and deploy a multipage website using:

HTML5 for semantic markup

CSS3 for styling and responsiveness

JavaScript for interactivity

GitHub Pages/Netlify/Vercel for deployment

3. Features
Feature	Description
Home Page	Contains a hero section and an automatic image slider
About Page	Describes the purpose and content of the website
Contact Page	Includes a functional form with client-side validation
Responsive Design	Works well on desktops, tablets, and mobile devices
Navigation Menu	Persistent navigation bar across all pages
Image Slider	Auto-playing image slideshow using JavaScript
Form Validation	Validates user input before form submission

4. Technologies Used
Technology	Purpose
HTML5	Semantic structure of the webpage
CSS3	Styling, layout, and responsive design
JavaScript	Interactivity (form validation, image slider)
GitHub	Version control
GitHub Pages / Netlify / Vercel	Deployment

5. Website Structure
Pages:
index.html – Home page with welcome message and slider

about.html – Descriptive page about the website

contact.html – Contact form with input validation

Directories:
bash
Copy
Edit
/website-project
│
├── /assets/images   → Contains logo and gallery images
├── /css/style.css   → CSS styles
├── /js/script.js    → JavaScript for slider and form validation
├── index.html       → Home page
├── about.html       → About page
├── contact.html     → Contact page
└── README.md        → Project overview
6. Functional Overview
6.1 Image Slider
A set of images that transition automatically every 3 seconds using JavaScript:

js
Copy
Edit
let slideIndex = 0;
function showSlides() {
  ...
  setTimeout(showSlides, 3000);
}
showSlides();
6.2 Contact Form Validation
Prevents empty form submissions and alerts the user:

js
Copy
Edit
document.getElementById('contact-form').addEventListener('submit', function(event) {
  if (!name || !email || !message) {
    alert("Please fill in all fields.");
    event.preventDefault();
  }
});
7. Responsiveness
The site layout adjusts using CSS media queries.

Navigation switches from horizontal to vertical on smaller screens.

Images and form inputs scale to device width using percentage widths and max constraints.

8. Deployment
The site can be deployed using:

GitHub Pages
Upload code to GitHub repo

Enable Pages in Settings → Select main branch

Deployed URL: https://username.github.io/project-name/

Netlify / Vercel
Create an account

Link GitHub repo or upload project folder

Follow deployment instructions

9. Challenges & Solutions
Challenge	Solution
Making slider work smoothly	Used setTimeout loop to rotate images
Mobile responsiveness	Applied Flexbox and media queries
Form validation errors	Handled using JS addEventListener for submit

10. Conclusion
This project showcases essential web development concepts including:

Writing semantic HTML

Styling with CSS and Flexbox

Creating interactivity with JavaScript

Responsive design techniques

Website deployment on live servers
