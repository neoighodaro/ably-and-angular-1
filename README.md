# Ably-Angularjs

## Getting started with Ably and AngularJs - Making a food ordering app

This project is designed as part of an article on using Ably's Realtime Data Devliery platform to build real time applications using AngularJS.

It is really simple to get into. I made two simple html pages with bootstrap, pulling in Ably and Angular to make the app work.

There is really nothing to install. Just download and get started right away.

## Requirements

In order to run these tutorials locally, you will need an Ably `API key`. If you are not already signed up on [Ably](https://ably.io), you should [sign up now for a free Ably account](https://ably.io). Once you have an Ably account:

	
> 1. Log into your app dashboard	
> 2. Under “Your apps”, click on “Manage app” for any app you wish to use for this tutorial, or create a new one with the “Create New App” button	
> 3. Click on the “API Keys” tab	
> 4. Copy the secret “API Key” value from your Root key and store it so that you can use it later in this tutorial


## Setup
You would need to clone this repo and add your API key to the document. Go to your `terminal` and run the following commands:
```shell
$ git clone https://github.com/chiefoleka/ably-angularjs
$ cd ably-angularjs
$ nano index.html # replace API-Key-Here with your API Key
$ nano admin.html # replace API-Key-Here with your API Key
```
Once you are done, we are set to run this tutorial. Feel free to use any editor of your choice to edit both files.
If you have apache setup locally, then you can easily create a php server like this:
```shell
$ php -S localhost:8000
```
Go to your browser and visit `http://localhost:8000` to see the app.

That's it.