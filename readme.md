create a folder
open terminal
npm init
npm i express passport  passport-oauth2 ejs nodemon cookie-session dotenv
code .
// open package.json and change scprit
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
    } 

    to

    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "start": "nodemon app.js"
    }

// create app.js file

// now we need to require export in aap.js 

