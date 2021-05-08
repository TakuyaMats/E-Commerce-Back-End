# E-Commerce-Back-End

1. [ Overview. ](#overview)
2. [ Web Address. ](#web-address)
3. [ Usage tips. ](#usage)
4. [ Credits. ](#credits)
5. [ License. ](#license)

<a name="overview"></a>

## 1. Overview

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### This is Takuya Matsumoto's E-Commerce Back End

<a name="web-address"></a>

## 2. Site Links & Video Demonstration

### Application Demonstration

---

![Video-Demo](./Video-Demo/APPLICATION-DEMO.gif "Video")

### Category Demonstration

---

![Video-Demo](./Video-Demo/CATEGORY-DEMO.gif "Video")

### Product Demonstration

---

![Video-Demo](./Video-Demo/PRODUCT-DEMO.gif "Video")

### Tag Demonstration

---

![Video-Demo](./Video-Demo/TAG-DEMO.gif "Video")

[github repository site] https://github.com/TakuyaMats/E-Commerce-Back-End.git

<a name="usage"></a>

## 3. Usage Tips

To run the program type this in the integrated terminal:

`node server.js`

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

```

<a name="credits"></a>

## 4. Credits

- Ben Durham: [https://github.com/bdurham227]

<a name="license"></a>

## 5. License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

MIT License

Copyright (c) [2021] [Takuya Matsumoto]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
