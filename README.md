# NodeJs-Notes


## Node-Package-Manager

**Syntax:** npm Command -PrePackageCommand Package --PostPackageCommand  
  
**Save dependencies in project:** --save  
**Save dependencies temporary:** --no-save  
**Save dependencies globally:** -g  
**Save as development-dependencies:** -D  

### Files  
**Package.json:** 
* lists all required dependencies  
* defines entry point  
 
**Package-Lock.json:** lists all current dependencies  

### Commands

**Generate Package.json File:** npm init  
**INstall all Packages from Packages.json**: npm install  
**Install Express.js locally:** npm install express --save  
**Install Nodemon.js globally:** npm install -g nodemon  

### Useful Packages  
[Routing-Controllers](https://github.com/typestack/routing-controllers)  
[uuid](https://github.com/kelektiv/node-uuid)  
[purify](https://github.com/gigobyte/purify)  

## Syntax

### Import modules
**include Absolute-Path:** const module = require("Absolute-Path");  
**include Relative-Path:** const module = require("./Relative-Path");  
**Parent-Directory:** ../  

