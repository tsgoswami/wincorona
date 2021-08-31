


# ✨ Wincorona✨

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/tsgoswami)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/tsgoswami) [![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/tsgoswami)

<p align="center">
Wincorona is an application developed for non profit during the 2nd phase of covid in India when there was a scarcity of oxygen, blood plasma and people were sharing information about oxygen and blood supplier over social media and it was really hard to keep track of those information. This app is design to solve that problem. The application allows to get information related to required items using pincode. Anyone can use their pincode and search oxygen, blood plasma etc and if the information is available it will be shown in the results. If users are not satisfied with the results then they can post in the ask for help section. 
</p>

Deployed Production Link - [Live URL]
<br>
Documentation generated using Postman - [API Documentation] 

## Core Features
- Get oxygen supplier, blood plasma donor, etc. just by entering your pincode.
- Post for Help if not satisfied with the search result.
- Register and Login to become active contributor.
- Contribute by posting information about oxygen supplier, blood plasma donor, etc. to help others.

## Technology Stack
<b>Frontned</b> : React.js
<br>
<b>Additional Libraries</b>
 - Material UI
 - Axios
 - React Router DOM
 - React Toast Notification
 -  JSON Web Token
<br>

<b>Backend</b> : Node.js
<br>
<b>Additional Libraries</b>
  - Axios
  - Bcrypt JS
  - Body Parser
  - CORS
  - Express
  - Express Validator
  - Google APIs
  - Mongoose
  - Morgan
  - Multer
  - Nodemailer
<br>
<br>
<b>Language<b>: TypeScript
<br>
<b>Database: MongoDB</b>
<br>  
<b>Authentication and Authorization<b> : Basic Auth, JWT and  Google Auth2.0
<br>
<b>Deployement</b> : Netlify and Heroku
<br>




## Setup
##### Environmental Variables for Backend
```
- BASE_URL = Set your frontend URL e.g - localhost:3000 for development
- PIN_API = https://api.postalpincode.in/pincode
- SECRET = eg. eyJhbGciOiJIUzI1NiIsInR ... for generating JWT Tokens
- MONGODB_URI_PROD = URI for connecting to MongoDB Database.
- MONGODB_POOLSIZE = 10 or you can set to your custom
- MAIL_SERVER_HOST = eg. smtp.gmail.com - Set it to yours.
- MAIL_USER = eg. youremail@gmail.com 
- SUPER_ADMIN_NAME = eg. SUPER ADMIN or Set it as per your choice.
- SUPER_ADMIN_EMAIL = eg. admin@gmail.com 
- SUPER_ADMIN_PHONE = eg. 8981430145
- SUPER_ADMIN_PASSWORD = eg. PassDum@123 or Set Default Password for Admin
- PORT = 8080 or Set Default Port
- CLIENT_ID = Client ID generated by Google Cloud Console for Oauth2.0
- CLIENT_SECRET = Client Secret generated
- REFRESH_TOKEN = Refresh token generated
- REDIRECT_URL = eg https://developers.google.com/oauthplayground 
```
For seting up Oauth2.0 on GCC. Refer here - [Sending Email with Gmail and Oauth2.0]

Backend
```
cd backend
npm install
npm run local -- for development or npm start -- for production
```
Frontend
```
cd frontend
npm install
npm start
```
  
 ***Glad to see you here! Show some love by [starring](https://github.com/tsgoswami/Wincorona) this repo.***

[![Facebook](https://img.shields.io/static/v1.svg?label=follow&message=@tsgoswami&color=black&logo=facebook&style=flat&logoColor=white&colorA=blue)](https://www.facebook.com/trishnangshu.goswami/)  [![Instagram](https://img.shields.io/static/v1.svg?label=follow&message=@tsgoswami&color=black&logo=instagram&style=flat&logoColor=white&colorA=blue)](https://www.instagram.com/letstalkcs/) [![LinkedIn](https://img.shields.io/static/v1.svg?label=connect&message=@tsgoswami&color=black&logo=linkedin&style=flat&logoColor=white&colorA=blue)](https://www.linkedin.com/in/trishnangshugoswami/) [![Twitter](https://img.shields.io/static/v1.svg?label=connect&message=@tsgoswami&color=black&logo=twitter&style=flat&logoColor=white&colorA=blue)](https://twitter.com/ts_goswami)

> Made with 🖤 by Trishnangshu Goswami

[Sending Email with Gmail and Oauth2.0]: https://medium.com/@nickroach_50526/sending-emails-with-node-js-using-smtp-gmail-and-oauth2-316fe9c790a1

[API Documentation]: https://documenter.getpostman.com/view/11794310/U16bx9tr
[Live URL]: https://heuristic-hugle-cf67ea.netlify.app/#/
