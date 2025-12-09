

# WeatherKings: A weather prediction game

## Overview

WeatherKings is a full-stack weather prediction platform where users place bets on daily weather outcomes—such as maximum temperature, precipitation, and wind—and earn points or virtual balance based on accuracy.
Real-world weather data is fetched from public APIs, and the backend computes bet outcomes, updates user balances, and displays results through a web dashboard.

This project was built as a complete, containerized system including frontend, backend, and database layers.
## Project Architecture  
Our system will use **three Docker containers** to create a full-stack application.

### Components  
- **Frontend**: React Native  
  - Displays the UI for entering predictions and viewing results  
- **Backend**: Spring Boot  
  - Handles REST API logic, scoring, and data requests  
- **Database**: MySQL  
  - Stores users, predictions, scores, and weather data  

### Data Flow  
React Native (Frontend) → Spring Boot (Backend) → MySQL (Database)  
The backend will also connect to external APIs (OpenWeather, NOAA HRRR) to fetch real weather data for scoring.

## Project Specifications  

**Core Features**  
- Submit daily predictions for weather metrics  
- Fetch real data from public weather APIs  
- Calculate and display scores based on prediction accuracy   


**Technical Goals**  
- Containerized deployment using Docker Compose  
- RESTful communication between frontend and backend  
- Persistent storage of users and predictions  


## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.
Kaden
Sri
Leon
Sam
Manuel
Krishna

## License
For open source projects, say how it is licensed. At this moment - N/A

