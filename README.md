# BlanjaWEB With React

## About the project

Project membuat front-end blanja web menggunakan React dan database MYSQL.

## Build with Project
* [ReactJS](https://reactjs.org/)
* [MYSQL](https://www.mysql.com/)
* [AWS](https://www.awseducate.com/)

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

| Endpoint | Description |
| --- | --- |
| /register | Register New User |
| /login | Login User |
| /logout | Logout User |
| /forgot | Forgot Password User |
| /otp | Verif OTP Forgot Password |
| /confirm | Set New Password |
| /reset | Reset Password User |
| / | Home Pages |
| /products/:id | Detail Product |
| /mybag | My Bag Pages |
| /checkout | Pages Checkout |
| /search?keyword="keyword" | Search Feature |
| /filter?category="key_category"&size="key_size"&color="key_color" | Fiter Search |
| /category/"id_category"?keyword="category_name" | Sort By Category |
| /myprofile | My Profile Pages |
| /shippingaddress | Shipping Address Pages |
| /myorder | My Order Pages |
| /myproducts | My Products Seller Pages |
| /edit/:id | Edit Product Pages |

### Photo Documentation
## Home
![screenshot-107 20 36 53_3000-2021 02 19-21_25_01](https://user-images.githubusercontent.com/52094775/108523682-c9eed980-7300-11eb-9c88-b35eb828aa4f.png)
![web-detail](https://user-images.githubusercontent.com/52094775/108524059-3669d880-7301-11eb-81f4-b4c0595f6328.png)
![web-mybag](https://user-images.githubusercontent.com/52094775/108524082-3c5fb980-7301-11eb-9f68-75e907a6fcf9.png)
![web-checkout](https://user-images.githubusercontent.com/52094775/108524098-41246d80-7301-11eb-84b3-dc7be5a64e38.png)
![web-crudProd](https://user-images.githubusercontent.com/52094775/108524108-441f5e00-7301-11eb-8ca1-7dc4171fc748.png)

