# 🚽 Pipo App Backend

Welcome to the Pipo App Backend repository! This project is part of the Pipo App, a web application designed to help users find nearby public restrooms, leave comments, rate them, and add new locations. It is especially useful for foreign users exploring the city.

🔗 [Link to Frontend](https://github.com/gabasaura/pipo-app-frontend)
🔗 [Render Playground](https://pipo-app-frontend.onrender.com/)


## 📋 Table of Contents
- [About](#about)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Contact](#contact)

## 🧐 About

The Pipo App Backend provides RESTful API endpoints to support the functionalities of the [Pipo App Frontend](https://github.com/gabasaura/pipo-app-frontend). \
Users can interact with the backend to perform CRUD operations on restroom locations, leave comments, and rate them.

## ✨ Features

- User authentication with JWT
- CRUD operations for restrooms
- Rating and commenting system
- Integration with Docker for containerization
- PostgreSQL database for persistent storage

## 🛠️ Technologies

- **Python**
- **Flask**
- **JWT (JSON Web Tokens)**
- **Docker**
- **PostgreSQL**
- **Toastify** for notifications

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Docker

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/gabasaura/pipo-app-backend.git
    cd pipo-app-backend
    ```

2. Create and activate a virtual environment:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up Docker containers:

    ```bash
    docker-compose up
    ```

## 🔧 Environment Variables

Create a `.env` file in the root directory and add the following variables:

    FLASK_APP=app.py
    FLASK_ENV=development
    SECRET_KEY=your_secret_key
    DATABASE_URL=postgresql://user:password@localhost:5432/pipo_app

## 📦 Usage
Run the Flask application:

    flask run

## 📦 Contact
Authors: 🔗 [Nicolás Guzman](https://github.com/nguzm4n) 🔗 [Gabriela Garin](https://github.com/gabasaura)