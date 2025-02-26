Hotel Booking App (Frontend Only)

This is a frontend project for a hotel booking app, built using React and Vite. The backend is currently in progress and will be integrated soon.

1. Project Workflow

Browse available hotels

View hotel details and amenities

Search for hotels by location, price, or rating

Select check-in and check-out dates

Make a booking request (frontend only, no backend integration yet)

Register/Login (feature planned for backend integration)

2. Define Core Features & User Stories

User Stories

As a guest user, I want to browse available hotels to find a suitable stay.

As a guest user, I want to filter hotels by location, price, or rating.

As a guest user, I want to view hotel details, including images, amenities, and pricing.

As a guest user, I want to select check-in and check-out dates.

As a guest user, I want to make a booking request (pending backend integration).

As a user, I want to create an account so that I can save my bookings (planned feature).

As a user, I want to log in and manage my bookings (planned feature).

3. Wireframe Planning

Before coding, wireframes were designed to visualize the layout and user experience.

Main Pages & UI Elements:

Homepage – List of featured hotels

Search Page – Filters for hotels (location, price, rating, etc.)

Hotel Details Page – Displays hotel description, amenities, images, and booking form

Booking Page – Allows users to enter their details for booking (frontend only)

Login & Signup Pages (Planned for backend integration)

4. Frontend Structure (React)

Components:

Component

Purpose

Navbar.jsx

Displays navigation links (Home, Search, Login)

Footer.jsx

Displays site info, social links, copyright

HotelCard.jsx

Displays an individual hotel’s summary

SearchBar.jsx

Allows users to search for hotels

HotelDetails.jsx

Displays a single hotel’s details

BookingForm.jsx

Captures booking details (frontend only)

Pages:

Page

Purpose

HomePage.jsx

Landing page with featured hotels

SearchPage.jsx

Filters and displays hotel search results

HotelPage.jsx

Displays details for a selected hotel

BookingPage.jsx

Allows users to request a booking

Login.jsx (Planned)

User authentication page

Signup.jsx (Planned)

User registration page

5. State Management (Planned)

State will be managed using Context API (or Redux if needed) once backend is integrated.

State

Managed by

Hotels

hotelsReducer.js

Bookings

bookingsReducer.js (Planned)

Users

usersReducer.js (Planned)

6. Step-by-Step Implementation Plan

✅ Completed:

Setup React with Vite

Built homepage with hotel listings

Implemented hotel search and filtering

Created hotel details page with booking form

🔧 In Progress:

Responsive UI improvements

Integrating a date picker for check-in/out selection

🚀 Next Steps (Backend Integration):

User authentication (Register/Login)

Save and retrieve bookings from the database

Payment gateway integration

7. How to Run Locally

1️⃣ Clone the repository:

 git clone https://github.com/WEBROBOCOP/hotel-booking-app.git
 cd hotel-booking-app

2️⃣ Install dependencies:

npm install

3️⃣ Start the development server:

npm run dev

8. Future Enhancements

Add a favorites feature

Implement Google Maps for hotel locations

Multi-language support

9. Contributors

David Etim (@WEBROBOCOP) - Frontend Developer

Backend will be added soon! Stay tuned. 🚀

