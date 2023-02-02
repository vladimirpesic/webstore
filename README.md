# Webstore

eCommerce starter built on [Node.js](https://nodejs.org/), [Express](https://expressjs.com/), [EJS](https://ejs.co/) and [MongoDB](https://www.mongodb.com/), with [Stripe](https://stripe.com/) integration.

Make sure to populate following files with valid credentials:

`package.json`
```bash
"start": "NODE_ENV=production MONGO_USER= MONGO_PASSWORD= MONGO_DEFAULT_DATABASE= STRIPE_KEY= node app.js"
```

`nodemon.json` for local development
```bash
{
    "env": {
        "MONGO_USER": "",
        "MONGO_PASSWORD": "",
        "MONGO_DEFAULT_DATABASE": "",
        "STRIPE_KEY": "",
        "SENDGRID_KEY": ""
    }
}
```

`checkout.ejs` with Stripe public key
```bash
data-key=""
```
