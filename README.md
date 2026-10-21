# Website Projects

A collection of web development projects demonstrating user interfaces, backend APIs, database design and practical workflows.

## Projects

### 01 — Market Website
Vegetable and grocery shopping application featuring product browsing, search, cart, order placement and order tracking.

[Explore Market Website source code](./01-Market-Website/)

### 02 — Hospital Website
Outpatient registration and management application with patient tokens, daily queue, consultation status and payment tracking.

[Explore Hospital Website source code](./02-Hospital-Website/)

## Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express
- **Database:** SQLite

## Structure
```text
Website-Projects/
├── 01-Market-Website/
│   ├── frontend/
│   ├── backend/
│   ├── database/
│   ├── assets/
│   └── README.md
├── 02-Hospital-Website/
│   ├── frontend/
│   ├── backend/
│   ├── database/
│   ├── assets/
│   └── README.md
├── README.md
├── .gitignore
└── SECURITY.md
```

## Run Locally

Each project includes its own README and Node.js backend. Open its `backend` directory, run `npm install` and `npm start`, then visit the localhost address shown in its README.

The standalone source implementations and their fictional seed records are separate from any privately hosted operational application. The Hospital Website backend is **local-use only** until authentication, role authorization and privacy safeguards have been implemented and tested. Do not process real patient data with it.

See [SECURITY.md](./SECURITY.md).
