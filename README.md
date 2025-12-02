
# WeatherKings: A weather prediction game

## Description
DraftUWeather is a weather prediction game where users forecast daily conditions (temperature, wind, precipitation) and compete for accuracy.
Players earn points based on how close their predictions are to real-world data from APIs such as OpenWeather or NOAA HRRR. The system will compare user predictions to actual data and generate a score which can be posted on a global leaderboard. Additional features could be a 'Forecast of the day' or 'WildCard Weather Guess' where users guess on certain weather conditions occuring. 

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
- Maintain a leaderboard of user performance  

**Additional Features (Planned)**  
- Forecast of the Day challenge  
- Wildcard Weather Guess mode  
- Graphs or trends showing user accuracy over time  

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

## Project status
Sprint 0 – Planning Phase and Documentation setup Phase 
Architecture and specifications defined. 
No Development yet.

