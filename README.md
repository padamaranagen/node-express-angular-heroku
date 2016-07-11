1.	Create a repo called node-express-angular
 ![alt tag](https://github.com/nagendramca2011/node-express-angular/blob/master/public/img/repo.jpg)
2.	Clone the repository to the directory C using below

git clone https://github.com/nagendramca2011/node-express-angular.git

3.	Navigate to above directory
C:\>cd node-express-angular
4.	Initialize npm

C:\node-express-angular>npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg> --save` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
name: (node-express-angular)
version: (1.0.0)
description: sample application using node,express and angular
entry point: (index.js)
test command:
git repository: (https://github.com/nagendramca2011/node-express-angular.git)
keywords: angular,express,node
author: Padamara Nagendra
license: (ISC)
About to write to C:\node-express-angular\package.json:

{
  "name": "node-express-angular",
  "version": "1.0.0",
  "description": "sample application using node,express and angular",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/nagendramca2011/node-express-angular.git"
  },
  "keywords": [
    "angular",
    "express",
    "node"
  ],
  "author": "Padamara Nagendra",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/nagendramca2011/node-express-angular/issues"
  },
  "homepage": "https://github.com/nagendramca2011/node-express-angular#readme"
}


Is this ok? (yes) Yes


5.	Add Express Dependencies

C:\node-express-angular>npm install express --save
express@4.14.0 node_modules\express
├── escape-html@1.0.3
├── array-flatten@1.1.1
├── cookie-signature@1.0.6
├── utils-merge@1.0.0
├── etag@1.7.0
├── path-to-regexp@0.1.7
├── range-parser@1.2.0
├── parseurl@1.3.1
├── cookie@0.3.1
├── encodeurl@1.0.1
├── merge-descriptors@1.0.1
├── content-type@1.0.2
├── vary@1.1.0
├── content-disposition@0.5.1
├── methods@1.1.2
├── fresh@0.3.0
├── serve-static@1.11.1
├── depd@1.1.0
├── qs@6.2.0
├── finalhandler@0.5.0 (unpipe@1.0.0, statuses@1.3.0)
├── debug@2.2.0 (ms@0.7.1)
├── proxy-addr@1.1.2 (forwarded@0.1.0, ipaddr.js@1.1.1)
├── on-finished@2.3.0 (ee-first@1.1.1)
├── type-is@1.6.13 (media-typer@0.3.0, mime-types@2.1.11)
├── accepts@1.3.3 (negotiator@0.6.1, mime-types@2.1.11)
└── send@0.14.1 (destroy@1.0.4, ms@0.7.1, statuses@1.3.0, mime@1.3.4, http-error
s@1.5.0)

6.	See which was added or not
 
C:\node-express-angular>type package.json
{
  "name": "node-express-angular",
  "version": "1.0.0",
  "description": "sample application using node,express and angular",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/nagendramca2011/node-express-angular.git"
  },
  "keywords": [
    "angular",
    "express",
    "node"
  ],
  "author": "Padamara Nagendra",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/nagendramca2011/node-express-angular/issues"
  },
  "homepage": "https://github.com/nagendramca2011/node-express-angular#readme",
  "dependencies": {
    "express": "^4.14.0"
  }
}

7.	Add Bower Dependency
C:\node-express-angular>npm install bower --save
bower@1.7.9 node_modules\bower
8.	Check bower is installed or not

C:\node-express-angular>type package.json
{
  "name": "node-express-angular",
  "version": "1.0.0",
  "description": "sample application using node,express and angular",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/nagendramca2011/node-express-angular.git"
  },
  "keywords": [
    "angular",
    "express",
    "node"
  ],
  "author": "Padamara Nagendra",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/nagendramca2011/node-express-angular/issues"
  },
  "homepage": "https://github.com/nagendramca2011/node-express-angular#readme",
  "dependencies": {
    "bower": "^1.7.9",
    "express": "^4.14.0"
  }
}
9.	Which version of node you working that you need to add it in package.json
C:\node-express-angular>node -v
v4.4.4

C:\node-express-angular>type package.json
{
  "name": "node-express-angular",
  "version": "1.0.0",
  "description": "sample application using node,express and angular",
  "main": "index.js",
  "engines": {
    "node": "4.4.4"
  },
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/nagendramca2011/node-express-angular.git"
  },
  "keywords": [
    "angular",
    "express",
    "node"
  ],
  "author": "Padamara Nagendra",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/nagendramca2011/node-express-angular/issues"
  },
  "homepage": "https://github.com/nagendramca2011/node-express-angular#readme",
  "dependencies": {
    "bower": "^1.7.9",
    "express": "^4.14.0"
  }
}

10.	We need to specify the path of the bower install inside package.json file

C:\node-express-angular>type package.json
{
  "name": "node-express-angular",
  "version": "1.0.0",
  "description": "sample application using node,express and angular",
  "main": "index.js",
  "engines": {
    "node": "4.4.4"
  },
  "scripts": {
     "postinstall": "./node_modules/bower/bin/bower install"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/snagendramca2011/node-express-angular.git"
  },
  "keywords": [
    "angular",
    "express",
    "node"
  ],
  "author": "Padamara Nagendra",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/nagendramca2011/node-express-angular/issues"
  },
  "homepage": "https://github.com/nagendramca2011/node-express-angular#readme",
  "dependencies": {
    "bower": "^1.7.9",
    "express": "^4.14.0"
  }
}

11.	Express as a webserver
Create a new file in the root of your project named app.js to server static files.
app.js
var express = require('express');
var app = express();
app.use(express.static(__dirname + '/public'));
var port = process.env.PORT || 8000;
app.listen(port, function(){
        console.log('listening on', port);
});
12.	Define a Procfile
We need to tell Heroku what it needs to do to start your app : Create file named Procfile in the root of your project and add :

web: node app.js

This tells Heroku to launch node using the app.js file.

13.	There is a file in your git root directory named .gitignore. It's a file, not a command. You just need to insert the names of the files that you want to ignore, and they will automatically be ignored. Create a file and add:

node_modules
public/bower_components

14.	Front-end dependencies creation using below

C:\node-express-angular>bower init
? name node-express-angular
? description sample application using node,express and angular
? main file index.js
? keywords angular,express,node
? authors Padamara Nagendra
? license ISC
? homepage https://github.com/nagendramca2011/node-express-angular
? set currently installed components as dependencies? Yes
? add commonly ignored files to ignore list? Yes
? would you like to mark this package as private which prevents it from being ac
cidentally published to the registry? No

{
  name: 'node-express-angular',
  description: 'sample application using node,express and angular',
  main: 'index.js',
  authors: [
    'Padamara Nagendra'
  ],
  license: 'ISC',
  keywords: [
    'angular',
    'express',
    'node'
  ],
  homepage: 'https://github.com/nagendramca2011/node-express-angular',
  ignore: [
    '**/.*',
    'node_modules',
    'bower_components',
    'test',
    'tests'
  ]
}

? Looks good? Yes

15.	Add the dependencies
    "bootstrap": "3.3.6",
    "angular": "^1.5.5",
    "angular-route": "^1.5.6",
    "font-awesome": "^4.6.3"

C:\node-express-angular>type bower.json
{
  "name": "node-express-angular",
  "description": "sample application using node,express and angular",
  "main": "index.js",
  "authors": [
    "Padamara Nagendra"
  ],
  "license": "ISC",
  "keywords": [
    "angular",
    "express",
    "node"
  ],
  "homepage": "https://github.com/nagendramca2011/node-express-angular",
  "ignore": [
    "**/.*",
    "node_modules",
    "bower_components",
    "test",
    "tests"
  ],
  "devDependencies": {
    "bootstrap": "3.3.6",
    "angular": "^1.5.5",
    "angular-route": "^1.5.6",
    "font-awesome": "^4.6.3"
  }
}

16.	 Install bower dependencies using 

C:\node-express-angular>bower install
bower cached        https://github.com/twbs/bootstrap.git#3.3.6
bower validate      3.3.6 against https://github.com/twbs/bootstrap.git#3.3.6
bower cached        https://github.com/angular/bower-angular.git#1.5.7
bower validate      1.5.7 against https://github.com/angular/bower-angular.git#^
1.5.5
bower cached        https://github.com/FortAwesome/Font-Awesome.git#4.6.3
bower validate      4.6.3 against https://github.com/FortAwesome/Font-Awesome.gi
t#^4.6.3
bower cached        https://github.com/angular/bower-angular-route.git#1.5.7
bower validate      1.5.7 against https://github.com/angular/bower-angular-route
.git#^1.5.6
bower cached        https://github.com/jquery/jquery-dist.git#2.2.4
bower validate      2.2.4 against https://github.com/jquery/jquery-dist.git#1.9.
1 - 2
bower install       font-awesome#4.6.3
bower install       angular-route#1.5.7
bower install       angular#1.5.7
bower install       bootstrap#3.3.6
bower install       jquery#2.2.4

font-awesome#4.6.3 bower_components\font-awesome

angular-route#1.5.7 bower_components\angular-route
└── angular#1.5.7

angular#1.5.7 bower_components\angular

bootstrap#3.3.6 bower_components\bootstrap
└── jquery#2.2.4

jquery#2.2.4 bower_components\jquery

17.	Add .bowerrc files and add 

{
  "directory": "public/bower_components"
}
18.	 Copy sample project folder

C:\node-express-angular\public>tree /f
Folder PATH listing
Volume serial number is 5EF4-DE84
C:.
│   apple-touch-icon-precomposed.png
│   favicon.ico
│   index.html
│
├───css
│       main.css
│
├───js
│       main.js
│
├───partials
│       404.html
│       about.html
│       blog.html
│       blog_item.html
│       contact.html
│       faq.html
│       home.html
│       pricing.html
│       services.html
│
└───templates
        footer.html
        header.html



