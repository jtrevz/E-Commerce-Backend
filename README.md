# E-Commerce API ![badge](https://img.shields.io/badge/license-MIT-yellow.svg)

This API is a database that organizes product from an e-commerce site. The database organizes information into categories, products, and tags. This API allows client to create, read, update, and delete data based on their storage needs.

![E-Commerce API]()

## Table of Contents:
  * [Database](#database)
  * [API](#api)
  * [Instructions](#instructions)
  * [License](#license)
  * [Questions](#questions)
<br>

### Database

![Database]()

This application consists of four tables: Categories, Products, Tags and Product Tags.

![Categories]()

Categories describe the product type like shirts, pants, etc.

![Products]()

Products refers to the actual products available in the e-commerce site. It includes information like the product name, price, how much stock is available, and what category it belongs to.

![Tags]()

Tags are used to describe the products further. While categories explained what type of product each item is, tags describe product color like red, green, gold or the product description like whether the product is about rock or pop music.

![Product Tags]()

Product tags are where the information about what types of tags each product has is stored. Each product can have several product tags for each type of tag the product has. 

<br>

### API

![API]()

This application allows for client to create, update, read, and delete product information based on their needs. The client can use HTTP Request methods (Get, Post, Put, Delete) to make this happen and will receive information in JSON format.

<br>

### Instructions

First, open up the schema (in the db file) named seed.sql and run the syntax to create the database and the tables. Then

![Schema](https://user-images.githubusercontent.com/78758382/116194250-37025f00-a6f6-11eb-974d-45c1164d4e43.png)

Once that has been completed, open the intergrated terminal and  run:
```
npm i
```

After the dependencies have been installed, the seeds have to be input into the database. Run the code below on your terminal:

```
npm run server
```
Once your dependencies have been installed, then the server is ready to be turned on by running:
```
node server.js
```
This will start the application and you are welcome to both browse by categories, products, and tags. You are also welcome to add to the database, update information on existing data and delete. 

<br>


### License
[Licences](https://opensource.org/licenses/MIT)
<br>
<br>
### Questions
Any questions for me? Message me on [GitHub](https://github.com/jtrevz) or by email @ jenny.trevizo2013@gmail.com