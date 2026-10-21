# Hospital Website

Outpatient registration and clinic workflow web application.


## Features
- Patient registration
- Daily OP token numbers
- Today's queue dashboard
- Consultation and payment status
- Node.js REST API with SQLite database

## Run locally
1. Install Node.js 20 or newer.
2. Open a terminal in `02-Hospital-Website/backend`.
3. Run `npm install` and `npm start`.
4. Open http://127.0.0.1:3002

Database initialization runs automatically and loads fictional example records.

## Privacy and deployment
This is a **local-only standalone implementation**, not the separately hosted operational application. It contains **no real patient data**. The backend intentionally binds to localhost and does **not** implement production authentication or role-based authorization; do not expose it to the internet, host it publicly, or enter real patient information without first implementing and testing appropriate safeguards.
