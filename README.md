# Smart India Hackathon Workshop
# Date: 31.04.2026
## Register Number: 212224040286
## Name: Samritha R
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

# Idea

**RailNav AI – Smart Railway Station Navigation System**

RailNav AI is an intelligent navigation platform designed to help passengers easily locate facilities and destinations inside railway stations. The system combines **3D indoor maps, AI-powered route guidance, voice assistance, QR-based location tracking, and accessibility features** to provide seamless navigation for all passengers, including senior citizens and differently-abled travelers.

The solution can be accessed through:

* Mobile Application (Android/iOS)
* Railway Digital Kiosks
* Railway Website Integration
* Smart QR Navigation Points inside stations

---

# Proposed Solution / Architecture Diagram

### Key Features

### 1. Interactive 3D Indoor Maps

* Detailed station layout visualization.
* Zoom, rotate, and floor navigation.
* Highlight important facilities.

### 2. Real-Time Route Guidance

* Find shortest path to:

  * Platforms
  * Ticket counters
  * Waiting halls
  * Food courts
  * Restrooms
  * Exit gates
  * Parking areas

### 3. QR-Based Location Detection

* QR codes placed at strategic points.
* User scans QR to identify current location.
* Navigation starts instantly.

### 4. Voice Navigation

* Multilingual support.
* Turn-by-turn voice guidance.
* Special support for visually impaired passengers.

### 5. Accessibility Mode

* Wheelchair-friendly route suggestions.
* Elevator and ramp guidance.
* Accessible restroom locations.

### 6. AI Chat Assistant

* Ask questions naturally:

  * "Where is Platform 5?"
  * "Nearest restroom?"
  * "How do I reach the exit gate?"

### 7. Emergency Assistance

* Emergency exit navigation.
* Medical room guidance.
* Security help desk location.

---
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/8d08195d-15bb-4ca7-86db-3a0726676bda" />



# Use Cases

### UC1: Platform Navigation

Passenger enters station and searches for Platform 8. The app provides the shortest route with walking time.

### UC2: Finding Facilities

Passenger searches for:

* Restroom
* Food Court
* Waiting Hall
* Ticket Counter

The nearest facility is displayed with directions.

### UC3: Assistance for Visually Impaired Users

Voice commands guide users through the station using audio instructions.

### UC4: Wheelchair Accessibility

System generates routes containing:

* Elevators
* Ramps
* Accessible pathways

### UC5: Emergency Evacuation

During emergencies, passengers receive safe exit routes based on current location.

### UC6: Digital Kiosk Navigation

Passengers without smartphones can use touch-screen kiosks to find locations.

 <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/b4ddf609-bbdd-45f9-89aa-ffbeaeccef8f" />



# Technology Stack

## Frontend

* React.js
* React Native / Flutter
* HTML5
* CSS3
* JavaScript

## Backend

* Node.js
* Express.js

## Database

* PostgreSQL
* MongoDB

## Mapping & Navigation

* Three.js (3D Maps)
* Mapbox Indoor Maps
* OpenStreetMap

## AI & Voice

* Python
* TensorFlow
* Speech Recognition APIs
* Text-to-Speech APIs

## Cloud & Deployment

* AWS
* Firebase
* Docker

---

# Dependencies

### Frontend

```bash
npm install react
npm install react-router-dom
npm install three
npm install mapbox-gl
npm install axios
```

### Backend

```bash
npm install express
npm install mongoose
npm install cors
npm install dotenv
npm install socket.io
```

### AI Services

```bash
pip install tensorflow
pip install speechrecognition
pip install pyttsx3
pip install nltk
```

### Database

```bash
MongoDB Atlas
PostgreSQL
```

---

# Expected Outcome

* Reduced passenger confusion inside stations.
* Faster access to platforms and facilities.
* Improved accessibility for differently-abled passengers.
* Better crowd management and passenger flow.
* Enhanced railway travel experience through smart digital navigation.

**Project Name:** *RailNav AI – Smart Indoor Navigation System for Railway Stations*
**Organization:** Ministry of Railways
**Theme:** Smart Transportation & Accessibility
**Innovation Level:** AI + Indoor Navigation + Accessibility + Real-Time Guidance.

