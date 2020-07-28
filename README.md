# eCommerce Back-End
>A program that allows users to access and manipulate a database.

## Table of contents
* [General info](#general-info)
* [Installation](#installation)
* [Functionality](#functionality)
* [Status](#status)
* [Link](#link)
* [License](#license)
* [Contact](#contact)

## General info
This app will allow you to create and update database information for an eCommerce site with the ability to create, change, and delete information on the database.

## Installation
Steps required to install project and how to get the development environment running:

To generate your Database:

- Clone this repository to your own system.
- Run npm install from the command line in the root directory.
- Login to your MySql through the command line, then run "source db/schema.sql". Then Exit MySql.
- Run "npm run seed" in the command line to seed your database.
- Invoke the application with "npm start".

## Functionality
After starting the program with "npm start", open your Insomnia App and proceed to the route http://localhost:3001/api/categories/, http://localhost:3001/api/products, or http://localhost:3001/api/tags. Depending on what you would like to do, you can GET all the database information from each endpoint, POST new data to the Database, change the database information with a PUT request and the ID number of the item you would like to change at the end of the route (i.e.http://localhost:3001/api/categories/6), or DELETE an item in the database by selecting the item with the id at the end of the route.

## Status
Project is: _complete_ (for now)

## Links
Respository Link - https://github.com/JohnNielsen1221/ecommerce-back-end
Demo Video Link - https://drive.google.com/file/d/1iYC09wiaAhh1Puna67LYRHgTFfCoZvqw/view


## License
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Contact
Created by John Hayes Nielsen - johnhayesnielsen@gmail.com