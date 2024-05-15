# Simplifying API Development with Swagger Integration in Node.js and Express.js

Before we dive into the integration, make sure you have the following installed:
    **Node.js** and **npm**
    **Express.js**

## Step 1: Setting Up a New Express.js Project
Initialize a new Node.js project and install Express.js:
```
npm init -y
npm install express
```

## Step 2: Installing Swagger Tools
Run the following commands in your terminal :
```
npm install swagger-jsdoc swagger-ui-express
```
## Step 3 : Configuring Swagger
Create a new file named [swagger.js](https://github.com/nesrine-snoussi/Swagger-Integration-in-Express.js/blob/master/swagger.js) to configure Swagger in your project.

## Step 4 : Integrating Swagger with Express.js 
Integrate Swagger into our Express.js project by updating the [app.js](https://github.com/nesrine-snoussi/Swagger-Integration-in-Express.js/blob/master/app.js) file.

## Step 5 : Writing API Documentation 
You can find an example of how to write the API documentation in this file [sample.js](https://github.com/nesrine-snoussi/Swagger-Integration-in-Express.js/blob/master/routes/sample.js) .

## Step 6 : Running Your Express.js Server 
Start your server and visit http://localhost:3000/api-docs in your browser to access the Swagger UI and explore your API documentation.
