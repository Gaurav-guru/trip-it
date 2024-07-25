# Tripit ✈️

## Overview
Tripit is a Travel Itinerary application built using React and Spring Boot. It allows users to plan and manage their travel itineraries efficiently by fetching destination data from a custom-built API developed with Spring Boot.

## Features
- User authentication (Login/Register)
- Dynamic travel destination fetching from a custom API
- User-friendly UI with responsive design

## Tech Stack
- **Frontend**: React, Tailwind CSS
- **Backend**: Spring Boot, Java
- **Database**: My-sql
- **API**: Custom-built API with Spring Boot

## Installation

### Prerequisites
- Node.js
- Java JDK
- Maven
- MySQL

### Frontend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Gaurav-guru/trip-it.git
   cd trip-it/frontend
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the `frontend` directory and add your environment variables:
   ```bash
   REACT_APP_BASE_URL=http://localhost:8080
   ```

4. Start the development server:
   ```bash
   npm start
   ```

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd ../backend
   ```

2. Update the `application.properties` file with your database configurations.

3. Build the project using Maven:
   ```bash
   mvn clean install
   ```

4. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

## Usage
1. Open your browser and navigate to `http://localhost:3000` to access the frontend.
2. Register a new account or log in with existing credentials.
3. Start planning your travel itineraries by searching for destinations.

## Project Video
Watch the demonstration video of the Tripit application here:

[![Tripit Demo Video](https://github.com/Gaurav-guru/trip-it/releases/download/video/Screen.Recording.2024-07-25.145614.online-video-cutter.com.mp4)

Replace `YOUR_VIDEO_ID` with the actual ID from the YouTube video link.

## Project Structure
```
trip-it/
├── backend/                # Spring Boot backend
│   ├── src/
│   ├── pom.xml
│   └── ...
├── frontend/               # React frontend
│   ├── public/
│   ├── src/
│   ├── .env
│   ├── package.json
│   └── ...
└── README.md
```

## Contact
For any inquiries, please contact [gauravdw9096@@gmail.com].
