<b>Step 1:</b>
cd .\e-commerce-api\\
<br>
<b>Step 2:</b>
npm i
<br>
<b>Step 3:</b>
(Type this command in a seperate terminal)
mongod
<ul>(Note: You need mongodb installed)</ul>
<br>
<b>Step 4:</b>
npm run dev
(In the previous terminal)
<br>
<br>
<b><ul>NOTE:</ul>b></ul></b>
Create a config folder in root directory of teh project
Create a dev.env file in the config folder
Include the following environment variables:
JWT_SECRET= Any secret key of your choice, it may be any string
PORT= The port you want oyur project to run on
MONGODB_URL= Your mongodb server url
