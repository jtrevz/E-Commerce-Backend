# E-Commerce API ![badge](https://img.shields.io/badge/license-MIT-yellow.svg)

This API is a database that organizes product from an e-commerce site. The database organizes information into categories, products, and tags. This API allows client to create, read, update, and delete data based on their storage needs.

![E-Commerce API](https://user-images.githubusercontent.com/78758382/116605742-69c67600-a8f5-11eb-81ab-8161aa41f22a.png)


## Table of Contents:
  * [Database](#database)
  * [API](#api)
  * [Instructions](#instructions)
  * [License](#license)
  * [Questions](#questions)
<br>

### Database

![Database](https://user-images.githubusercontent.com/78758382/116605773-7519a180-a8f5-11eb-8c97-ff33890788c4.png)


This application consists of four tables: Categories, Products, Tags and Product Tags.

#### Category

![Categories](https://user-images.githubusercontent.com/78758382/116605959-adb97b00-a8f5-11eb-902c-154494389e4e.png)

Categories describe the product type like shirts, pants, etc.

#### Products

![Products](https://user-images.githubusercontent.com/78758382/116605869-97132400-a8f5-11eb-9dee-f3fbc871ddde.png)

Products refers to the actual products available in the e-commerce site. It includes information like the product name, price, how much stock is available, and what category it belongs to.

#### Tags

![Tags](https://user-images.githubusercontent.com/78758382/116605959-adb97b00-a8f5-11eb-902c-154494389e4e.png)

Tags are used to describe the products further. While categories explained what type of product each item is, tags describe product color like red, green, gold or the product description like whether the product is about rock or pop music.

#### Product Tags

![Product Tags](https://user-images.githubusercontent.com/78758382/116605999-b90ca680-a8f5-11eb-89fc-d7b274ea9609.png)

Product tags are where the information about what types of tags each product has is stored. Each product can have several product tags for each type of tag the product has. 

<br>

### API

![API](https://user-images.githubusercontent.com/78758382/116606034-c32ea500-a8f5-11eb-99c1-4f19928f0306.png)

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
