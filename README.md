# BlanjaWEB With React

## About the project

Project membuat front-end blanja web menggunakan React dan database MYSQL.

## Build with Project
* [ReactJS](https://reactjs.org/)
* [MYSQL](https://www.mysql.com/)

## Getting Started
Berikut panduan untuk menjalankan project ini secara lokal
### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Vsept17/BlanjaWeb-ReactJS
   ```
2. Install yarn packages
   ```sh
   yarn
   ```
   This will install the dependencies inside `node_modules`
### ENV configuration

Please create and make the changes in the .env file.
```
"REACT_APP_URL"="YOUR_IP_DATABASE"
```
### Usage

`node index` OR `nodemon start` OR `npm start`

Runs the app in the development mode.<br>
Open [http://107.20.36.53:3000/](http://107.20.36.53:3000/) to view it in the browser.

### Endpoint

| Method | Endpoint | Description |
| --- | --- | --- |
| POST | /auth/register | Register New User |
| POST | /auth/login | Login User |
| POST | /auth/logout | Logout User |
| GET | /auth/verify | Activate User Account |
| POST | /auth/forgot | Forgot Password User |
| POST | /auth/otp | Verif OTP Forgot Password |
| PATCH | /auth/reset | Reset Password User |

* /product/:id
* /mybag
* /checkout
* /category
* /inputProduct
* /login
* /register
* /konfirmasi
* /reset-password
* /update
