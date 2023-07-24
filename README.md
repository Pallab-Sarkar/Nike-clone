<h3 align="center">It's a MERN Stack E-commerce web application with all the major functionalities</h3>


Nike Clone is MERN Stack e-commerce web application that allows you to buy shoes & clothes online with payment gateway integration. It has a variety of categories, just visit the product listing page and you will see all the products, apply filters as per your need and in just a few clicks you can buy any products from the website. This project is just for educational purpose.


<br />

## Screens ( All screens are responsive)
- Homepage / Landing Page
- Product Listing Page with Filters
- Product Description Page
- Cart Management Page
- Wishlist/Favourites Management Page
- Checkout with Address Management Page
- Login / Logout Page
- Signup Page
- Order Summary Page


<br />


## Features
- Login and Signup User Account
- JWT (Json Web Token) Authentication and BcryptJS Password Hashing 
- Product Filters Based on Price, Category, Size, Color and Gender
- Product Sorting Based on Price, Rating and Name
- Product Filtering and Sorting works together 
- My Orders Section for details of all ordered item
- Wishlist Add and Remove Items
- Cart Add and Remove Items 
- Cart Update Quantities 
- Address Management
- Order Summary
- Coupons provided for discount
- Razorpay Payment Gateway
- Darkmode available

<br />


## Getting Started

This project was built using React, Redux, Chakra UI, HTML, CSS, JavaScript, Rest API, Node JS, Express and MongoDB with JWT and RazorPay integration. It is an e-commerce web application and for running on your local environment you should follow these guidelines.


### Prerequisites

- NPM
- Node JS
- MongoDB

### Setup


The project repository can be found in [GitHub link](https://github.com/pallab12/Nike-clone.git) or just clone the project using this command.


```
Using HTTPS

# git clone https://github.com/pallab12/Nike-clone.git
```

+ Open terminal on your workspace with

```
cd /home/workspace/Nike-Clone
```


## Install

Install NPM

Check that you have node and npm installed

To check if you have Node.js installed, run this command in your terminal:


```
node -v
```

To confirm that you have npm installed you can run this command in your terminal:


```
npm -v
```

To confirm that you have MongoDB installed you can run this command in your terminal:


```
mongo -v
```


To install all the dependences of the project, run the following command:


```
cd client

npm install

cd ../

cd server

npm install
```


To run the application got to the client folder and run the following command:

```
npm start
```

### Environment Variables

To run this project, you will need to add the following environment variables to your .env file in server folder

`JWT_ACCESS_KEY`

`MONGO_PATH`

`RAZORPAY_KEY_ID`

`RAZORPAY_KEY_SECRET`



### Tools used on this project

- Visual Studio Code
- Vite-JS template
- MongoDB compass
- Razorpay Dashboard to monitor payments

<br />