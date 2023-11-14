# Thuan Thien application web

A rice introduction website includes a home page, introduction page, blog page, detailed blog page, product page, detailed product page, and contact page. The website has features like order product, cart, slides

## Table of Contents

- [Installation](#installation)
- [Configuration](#configuration)
- [Scripts](#scripts)
- [Folder Structure](#folder-structure)

## Getting Started

### Prerequisites

Make sure you have the following software installed before proceeding:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Clone the repository:
```
git clone https://github.com/quyenngthmy/pharmacy_web.git
```
2. Navigate to the project directory:
```
cd source
```
3. Install dependencies:
```
npm install
```

### Scripts
List and explain the available npm scripts:

npm start: Start the development server.
npm run build: Build the project for production.
npm test: Run tests.

### Folder Structure
Explain the purpose of each important folder in your project.
```
├── /build/                  # Compiled files (not included in the repository)
├── /src/                   # Source code
│   ├── /assets/            # Static assets
│   ├── /components/        # React components
│   ├── index.scss          # Stylesheets
│   ├── index.html          # HTML template
│   ├── index.js            # Entry point
├── .babelrc                # Babel configuration
├── webpack.config.js       # Webpack configuration
└── package.json            # NPM package configuration
```
