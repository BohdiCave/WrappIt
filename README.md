# WrappIt

## Overview
Ahh, the holidays, the time of year when you can't figure out what to buy your loved ones. With our app, WrappIt, we make it easy to find that perfect gift. Just select that special person's top 3 interests from our categories of gifts and we'll wrap up a list of gifts specific to those interests. No need to fret, just WrappIt and gift it

## Table of Contents
- [Overview](#Overview)
- [Description](#Description)
- [Installation](#Installation)
- [Usage](#Usage)
- [WrappIt Screenshots](#Screenshots)
- [Built With](#Built)
- [Heroku](#Heroku)
- [License](#License)
- [Contributors](#Contributors)
- [GitHub](#GitHub) 

## Description
The WrappIt App is for users who are having trouble finding that perfect gift. Open source css framewok UIkit, New York Times API for books and movies, and eBay API for home decor, cooking, makeup, and video games & consoles were used to the WrappIt App.

## Installation
    `npm install dotenv` `npm install express` `npm install express-handlebars` `npm install mysql2` `npm install sequelize`  

## Usage
Run the following command at the root of your project and answer the prompted questions:

    `node server.js`
    
Once 'App listening on PORT: 8080' displays in your terminal, open your browser and search:

    `http://localhost:8080/`

## WrappIt Screenshots

### Main Page
<img src="public/assets/WrappIt01.png" alt="WrappIt App Main Page">

### Creating Account
<img src="public/assets/WrappIt02.png" alt="WrappIt App Creating Account">

### Selecting giftee's top 3 interests
<img src="public/assets/WrappIt03.png" alt="WrappIt App Selecting Interests">

### Results
<img src="public/assets/WrappIt04.png" alt="WrappIt App Results">

## Built With
* [UIkit](https://getuikit.com/) - Open Source CSS framework
* [New York Times - Books](https://api.nytimes.com/svc/books/v3/lists/current/hardcover-fiction.json?api-key=VygNZrSBD3hbAKYqxo7V4fGEvJSq8aux) - New York Times API for Books List
* [New York Times - Movies](https://api.nytimes.com/svc/movies/v2/reviews/search.json?critics-pick=Y&opening-date=2019-01-01;2020-09-01&api-key=xUVU76OUVbXKD94Ig4mUUmlvQJGAyTSQ) - New York Times API for Movies List
* [eBay - Home Decor](https://open.api.ebay.com/shopping?callname=FindProducts&responseencoding=JSON&appid=SuzanneG-WrappIt-PRD-1f785c25d-fb2797a7&siteid=0&version=967&QueryKeywords=homedecor&AvailableItemsOnly=true&MaxEntries=400) - eBay API for Home Decor.
* [eBay - Cooking](https://open.api.ebay.com/shopping?callname=FindProducts&responseencoding=JSON&appid=SuzanneG-WrappIt-PRD-1f785c25d-fb2797a7&siteid=0&version=967&QueryKeywords=cookbooks&AvailableItemsOnly=true&MaxEntries=100) - eBay API for Cooking, MakeUp, Video Games & Consoles.
* [eBay - Makeup](https://open.api.ebay.com/shopping?callname=FindProducts&responseencoding=JSON&appid=SuzanneG-WrappIt-PRD-1f785c25d-fb2797a7&siteid=0&version=967&QueryKeywords=makeup&AvailableItemsOnly=true&MaxEntries=100) - eBay API for MakeUp, Video Games & Consoles.
* [eBay - Video Games & Consoles](https://open.api.ebay.com/shopping?callname=FindProducts&responseencoding=JSON&appid=SuzanneG-WrappIt-PRD-1f785c25d-fb2797a7&siteid=0&version=967&QueryKeywords=games&AvailableItemsOnly=true&MaxEntries=95) - eBay API for Video Games & Consoles.

## Heroku 
To view the WrappIt application, click here:
https://intense-falls-86763.herokuapp.com/

## License
![License](https://img.shields.io/badge/License-mit-blue.svg "License Badge")

[MIT License](http://opensource.org/licenses/mit-license.php)

## Contributors
* **Suzanne Givnish** - UI (JavaScript, HTML, CSS, jQuery) / views (handlebars)
* **Bohdan Pechenyak** - Database setup / models
* **Brandon Ryu** - Server / Controllers / config

## Github Info
[Suzanne Givnish](https://github.com/suzygiv),
[Bohdan Pechenyak](https://github.com/BohdiCave),
[Brandon Ryu](https://github.com/bryu0116)



