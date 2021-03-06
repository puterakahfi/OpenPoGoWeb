# Note that this project is deprecated and no further support will be provided for this repo. Use [OpenPoGoUi](https://github.com/OpenPoGo/OpenPoGoUI) with the latest version of [OpenPoGoBot](https://github.com/OpenPoGo/OpenPoGoBot) instead.

# OpenPoGoBotWeb
Web View for OpenPoGoBot and PokemonGo-Bot  

## Installation and Use
This project is a module of OpenPogoBot and PokemonGo-Bot.  
In case the module version has not been updated on those projects, you can run the following to update it:

```
$ cd OpenPoGoBot  
$ git submodule foreach git pull origin master  
```  

In the event that there is nothing in your web folder and the above doesn't do anything run the following:  

``` 
$ cd OpenPoGoBot  
$ git submodule init  
$ git submodule update  
```

Copy the userdata.js.example to userdata.js and update your settings  
YOU WILL NEED A GOOGLE MAPS API KEY   [Get one here](https://developers.google.com/maps/documentation/javascript/get-api-key)  

If you want to serve this as a webpage you will have to set up a webserver, for example:

```
$ cd OpenPoGoBot\web  
$ python -m SimpleHTTPServer
```  

This will enable you to view your page on [http://localhost:8000](http://localhost:8000)  

## Troubleshooting
1. If you have the latest code of both web and bot project and start the web server correctly, however you see a blank page when hit localhost:8000: clear your browser history data/cookie and try again. For Chrome user, try to open a Incognito window.

## Contributing
If you would like to contribute please review OpenPoGo's [contributing](https://github.com/OpenPoGo/OpenPoGoBot/blob/master/CONTRIBUTING.md) guidelines and submit a pull request.  
