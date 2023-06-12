In the Client Folder create .env file and put the below code inside it.

.env
```
REACT_APP_SERVER_DOMAIN='<server_domain>' # example 'http://localhost:8080'
```


After that create a file in the Server Folder with the name config.js(or as .env) and put the below code inside it.

config.js
```
export default {
    JWT_SECRET : "<secret>",
    EMAIL: "chathuradeshan28@gmail.com", // testing email & password
    PASSWORD : "sMf46xCzrvdrxvuagc",
    ATLAS_URI: "mongodb+srv://Admin:Admin8750@qr.7eqphv7.mongodb.net/"
}
```
