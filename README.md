# Wallet App Backend

This is a simple backend service for a digital wallet application built with **Node.js**, **Express**, and **PostgreSQL**. It allows users to register, fund their wallet, make payments, view transactions, and buy products. It also supports currency conversion via an external API.

### Install Dependencies
- npm install

### Create a .env file in the root directory:

PORT=3000

DATABASE_URL=postgresql://username:password@host:port/database_name

CURRENCY_API_KEY=your_currencyapi_key

### Set Up the Database
- psql -d your_database_name -f schema.sql

###  Start the Server
- npm start
