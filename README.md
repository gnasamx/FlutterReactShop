## :shopping: Flutter React Shop

A Nodejs shopping cart app with Flutter, React.

### :arrow_down: Install Dependencies

`npm install`

### :running: Run Server

1. Start MongoDB service - `systemctl start mongod`
1. Build app using webpack - `npm run dev:build`
1. Run server - `npm run dev`

### :high_brightness: Routes

> Authentication

**Signup** - `http:localhost:8000/api/v1/signup`

**Login** - `https:localhost:8000/api/v1/login`

> Products

**Add new products** - `http:localhost:8000/api/v1/products/create`

**Get all products** - `http:localhost:8000/api/v1/products`
