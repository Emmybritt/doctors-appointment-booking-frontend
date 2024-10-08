# React + TypeScript + Vite

# Doctors Appointment Booking Frontend

This project is the frontend for the doctors appointment booking application.

## Prerequisites

- Node.js (version 18 or higher)
- npm or yarn
- firebase auth

## Setup

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Emmybritt/doctors-appointment-booking-frontend.git
   cd appointment-booking-frontend
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

   or if you are using yarn:

   ```sh
   yarn install
   ```

3. **Create a `.env` file at the root of the project and copy and paste this environment variables:**

   ```plaintext
   VITE_FIREBASE_API_KEY=your_firebase_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_sender_id
   VITE_FIREBASE_APP_ID=your_firebase_app_id
   ```

4. **Run the application:**

   ```sh
   npm run dev
   ```

   or if you are using yarn:

   ```sh
   yarn dev
   ```

   Open [http://localhost:5173](http://localhost:5173) with your browser to see the result.


## Features

### Authentication with Firebase Auth:

- Secure user authentication using Firebase.
- Login and registration functionalities.

### Calendar Implementation:

- Integrated calendar for selecting and viewing available appointment slots.

### Book Appointment:

- Functionality to book appointments with doctors.

### View Booked Appointments:

- Allows users to view their booked appointments.

### State Management with Redux:

- Used Redux for managing application state.

### API Calls with Axios:

- Utilized Axios for making API calls to the backend.

### Protected Routes:

- Implemented route protection to ensure that only authenticated users can access certain pages.


## Optimization Techniques

### Infinite Scrolling:

- Implemented infinite scrolling on the doctors list page to decrease load time and for better user experience.

### Image Optimization:

- Lazy loading of images to optimize performance and reduce initial load time.

### Search for Doctors:

- Debounced search functionality to provide efficient and responsive search experience.

- Fallback loader: As a fallback UI, I created loader for both the doctors listing and details page. I chose to use the loader as it   minimizes Cumulative Layout Effects and also increases speed perception.
