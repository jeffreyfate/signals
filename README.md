#Signals

[![serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com)

A service that provides updates to current content in streaming services.

##Install

Make sure you have the [Serverless Framework](http://www.serverless.com) installed and you're using Node.js v4.0+.
```
npm install serverless -g
```

Install the project using Serverless:
```
serverless project install signals
```

Install project dependencies via npm:
```
npm install
```

Deploy your functions and endpoints:
```
serverless dash deploy
```

##Includes

This project contains the following:

* **Multi:** Multiple functions each containing a single endpoint
* **Single:** A single function that uses multiple endpoints.
* **Optimizer Plugin:**  Each function is automatically optimized via the [serverless-optimizer-plugin](https://www.github.com/serverless/serverless-optimizer-plugin)
* **Templates:** Templates are used to reduce configuraton syntax
* **REST API Parameters:** The Multi/Show function endpoint gives an example of how to accept a path parameter

##Setup

1. ```npm install serverless -g```
2. ```serverless project install serverless-starter```
3. Create Github repo for new function
4. Edit README.md and other configuration with new repo information
5. ```git remote add origin https://github.com/{ACCOUNT}/{REPO}.git```
6. ```git add {CHANGED_OR_NEW_FILES}```
7. ```git commit -m {MESSAGE}```
8. ```git push -u origin master```
