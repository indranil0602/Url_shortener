This is an web based project which takes long url as input and returns a short url.

Technology Used:
npm, express, node js, mongodb

Create package.json.
Install node modules express, shortid, ejs, nodemon, mongoose and update package.json.
Update "scripts" object of package.json as following:
  "devStart": "nodemon server.js"
Set PORT at server.js or by default it will run on port 3000.
Run this project and up the server with the following command in terminal:
  npm run devStart
Get the user interface on http://localhost:3000

Make change in ./server.js to change features of the application.
Make change in ./models/shortUrl.js to change model of data to store.
Make change in ./views/index.ejs to change the view or the user interface.
