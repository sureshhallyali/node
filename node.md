Node.js is an open-source, cross-platform, 
JavaScript runtime environment build on chrome  that executes JavaScript code outside of a browser.

npm init --yes
npm install express body-parser --save
npm install --save mongoose


To npm to initialtial project  setup of project
    npm init --y 
    	--y (yes) set the default setting and it will create file  package.json 
To install package  
    npm install package_name 
        	 for 'install'  shortcut we can use 'i'
To install as dependencies package
    npm i --save package_name
To install as development dependancy package
    npm i --save-dev package_name


node js Package list
Inbuilt node packages
    http	-->For http req handling.
    file	--> For handing file System.
    crypto	--> use to perform cryptographic operations on data
    
Third party node packages
    express		--> Framework
    express-promise-router
    mongodb,		--> MongoDb deiver
    mongoose		--> MongoDb deiver
    body-parser		-->For exatracting data from  request body
    jsonwebtoken(JWT) -->For token generate
    bcrypt
    morgan      -->
    socket.io 
    passport 	-->
    joi         -->For validation
    dotenv      -->secreate environment varibale
    nodemon	-->restart Server at every save file automatically
    Bcrypt      -->To allow cryptography   password hashing function designed

    Express.js, or simply Express, is a web application framework for Node.js,
    Released as free and open-source software under the MIT License.It is designed for building web applications and APIs.
    It has been called the de facto standard server framework for Node.js.

    body-parser
    body-parser extract the entire body portion of an incoming request stream and exposes it on req.body.
    The middleware was a part of Express.js earlier but now you have to install it separately. 
    This body-parser module parses the JSON, buffer, string and URL encoded data submitted using HTTP POST request.

    Morgan 
    Morgan is a HTTP request logger middleware for Node.js. Morgan is basically a logger, on any requests being made,it     	generates logs automatically.
    It simplifies the process of logging requests to your application. 
    You might think of Morgan as a helper that generates request logs.
    For example, Morgan can write requests in the Apache common format, split logs across outputs, and 
    automatically rotate log files.

    Nodemon 
    Nodemon is a utility that will monitor for any changes in your source and automatically restart your server. 
    Perfect for development. Install it using npm. Just use nodemon instead of node to run your code, 
    and now your process will automatically restart when your code changes.
    need to add in (package.json)  script  "devStart":nodemon server.js"
    Which allows to  restart server automatically.

    CORS
    Cross-Origin Resource Sharing (CORS) is a mechanism that uses additional HTTP headers to tell 
    browsers to give a web application running at one origin, access to     selected resources from a different origin.
    A web application executes a cross-origin HTTP request when it requests a resource that has a different 
    origin (domain, protocol, or port) from its own.
    An example of a cross-origin request: the front-end JavaScript code served from https://domain-a.com uses
	XMLHttpRequest 
    to make a request for     https://domain-b.com/data.json.
    example     var cors = require('cors');
                app.use(cors());


      dotenv
	Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env. 
	Storing configuration in the environment separate from code is based on The Twelve-Factor App methodology.
	example 
		create .env file and write like the
			DB_HOST=localhost
			DB_USER=root
			DB_PASS=s1mpl3
 		call in your file   require('dotenv').config() 
	useage 
		process.env.PORT	


    hbs is a express.js wrapper for the handlebars.js javascript template engine.
    Handlebars.js is a template engine to make writing html code easier, if intrested you can look here.
    ... A wrapper makes it possible to use for example a client-side library in express.js and that is what hbs does.
    
    
    
 Resource   
 Codevolution
https://www.youtube.com/watch?v=ozXGkqpzo_A&list=PLC3y8-rFHvwg2RBz6UplKTGIXREj9dV0G&index=1
https://www.youtube.com/watch?v=cAN71OrRlzc&list=PLC3y8-rFHvwg2RBz6UplKTGIXREj9dV0G&index=12
https://codequs.com/p/BkqKxaZ_N/using-apache-spark-to-query-a-remote-authenticated-mongodb-server
https://www.youtube.com/user/edurekaIN/playlists

All querys of mongodb
https://www.quackit.com/mongodb/tutorial/mongodb_limit_query_result
s.cfm

mongodb core explaine in video
https://www.youtube.com/watch?v=RPf4RBg-vPU&list=PLWPirh4EWFpG2gpAkHVocvvzIWNGet2BF&index=9 


node js jwt explation
https://www.youtube.com/watch?v=2jqok-WgelI
https://medium.com/dev-bits/
a-guide-for-adding-jwt-token-based-authentication-to-your-single-page-nodejs-applications-c403f7cf04f4

https://www.youtube.com/watch?v=elgGfsqG8nU&list=PLy9JCsy2u97k6olfalMTA_XSPz4pNuT46&index=3

https://www.youtube.com/user/thenewboston/channels

