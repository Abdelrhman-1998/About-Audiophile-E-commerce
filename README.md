# Frontend Mentor - Audiophile e-commerce website solution

This is a solution to the [Audiophile e-commerce website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/audiophile-ecommerce-website-C8cuSd_wx). 

## Table of contents

- [Overview](#overview)
  - [Features](#Features)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Technologies and libraries](#Technologies)
  - [Hosting](#Hosting)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

  Audiophile is the premier store for high end headphones, earphones, speakers, and audio accessories.

  ![](./screenshots/preview.jpg)

### Features

Users should be able to:

- Sign up / sign in to their account
- Edit their profile  (name,Email,password)
- See last submitted orders' details
- Receive an E-mail confirmation after submitting order
- See interactive loding screens and spinners during loading pages
- Purchase the order with cash or credit card
- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Add/Remove products from the cart
- Edit product quantities in the cart
- Fill in all fields in the checkout
- Receive strong form validations if fields are missed or incorrect during checkout
- See correct checkout totals depending on the products in the cart
  - Shipping always adds $50 to the order
  - VAT is calculated as 20% of the product total, excluding shipping
- See an order confirmation modal after checking out with an order summary
- See an alert modal after unsuccessful payment (only on credit card option)
- See an alert modal if they navigate away during form submission 

### Screenshot

#### Home
![](./screenshots/home.png)
------------------------------
#### Headphones
![](./screenshots/headphones.png)
------------------------------
#### Speakers
![](./screenshots/Speakers.png)
------------------------------
#### Earphones
![](./screenshots/Earphones.png)
------------------------------
#### Product Details
![](./screenshots/product-details.png)
------------------------------
#### Checkout Form
![](./screenshots/checkout%20form.png)
------------------------------
#### Dashboard
![](./screenshots/userDashboard-editProfile.png)
------------------------------
![](./screenshots/userDashboard-details.png)
------------------------------
#### Modals and pop ups alert
![](./screenshots/sign%20up.png)
![](./screenshots/sign%20in.png)
![](./screenshots/cart.png)
![](./screenshots/confirmation%20modal.png)
![](./screenshots/failed%20payment.png)
![](./screenshots/stripe%20payment%20gateway.png)
![](./screenshots/canDeactivate%20form%20guard.png)
------------------------------
#### Received E-mail
![](./screenshots/Received-e-mail.png)

### Links

IMPORTANT:

  Since this project is one of my biggest projects and took a lot of time and efforts for testing and development,I decided to keep the source code private.
  If you are a reqruiter or a software agency that I applied to,feel free to ask me for the access to the source via any of my contacts.

  Thank you for understanding.

- Solution URL: (https://github.com/Abdelrhman-1998/About-Audiophile-E-commerce)
- Live Site URL:(https://audiophille-e-commerece.firebaseapp.com/)


### Technologies

- Angular2(v.14) 
- Typescript
- Node js
- SASS
- Bootstrap(v.5)
- Fontawesome
- Firebase-Auth
- Firebase-RealtimeDatabase

### Hosting 

  -Firebase Hosting (Frontend-only since firebase is a static hosting service)
  -Heroku(backend-only)

### Continued development

- Moving the whole project to standalone components
- Adding offline capabilities
- Working on SEO (Angular Universal)
- Using angular capacitor and ionic to make an andriod and iOS App(https://capacitorjs.com/solution/angular)


### Useful resources

- [classValidators](https://github.com/typestack/class-validator) - This helped me for creating strong validation with my reactive and template driven form 

- [SendGridApi](https://rapidapi.com/sendgrid/api/sendgrid/) - This helped me for sending E-mails

- [Stripe Payment gateway](https://stripe.com/docs/js) - This helped me for creating my demo payment gateway 

- [Country-data-Api](https://countriesnow.space/api/v0.1/countries/states) 

- [flagIcon](https://www.npmjs.com/package/flag-icon-css) - Give you the flags of all country 

- [ng-skeleton](https://www.npmjs.com/package/ng-skeleton) - Very Useful for lazy loading your content 

- [ng Select](https://www.npmjs.com/package/@ng-select/ng-select) - interactive select componet 

## Author

- Frontend Mentor - [@Abdelrhman-1998](https://www.frontendmentor.io/profile/Abdelrhman-1998)
