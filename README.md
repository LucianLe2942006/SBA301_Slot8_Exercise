# SBA301 Slot 8 - Product REST API Design and Inspection Kit

## Scope
Practice Client-Server, HTTP, JSON, REST, Postman and DevTools.
This lab does NOT implement a real Spring Boot backend and does NOT teach Fetch/Axios in depth.

## Requirements
- Node.js 21 or equivalent course environment
- npm
- Postman
- Chrome/Edge DevTools

## Install
```bash
npm install
```

## Run mock API
```bash
npm run api
```

Base URL: http://localhost:3001

## Run JSON demo
```bash
npm run json-demo
```

## Reset data
Stop json-server first, then:
```bash
npm run reset-db
npm run api
```

## Required API tests
GET /products
GET /products/1
GET /products/999999
POST /products
PUT /products/1
PATCH /products/1
DELETE /products/4

## Evidence
See evidence/postman and evidence/devtools.
See docs/api-contract.md for the API contract.
