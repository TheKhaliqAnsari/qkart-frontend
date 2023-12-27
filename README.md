
# Qkart-Ecom

QKart is an E-commerce application offering a variety of products for customers to choose from. 

During the course of this project,

- Implemented the core logic for authentication, shopping cart and checkout
- Improved UI by adding responsive design elements for uniform experience across different devices
- Utilized REST APIs to dynamically load and render data served by the backend server
- Deployed website to Netlify

![Qkart Component Architecture](https://github.com/anshumansinha18/Qkart-Frontend/assets/39727166/f204a6e0-051a-4b64-a4a1-89128f17c18c)
![QKart Shopping Interface (Products page)](https://github.com/anshumansinha18/Qkart-Frontend/assets/39727166/5386a6d8-75e2-4e35-82c7-da2852827794)

##  Registration-login Flow & Routing Setup

- Used React Router library to set up routes in the application and redirect customers to appropriate pages
- Added UI and logic to get the Login page ready
- Stored user information at client side using localStorage to avoid login on revisit

**Skills used**: 
React Router, Material UI, localStorage, Controlled Components, Conditional Rendering

![Request-response cycle for QKart User signup and login](https://github.com/anshumansinha18/Qkart-Frontend/assets/39727166/466aafaf-30f8-4e41-b4eb-db94640c8029)
![User flow on website for signup and login](https://github.com/anshumansinha18/Qkart-Frontend/assets/39727166/f3fda1df-a90c-4448-8072-78c3ab7ef8a3)


## Registration Feature

- Implemented logic and used backend API to get the registration feature ready
- Added validation for the register form user input values to display informative error messages

## Display products and Search Feature Implementation

- Utilized the **useEffect()** hook to fetch products data after **DOM** is rendered for faster page loading
- Added search bar to display only on the Products page’s header and implemented search logic
- Implemented debouncing for improved UX and reduced API calls on search

**Skills Used:** Keyword Search, Debouncing, Material UI Grid

![QKart Products page](https://github.com/anshumansinha18/Qkart-Frontend/assets/39727166/286a8230-dd94-4d40-b719-36ed0461bd8f)


## Shopping Cart and Checkout Flow

- Added Cart to Products page and made it responsive
- Made authenticated POST API calls to implement Cart logic
- Rendered Cart with differing designs in Products page and Checkout page using conditional rendering.
- Implemented UI and logic to add and select new addresses

**Skills used**: 
Responsive Design, Reusable Components

![Products page UI with responsive Cart design (Left: Desktop, Right: Mobile)](https://github.com/anshumansinha18/Qkart-Frontend/assets/39727166/49cac148-8c13-4e15-8aef-efd38bf8587b)
![QKart Checkout page](https://github.com/anshumansinha18/Qkart-Frontend/assets/39727166/fb9c79ad-b8a8-4366-8e19-8157f70fa098)

## Deployement

- Deployed the QKart React app to Netlify
- Configured Netlify to support visiting any sub pages directly as React is a single page application

**Skills Used:** Deployement, Netlify 



