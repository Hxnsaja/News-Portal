# News Website Project

This repository contains the source code for a news website that allows users to view public posts and provides admins and moderators with the ability to manage content and users.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [Frontend Setup](#frontend-setup)
  - [Backend Setup](#backend-setup)
- [Database Setup](#database-setup)
- [Running the Development Server](#running-the-development-server)
- [Running Unit Tests](#running-unit-tests)
- [Architecture Documentation](#architecture-documentation)

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- *Node.js* (version 14.x or later)
- *npm*
- *MongoDB* (for database storage)
- *Git* (for cloning the repository)


## Installation

To set up the project locally, follow these steps:

### Frontend Setup

1. *Clone the Repository:*
   ```bash
   git clone https://github.com/Hxnsaja/News-Portal.git
   cd client

2. *Frontend Setup:*<br>
Install Dependencies:
   ```bash
   npm install

3. *Environment Variables:*<br>
Create a .env file in the frontend directory with the following variable:
   ```bash
   REACT_APP_API_BASE_URL=http://localhost:5000/api

### Backend Setup

1. *Navigate to the backend directory:*
   ```bash
   cd server

2. *Install Dependecies:*
   ```bash
   npm install

3. *Environment Variables:*<br>
Create a .env file in client directory with the following variables:
   ```bash
   DB_URI=mongodb://localhost:27017/news_website_db
   JWT_SECRET=your-jwt-secret

### Database Setup

1. *Start your MongoDB Server*
   ```bash
   mongod

### Running the Development Server

1. *Start the backend Server*
   ```bash
   npm start
   http://localhost:5000

2. *Start the frontend Server*
   ```bash
   npm start
   http://localhost:5000

### Running Unit test

1. *Frontend Test*
   ```bash
   npm test

2. *Backend Test*
   ```bash
   npm test








