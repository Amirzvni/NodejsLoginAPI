# node-mongo-registration-login-api

NodeJS + MongoDB API for User Management, Authentication and Registration


استارت سرور 

`npm install
&&
npm start
`



ساخت یوزر جدید 
<br>
`req : POST`

`endpoint : http://localhost:4000/users/register`

`body : {
    "firstName": "amir",
    "lastName": "rezvani",
    "username": "amir85",
    "password": "123"
}`
<br>
ورود یوزر
<br>
`req : POST
endpoint : http://localhost:4000/users/authenticate
body : {
    "username": "amir85",
    "password": "123"
}
`
<br>
دریافت تمام کاربران
<br>
`req : GET
endpoint : http://localhost:4000/users
Authorization : Bearer Token
`
<br>
آپدیت کاربران
<br>
`
req : PUT
endpoint : http://localhost:4000/users/{id}
body : {
    "firstName": "amir hossein",
    "lastName": "rezvani"
}
`
