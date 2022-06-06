# E-Commerse Website

## Overview
The goal of this project is to have an e-commerse website where users can browse and purchase items.  The project will be built in Django and Vue.js.

## Features
#### As a **shopper**, I want a **simple, easy to way to browse and purchase items** because **I don’t want to leave my house**.
### Tasks:
* Create Django models for products
* Create a form for customers to check out
* Create a template that shows the products

#### As a **shop owner**, I want to **add new products, tag products into groups, manage inventory and get customer information** because **I want to know how many products are sold and how many are left**.
### Tasks:
* Create Django models representing customer orders
* Create a form for the shop owner to add new products
* Create a view that receives the form submission and saves the product to the db
* Show on the frontend new products added

### Additional Features:
* Payment Processor
* Product Reviews
* Wish List

## Schema (Data Model)
* Product
  - date_added (date field)
  - title (char field)
  - description (char field)
* Customer
  - name (char field)
  - items_ordered (?)
  - address (?)
* Orders
  - date (datefield)
  - customer (foreign key to Customer)
  - product (foreign key to Product)

## Schedule
### Week 1
* Create & Clone Repo
* Create Virtual Environment
* Start Django Project
* Write Models
* MVP of e-commerse website (Home page, shopping cart, and user login)
  
### Week 2
* Add payment processor
* Product reviews
* Product ratings

### Week 3
* Create a customer wish list
  
### Week 4
* deploy to heroku
* additional styling tweaks


## Feature Tiers:
### Must Haves
* Products page 
* User login & signup
* Shopping cart
  
### Should Haves
* Payment processor

### Can Haves
* Customer wish list
* Product reviews
* Product ratings

### Won't Haves
* Share on social media button