# RetailBackEnd

## Object-Relational Mapping (ORM) Challenge: E-commerce Back End


## Description

1. Set up project: Set up repo, identify issues. 
2. Scaffold application's architecture: Install npm packages. 
3. Create models (category, product, tag, productTag). 
4. Create routes. 
5. Test routes with insomnia. 

## Tasks 
- [x] Install npm packages (mysql2, sequelize, dotenv) 

- [x] Connect schema to database:

    - [x] put sql password and username in .env file (this is conected to 'connection.js')
    - [x] .gitignore env file 
    - [x] mysql -u root -p (log-in w/ password)
    - [x] source db/schema.sql
    - [x] show databases; (to check if datbase has be successfully created)
    - [x] use ecommerce_db; (to change into this database)

- [x] Define 'Category' columns 

- [x] Define 'Product' columns 

- [x] Define 'Tag' columns 

- [x] Define 'ProductTag' columns

- [x] Create Product routes

- [x] Create Category routes

- [x] Create Tag routes 

- [x] Connect seeds to database. 

- [x] Test routes on insomina.

## Pictures 
<img src="./assets/insomnia post.png" alt ="pic of app" title="Post" />
<img src="./assets/insomnia products pic.png" alt ="pic of app" title="Products" />
<img src="./assets/insomnia tags pic.png" alt ="pic of app" title="Tags" />
<img src="./assets/mysql pic 1.png" alt ="pic of app" title="Sql Pic" />
<img src="./assets/mysql pic 2png.png" alt ="pic of app" title="Sql pic" />


- (​GitHub Repo Page:) [https://github.com/Dre0239/RetailBackEnd]

## Notes
- added "seed": "node seeds/index.js" to scripts in package.json to connect seed files. 
## License

​MIT License
​
Copyright (c) [2023] [Andre Mays]
​
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
​
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
​
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.