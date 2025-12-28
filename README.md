Weather & News API (Express Backend)

Project Description

This project is a server-side REST API built with Node.js and Express. It integrates external APIs and demonstrates how to securely fetch data on the backend and expose it to the frontend.

The application provides:

Weather data for a given city using OpenWeather API

Top news headlines based on the country code using NewsAPI

All API requests are handled only on the backend. API keys are stored securely in environment variables.

How to Install Dependencies

 git clone https://github.com/Akehdo/web2-assigments/tree/master/assigment2

Open terminal in the project folder

In terminal: npm install

Create a .env file and add your API keys:

OPENWEATHER_API_KEY=your_openweather_key
NEWS_API_KEY=your_newsapi_key
BINGX_API_KEY=your-bingx-api-key
BINGX_SECRET_KEY=your-bingx-secret-key
In terminal:  node server.js

The server will run on: http://localhost:3001

API Routes

Weather API

GET /api/weather - returns current weather data for a given city.
