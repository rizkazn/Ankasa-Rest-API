<h1 align="center">
  Ankasa Website (Ticketing)
</h1>

<p align="center">
  <a href="https://www.arkademy.com/auth/signup">
    <img src="https://www.arkademy.com/img/logo%20arkademy.1c82cf5c.svg" width="200px" alt="Arkademylogo.svg" />
  </a>
  <a href="https://www.fazztrack.com/">
    <img src="https://www.fazztrack.com/_nuxt/img/fazztrack-logo-color.db4c9cc.svg" width="200px" alt="Arkademylogo.svg" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/calvinrahmat/blanja.git">
    <img src="https://res.cloudinary.com/calvin-cloud/image/upload/v1631588597/Ankasa/Logo_Ankasa_cm4gp9.svg"  alt="LogoAnkasa">
  </a>
  
  <p align="center">
    <a href="https://github.com/calvinrahmat/back-ticketing.git"><strong>Explore the docs »</strong></a>
    <a href="http://ankasa.online/">View Demo</a>
  </p>
</p>

## Back to Frontend

<a href="https://github.com/Gustiana882/front-ticketing">https://github.com/rizkazn/front-ticketing</a>

## Built with

[![Express.js](https://img.shields.io/badge/Express.js-4.x-orange.svg?style=rounded-square)](https://expressjs.com/en/starter/installing.html)
[![Node.js](https://img.shields.io/badge/Node.js-v.12.13-green.svg?style=rounded-square)](https://nodejs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-v.13.3-blue.svg?style=rounded-square)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/Redis-v.6.2-red.svg?style=rounded-square)](https://redis.io/)

## Description about project
Ankasa is a flight ticket booking application project that was built and developed as a team. This application makes it easy for you to order airline tickets anywhere and anytime because it is based online. Built with React Js on the front, Node Js and Express Js on the back. The database used on this website is based on PostgreSQL which is operated using sequel. The features available on this website include flight search features, flight filters, and transit filters.

## Clone the repository

```bash

  git clone https://github.com/Gustiana882/back-ticketing.git
  
```

### Install dependencies
```bash

  yarn install
  
```

### run app
```bash

  cd back-ticketing

  yarn start
  
```

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn build`

```bash

  yarn run build
  
```
## for developer

### standar request login 
```bash
  {
    "email": "user",
    "password":"user1234"
  }
```

### standar request register
```bash
  {
    "name": "user",
    "email": "user@mail.com",
    "password": "user1234"
```

### standar response ticket API
```bash
  [
    { 
      "id" : "1",
      "uuid": "AB-221",
      "image": "img.jpg",
      "maskapai" : "Garuda Indonesia",
      "from": "Indonesi",
      "to": "Tokyo",
      "time": {
            "depature": "00:00",
            "arrived": "04:00",
            "transit": "1",
          },
       "price": {
            "idclass": 3,
            "class": "Economy",
            "adult": 1200000,
            "child": 800000,
          },
       "date": "Monday, 20 july 20",
       "chairsAmount": 108,
       "gate": 221,
       "terminal": "A",
    }
  ]
```

### standar request booking ticket
```bash
{
  "title": "Mr.",
  "name": "Budi",
  "nationallity": "Indonesia",
  "userId": 1,
  "idTicket": "AB-221",
  "Price": 3000000,
  "statusPay": false,
}
  
```

### standar response destination
```bash
[
  {
    "id": 1,
    "city": "Jakarta",
    "country": "Indonesia",
    "image": "image"
   }
]
```

### standar request booking ticket
```bash
[
  {
    "idSchedule": "A-212",
    "namePerson": "Mike Kowalski",
    "emailPerson": "mikekowalski@gmail.com",
    "phonePerson": "+62-819876563",
    "namePassenger": "Mike Kowalsky",
    "nationality": "indonesia",
    "totalPrice": 145,
    "insurance" false,
  }
]
```
