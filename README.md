# face-recognate-api

## General info
This repo is back-end part of the [face-recognate](https://github.com/mahmutsen/face-recognate) project which "detects faces on images you upload with relative urls.
	
## Technologies
Some key ones:
* **nodejs** runtime enviroment: 12.14.1
* **express** web framework version: 4.17.1
* **clarifai** api version: 2.9.1
* **bcryptjs** package version: 2.4.3
	
## Setup
```
$  clone this repo
$ npm install
$ npm start
```
## You must add your own API key in the controllers/image.js file to connect to Clarifai API.

You can grab Clarifai API key [here](https://www.clarifai.com/)
