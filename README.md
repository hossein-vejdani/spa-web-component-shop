
[![shop!](https://i.ibb.co/DVVSGMt/shop-banner.png)](https://i.ibb.co/DVVSGMt/shop-banner.png)


# SPA Web Component Shop
This is an example project that demonstrates how to build a single-page application (SPA) using web components and the `custom-element-router` package.

Online url: https://router-shop.000webhostapp.com

Package repository: https://github.com/hossein-vejdani/custom-element-router



## Technologies Used

* [Custom Element Router](https://github.com/hossein-vejdani/custom-element-router)
* [Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
* [Vite](https://vitejs.dev/)

## Usage

This project demonstrates how to use the [Custom Element Router](https://github.com/hossein-vejdani/custom-element-router) to build a single-page application with web components. The router is configured in the `src/router` folder, and the different pages of the shop are defined as web components in the `src/pages` folder.

The shop uses the `Fake Store API` to fetch products and display them in the different pages. The repository for fetching data is defined in the `src/repository` folder.

## Getting started

To get started with this example project, follow these steps:

### Clone this repository to your local machine
```bash
git clone https://github.com/hossein-vejdani/spa-web-component-shop
```
### Install the dependencies by running 
```bash
cd spa-web-component-shop
npm install
```

### Start the development server by running
```bash 
npm run dev
```
Then open your web browser and navigate to http://localhost:5173. Any changes you make to the source code will be automatically reloaded in the browser.

### Build the project:
```bash
npm run build
```

## Project Structure

The project is organized as follows:

* src/pages: This folder contains web components for the different pages of the shop. Each component corresponds to a route defined in the router configuration.
* src/router: This folder contains a TypeScript file that configures the Router package. The router is responsible for mapping URLs to web components.
* src/components: This folder contains shared web components that are used across different pages of the shop.
* src/repository: This folder contains a TypeScript file that defines a repository for fetching data from the Fake Store API. This repository is used by the different pages of the shop to display products.

