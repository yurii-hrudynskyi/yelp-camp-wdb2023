A recreated version of Colt Steele`s famous YelpCamp from The Web Developer Bootcamp 2023 course on  [Udemy](https://www.udemy.com/course/the-web-developer-bootcamp) and [GitHub](https://github.com/Colt/YelpCamp).

A fully functioning and responsive web application that allows users to create, edit, and view existing campgrounds around the world. To do that, they need to create an account. 

### Back-End:
* Express
* MongoDB + Mongoose
* Cloudinary and Multer for picture download
* Passport for authentication and authorization
* Helmet, JOI, and Sanitize HTML for security

### Front-End:
* EJS
* Flesh
* Bootstrap
* Mapbox for creating an interactive map

To run the app please make sure you have MongoDB installed and a Cloudinary for the file .env file in the root:
```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

Run nodemon app.js
