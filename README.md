# Republican-Clarifai-Demo

This is a simple demo to show the use of the [Clarifai API](developer.clarifai.com). The site merely takes a photo of all the 2016 Republican Presidential Candidates in their serious faces and presents a series of phrases that describe all of them on a simple webpage.

# Getting Started

- Clone this project into your local files
- Create a free account on [Clarifai's developer site](developer.clarifai.com) and a new application
- Download [MAMP](https://www.mamp.info/en/downloads/) or any local server service of your choice and route it to your local project
- Create a `keys.js` file and have it contain the following:

```
var CLIENT_ID = 'your ID here';
var CLIENT_SECRET = 'your secret here';

```

- Once that is created, put it under the `js` folder. Then include it in your .gitignore file (security purposes)

To run:
 - Start your server on localhost and go to `localhost:8888`

Enjoy!
