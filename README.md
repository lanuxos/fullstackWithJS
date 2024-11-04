# fullstackWithJS
# Fullstack Web Development with JavaScript

# Overview
# Pre-test
# Course introduction
# Prerequisities
- JavaScript syntax
- Primitive types
- Control flow
- Function
- HTML
- CSS
- tailwindcss
# JavaScript for Full-Stack
## JavaScript for Full-Stack
- client-side rendering
- server-side rendering
## Frontend with Vue JS and Nuxt
## Getting started pages with Nuxt
## Components: Button and Link
## Icon component
## Component
## Footer component
## Homepage
## Skill list component
## Experience item component
## Experience list component
## Portfolio list component
## Login page
## Login form component
## Input component
## Error message component
## State management
## Pinia state management
## Auth store
## Skill form component
## Editable component
## Profile store (skills)
## Experience form component
## Profile store (experience)
## Profile store (portfolio)
## Portfolio ViewPage
## Frontend summary
# Setup tools and environments 1
## Setup tools and environments 1
## Layers
## Auth (API)
## Profile (API)
## Portfolios (API)
## Auth (Service)
## Profile (Service)
## Portfolios (Service)
## Auth (Repository)
## Profile (Repository)
## Portfolios (Repository)
## Backend summary
# Setup tools and environments 2
## Setup tools and environments 2
## Integration and deployment
# Setup Vue JS for Frontend
## Setup Vue JS for Frontend
```bash
npm create vue@latest

frontend
typescript no
jsx no
vue router no
pinia yes
vitest yes
an end-to-end crpress
eslint yes
prettier yes

cd frontend
npm install
npm run format
npm run dev
```
# Setup Node JS + Express JS for backend
## Setup Node JS + Express JS for backend
```bash
mkdir backend
cd backend
npm init
npm install express
```
- index.js
```javascript
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
    res.send('Hello World')
})

app.listen(port, () => {
    console.log(`app listening on port ${port}`)
})
```
# Website overview
## Website overview
# Design Logical Diagram
## Design Logical Diagram
# Design Database Schema
## Design Database Schema
# Design API Specification
## Design API Specification
# Summary
## Summary
## Post-test
## Feedback