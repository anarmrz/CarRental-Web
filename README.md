# CarRental-Web 🚗

A comprehensive full-stack web application for vehicle rentals, featuring secure user authentication, dynamic inventory management, and personalized user dashboards. 

> **Note:** This is a collaborative academic project developed alongside university peers. It has been migrated to this repository to showcase the frontend architecture, the backend REST API, and the relational database integration.

## 🚀 Key Features

* **Secure Authentication Flow:** End-to-end user registration, login, and email verification (`VerifyEmailPage.jsx`) backed by custom backend middleware (`auth.middleware.js`).
* **Dynamic Vehicle Catalog:** Interactive UI displaying available vehicles using modular React components (`CarCard.jsx`), allowing users to browse and select options effortlessly.
* **Complete Rental Lifecycle:** RESTful controllers handling the business logic for creating reservations (`rentas.controller.js`) and processing transactions (`pagos.controller.js`).
* **Personalized Dashboards:** Dedicated views for users to manage their account details (`ProfilePage.jsx`) and track their active or past reservations (`MyRentalsPage.jsx`).
* **Decoupled Architecture:** Clean separation of concerns with an independent React client and a Node.js/Express server API.

## 🛠️ Technologies & Stack

**Frontend (Client)**
* React.js (Bootstrapped with Vite)
* Custom CSS for responsive component styling
* React Context API (`AuthContext.jsx`) for global state management

**Backend (Server)**
* Node.js & Express.js
* Modular routing (`carros.routes.js`, `usuarios.routes.js`, etc.)
* Custom Authentication & Error Handling Middlewares

**Database**
* Relational SQL Database
* Schema initialization and integrity constraints defined via `Creacion.sql`

## 🏗️ Project Structure

The repository follows a strict client-server architecture:

* `/client`: Contains the Vite+React frontend application, including all pages, reusable UI components, styling assets, and state context.
* `/server`: Contains the Express API, divided into controllers, routes, configurations (`db.js`, `mailer.js`), and middlewares.
* `Creacion.sql`: The foundational database schema ensuring data integrity across users, vehicles, and rentals.

## 🎓 Context and Credits

This repository is a consolidated migration of a full-stack web application originally developed as a collaborative academic project on my university account (`anaramirez26`). The complete implementation of the React frontend, Node.js/Express REST API, and relational database was built through teamwork as part of our university coursework.

**Developed by:**
* Ana Belén Ramírez Flores ([@anarmrz](https://github.com/anarmrz) / [@anaramirez26](https://github.com/anaramirez26))
* Julio Javier Morales Vargas ([@MVJJulio](https://github.com/MVJJulio))
* Bianca Natalia Luna Peñate ([@biiluu](https://github.com/biiluu))
* Andrés Rodolfo López Mejía ([@aloopez](https://github.com/aloopez))
