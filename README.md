# Tienda Virtual

A simple virtual store built with React where users can browse a list of products, add them to a shopping cart, and remove them.

## 🔗 Live Demo

[https://DENISGUERRA777.github.io/inicio-react](https://DENISGUERRA777.github.io/inicio-react)

## 📋 Description

Tienda Virtual is a front-end web application that simulates an online store. It displays a catalog of tech-themed shirts and lets users manage their shopping cart in real time using React's state management.

**Features:**
- Browse a product catalog
- Add products to the shopping cart
- Remove products from the shopping cart
- Dynamic cart that updates instantly

## 🛠️ Technologies

- [React 18](https://reactjs.org/)
- [Create React App](https://github.com/facebook/create-react-app)
- JavaScript (ES6+)
- CSS
- [GitHub Pages](https://pages.github.com/) (deployment)

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) and npm installed

### Installation

```bash
# Clone the repository
git clone https://github.com/DENISGUERRA777/inicio-react.git
cd inicio-react

# Install dependencies
npm install
```

### Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode at [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production into the `build` folder |
| `npm run deploy` | Deploys the app to GitHub Pages |

## 📁 Project Structure

```
src/
├── App.js            # Root component with state management
├── index.js          # Entry point
└── componets/
    ├── header.js     # Page header
    ├── Producto.js   # Individual product card (buy / remove)
    ├── Carrito.js    # Shopping cart
    ├── Footer.js     # Page footer
    └── Carrito.css   # Cart styles
```
