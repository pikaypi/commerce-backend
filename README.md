# E-Commerce Back End

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Test](#tests)
- [Questions](#questions)

---
## Description

---
## Installation
[Watch a video walkthrough on installing this application](https://drive.google.com/file/d/14TiIdvnmsa3qiqg517rVvXiEbR-wjuCp/view)
1. Once you have cloned the code repository, open the .env.EXAMPLE file in the root directory and add your mysql password. Save the file and rename it .env
2. Navigate in the terminal into the root directory. Here we will open the mysql shell and set up the tables. Execute the ```mysql -u root -p``` in the and enter your sql password (the same one you entered into the .env file)
3. Inside the shell execute ```source db/schema.sql```. When that finishes close the terminal by executing ```\q```
4. Seed the database by executing ```npm run seed``` in the root directory.
5. Start the server by executing ```npm run start``` in the root directory.

---
## Usage
[Watch a video walkthrough on the usage of this application](https://drive.google.com/file/d/1zuftv-qnsmqdqPxX8OxkzhIjICCKpq5Y/view)

The following url endpoints will return the following operations

GET routes
- /api/categories returns all categories
- /api/categories/id returns the product with the given id
- /api/tags returns all tags
- /api/tags/id returns the tag with the given id
- /api/products returns all products
- /api/products/id returns the product with the given id

POST routes
- /api/categories creates a new category using the data in the request body
- /api/tag creates a new tag using the data in the request body
- /api/product creates a new product using the data in the request body

PUT routes
- /api/categories/id updates the category with the given id using the data in the request body
- /api/tags/id updates the tag with the given id using the data in the request body
- /api/products/id updates the product with the given id using the data in the request body

DELETE routes
- /api/categories/id deletes the cateogry with the given id 
- /api/tags/id deletes the tag with the given id 
- /api/products/id deletes the product with the given id 



---
## Tests
There are currently no test for this application.

---
## Questions
[https://github.com/pikaypi](https://github.com/pikaypi)

---
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
