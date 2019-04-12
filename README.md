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

**Login** - `http:localhost:8000/api/v1/login`

> Products

**Add new products** - `http:localhost:8000/api/v1/products/create`

**Get all products** - `http:localhost:8000/api/v1/products`

**Fetch single product** - `http:localhost:8000/api/v1/products/:id`

**Update single product** - `http:localhost:8000/api/v1/products/update/:id`

**Delete single product** - `http:localhost:8000/api/v1/products/delete/:id`

> Cart

**Add to cart** - `http:localhost:8000/api/v1/cart/create/:id`

**Update cart product** - `http:localhost:8000/api/v1/cart/update/:id`

**Fetch all cart products** - `http:localhost:8000/api/v1/cart`

