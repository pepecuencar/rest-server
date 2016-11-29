# REST API with Express example with MongoDB and Mongoose

This example was taken out from the course "Server-side Development with NodeJS" by The Hong Kong University of Science and Technology
This will contain 3 models and routes for it (Dishes, Leaders and promotions). You can analize the schemas implemented on models and the available routes.

* For more information please go to the coursera course on the following link:
https://www.coursera.org/learn/server-side-development

# Pre requisites: NodeJS and MongoDB

* NodeJS. Download the version from the following link 
https://nodejs.org/en/download/

* MongoDB. Download the community version from the following link
https://www.mongodb.com/download-center?jmp=nav#community

- Have the MongoDB Server running on port 27017
- Have a DB name "conFusion"

# Instructions

1. Clone the repository. This is an already express application scaffolded created by using express. (The command I used to create this was express rest-server) 

2. Go to the folder that you just created and over that folder run the following commands to include all Node Modules (Moongoose and Mongoose Currency)
npm install     
npm install mongoose mongoose-currency --save

3. Run the following command to start the server
npm start

4. You can post this examples to dishes route using the following json document
 {
 "name": "Uthapizza",
 "image": "images/uthapizza.png",
 "category": "mains",
 "label": "Hot",
 "price": "4.99",
 "description": "A unique combination of Indian ",
 "comments":[]
 }      

