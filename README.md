# Eco Drive Score

## Project Description

**Eco Drive Score** is a mobile application that analyzes driving behavior using GPS speed data. It detects acceleration, braking, and route efficiency to calculate a driving score and recommend energy-efficient driving habits and routes to reduce fuel waste.

---

## Objectives

- Analyze driving behavior using GPS data  
- Detect acceleration and braking patterns  
- Calculate a driving efficiency score  
- Evaluate route efficiency based on traffic smoothness and stability  
- Promote fuel-efficient driving habits  

---

## Features

### Driving Behavior Analysis
- GPS-based speed tracking  
- Detection of hard acceleration  
- Detection of hard braking  
- Smooth driving evaluation  

### Driving Score System
- Initial score: **100**
- Score decreases with aggressive driving  
- Score increases with smooth driving  
- Final classification:
  - **Excellent**
  - **Good**
  - **Moderate**
  - **Inefficient**

### Eco Route Analysis
- Compares multiple routes  
- Evaluates distance and traffic smoothness  
- Counts number of stops and speed changes  
- Recommends most efficient route  

### Driving Mode Indicator
- **Eco Mode** (efficient driving)  
- **Normal Mode**  
- **Inefficient Mode**

---

## Platform

- **Mobile Application (Android)**
- Built with **Flutter (Dart)**

---

## Methodology

The system collects GPS speed data at regular intervals and calculates speed changes over time. Driving behavior is classified using threshold-based logic for acceleration and braking. A scoring system evaluates overall driving efficiency.

Route efficiency is determined by analyzing stability, stop frequency, and variation in speed along the route.

---

## Technology Stack

- Flutter (Dart)
- Google Maps API
- GPS Location Services
- Firebase (optional)
- Data visualization libraries

---

## Future Development

- Integration of accelerometer and gyroscope
- Machine learning-based driving classification
- Real-time traffic integration
- Fuel consumption estimation model
- Gamification system (leaderboards, challenges)

---

## License

This project is licensed under the MIT License.
