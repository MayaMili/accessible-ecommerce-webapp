# Accessible E-Commerce Web Application

A responsive e-commerce web application developed as my Bachelor's thesis project at the **University of Zagreb Faculty of Electrical Engineering and Computing (FER)**.

The project focuses on creating a functional online store with special attention to **web accessibility for visually impaired users**. It includes a dedicated accessibility mode and follows accessibility practices based on WCAG guidelines.

## Live Demo

**[View the live application](https://seke-webshop.vercel.app)**

## About the Project

The application was developed for **SEKE Rukotvorine**, a small family craft business offering handmade products.

The goal of the project was to develop a complete e-commerce interface while exploring how accessibility features can be integrated into a modern web application without requiring a separate version of the website.

Users can browse product categories, view individual products and their available variants, add products to a shopping cart and complete the checkout process.

A dedicated accessibility mode provides additional adaptations intended to improve the experience for visually impaired users.

## Features

* Product catalogue organized into categories
* Individual product pages
* Product variant selection
* Shopping cart
* Checkout and order confirmation
* Responsive layout for different screen sizes
* Firebase Firestore integration for catalogue data
* Dedicated accessibility mode

## Accessibility

Accessibility was one of the main focuses of the project.

The application includes:

* Semantic HTML structure
* Keyboard-accessible navigation
* Visible keyboard focus
* Skip-to-content functionality
* Descriptive alternative text for images
* Form labels and accessible controls
* ARIA attributes where appropriate
* Increased text size and contrast in accessibility mode
* Product variants represented using descriptive image thumbnails instead of colour-only indicators
* Prevention of adding products to the cart before a required variant is selected
* Screen reader testing using **Apple VoiceOver**

The accessibility implementation was developed with reference to **WCAG 2.2** recommendations.

## Technologies

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend & Data

* Firebase
* Cloud Firestore

### Development & Deployment

* Git
* GitHub
* Vercel
* Visual Studio Code

## Project Structure

```text
accessible-ecommerce-webapp/
├── api/
├── images/
├── scripts/
├── styles/
├── index.html
├── product.html
├── category.html
├── cart.html
├── checkout.html
├── confirmation.html
├── seed-catalog.html
├── dev-server.js
├── vercel.json
└── package.json
```

## What I Learned

Through this project, I gained practical experience in building and structuring a complete web application, managing application data with Firestore, implementing shopping cart and checkout functionality, deploying a web application, and using Git for version control.

The project also gave me the opportunity to explore web accessibility in greater depth, particularly semantic HTML, keyboard navigation, screen reader compatibility and WCAG recommendations.

## Author

**Maja Miličević**

Bachelor's thesis project
University of Zagreb
Faculty of Electrical Engineering and Computing (FER)
