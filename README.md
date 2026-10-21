# Website Projects

Two website projects covering local commerce and outpatient administration.

| Project | Features | Live application |
| --- | --- | --- |
| [Namma Ooru Market](./01-Namma-Ooru-Market/) | Produce catalog, shopping cart, checkout and tracking | [Visit website](https://namma-ooru-market.hatchable.site) |
| [SK Hospital OP Management](./02-SK-Hospital-OP-Management/) | OP registration, daily queue and payment workflow | [Visit website](https://sk-hospital-op.hatchable.site) |

## Technology stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express REST API
- **Database:** SQLite, SQL schema and initial records

## Repository structure
```text
Website-Projects/
├── 01-Namma-Ooru-Market/
│   ├── frontend/
│   ├── backend/
│   ├── database/
│   ├── assets/
│   └── README.md
├── 02-SK-Hospital-OP-Management/
│   ├── frontend/
│   ├── backend/
│   ├── database/
│   ├── assets/
│   └── README.md
├── README.md
├── SECURITY.md
└── .gitignore
```

## About this code

The repository contains **standalone local implementations** based on the features of two applications built on Hatchable. They are not exact exports of their deployed Hatchable source or infrastructure. Each project can be started independently on a local computer; the local SQLite database does not connect to any Hatchable production database.

Please see the individual project READMEs for setup instructions. **Do not use the hospital backend with real patient information or expose it publicly** until access controls and privacy protections have been added and tested.

See [SECURITY.md](SECURITY.md).
