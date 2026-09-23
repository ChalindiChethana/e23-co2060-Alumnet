# Alumnet Developer Guide

This document outlines the technical architecture, local development setup and repository structure for the Alumnet platform.

## 1. System Architecture 
* **Frontend:** React application located in the `code/client` directory.
* **Backend:** Node.js and Express REST API.
* **Deployment:** Frontend hosted on Vercel; backend hosted on Railway. 

## 2. Local Environment Setup 
Configure your local environment to run the application and test changes. 

### 2.1 Clone and Install
* Clone the repository: `git clone https://github.com/cepdnaclk/e23-co2060-Alumnet`
* Navigate to the frontend: `cd e23-co2060-Alumnet/code/client`
* Install frontend dependencies: `npm install`
* Repeat the dependency installation process for the backend directory as well. 

## 3. Running the application
* **Backend Development Server:** Navigate to the backend directory and start the node server. (`node server.js`)
* **Frontend Development Server:** Navigate to `code/client` and start the React server. (`npm run dev`)

## 4. Repository Structure
* `code/client/`: Contains all frontend soruce code and cofiguration files.
* `code/client/src/App.jsx`: The root React component managing the application's primary view state. 
* `code/client/src/api.jsx`: Centralized file for handling outgoing HTTP requests for the backend API.
* `code/client/package.json`: Defines frontend dependencies and run scripts.