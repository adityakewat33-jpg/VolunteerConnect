# VolunteerConnect – Community Volunteering & Event Management System

A full-stack, responsive web application connecting community organizers with local volunteers to discover, organize, and manage local social service drives and volunteer events.

## 🚀 Key Features

- **Role-Based Access Control (RBAC):** Dedicated authentication flows for **Volunteers** and **Organizers** with Firebase Authentication.
- **Geolocation & Nearby Discovery:** Browser Geolocation API (`navigator.geolocation`) and Haversine distance calculations to discover nearby volunteer opportunities.
- **Organizer Dashboard & Event Creation:** Allows organizers to create, manage, and edit community initiatives with Cloudinary image uploads and Google Maps location integration.
- **Volunteer Application Workflow:** Volunteers can view event details, apply for events, and track their participation status in real-time.
- **Automated Digital QR Pass Generation:** Upon organizer approval, the system dynamically generates a unique, verifiable QR entry pass.
- **Integrated QR Scanner:** In-app webcam QR code scanner (`html5-qrcode`) allowing organizers to verify volunteer passes at event check-ins.
- **Automated Email Notifications:** Integrates EmailJS API to deliver digital passes and confirmation alerts directly to volunteers' email inboxes.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Custom Responsive Grid & Flexbox), Vanilla JavaScript (ES6+ Modules)
- **Backend as a Service:** Firebase Authentication, Cloud Firestore
- **Cloud Media Storage:** Cloudinary REST API
- **APIs & Libraries:** EmailJS, HTML5 QR Code Scanner, QR Code Generator API, HTML5 Geolocation API

## 📂 Project Structure

```text
├── login.html              # Multi-role login and registration interface
├── dashboard.html          # Volunteer dashboard with search & nearby filter
├── organizer-dashboard.html# Organizer management portal
├── organize.html           # Event creation with image upload & coordinates
├── edit-event.html         # Event editing interface
├── event-details.html      # Detailed event view with join/apply actions
├── my-events.html          # Volunteer's applied and joined events
├── requests.html           # Organizer approval dashboard with QR generator & EmailJS
├── scanner.html            # Event check-in webcam QR pass scanner
├── profile.html            # User profile management
└── style.css               # Global responsive styling
```
