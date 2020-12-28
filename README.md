# How To set up Node Express step by step

## Setup Node express and express templates
-   npm init -y
-   npm install express
-   npm install express-es6-templates-engine
-   npm install --save-dev nodemon

## Set up package.json
-   In the `package.json` go under `scripts` and add the `"Dev": "nodemon index.js",`
    - This will allow for you to run nodemon on just the folder with the command `npm run dev`

## Make folder and files
-   In the terminal use code `mkdir templates` to make `Templates` folder in the project folder.
    - This will allow for you to make your templates file within that folder that can be called using `res.render` in the `index.js` file.
- In order to make files from your terminal use the code `touch index.js` or whatever file you would like to make ie. `.html` for your templates folder.

## Setup index.js
-  See attached `express-templet.js` file