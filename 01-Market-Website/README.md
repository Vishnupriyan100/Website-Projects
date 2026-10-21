# Market Website

Vegetable and grocery ordering website project.


## Features
- Product catalog, search and stock
- Cart and checkout
- Order tracking using order number and phone
- Local Node.js REST API
- SQLite product and order database

## Run locally
1. Install Node.js 20 or newer.
2. Open a terminal in `01-Market-Website/backend`.
3. Run `npm install` and `npm start`.
4. Open http://127.0.0.1:3001

The local database is automatically initialized using `schema.sql` and sample inventory from `seed.sql`.

## Note
This standalone implementation is separate from the separately hosted operational application and does not access its production API or database. Sample records are fictional. Production deployment requires additional security controls and testing.
