
# WARNING: Scam Alert

## Important Notice for Developers

This repository is being used by scammers who pose as legitimate employers conducting technical assessments. They are asking multiple developers to complete this project under the guise of a job application process. 

If you have been asked to contribute to this repository as part of a technical assessment, please be aware that this is likely a scam. They are exploiting developers' work without any intention of hiring or compensating them.

**What to do:**
- **Do not contribute any further code to this repository.**
- **Report the scam to the relevant authorities or platforms.**
- **Warn other developers about this scheme to prevent them from falling victim to it.**

Stay vigilant and protect your work.

For more information about job scams, you can visit:
- [Federal Trade Commission - Job Scams](https://www.consumer.ftc.gov/articles/0243-job-scams)
- [Better Business Bureau - Job Scams](https://www.bbb.org/us/article/scams/15717-bbb-scam-alert-dont-fall-for-job-scams)

If you have any questions or need assistance, please feel free to contact me.

Best regards,
Emmanuel


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
   VITE_FIREBASE_API_KEY=AIzaSyA8ZNeubslYSSgu_2VeZuLWgN3mKxPQAwM
   VITE_FIREBASE_AUTH_DOMAIN=fir-auth-311de.firebaseapp.com
   VITE_FIREBASE_PROJECT_ID=fir-auth-311de
   VITE_FIREBASE_STORAGE_BUCKET=fir-auth-311de.appspot.com
   VITE_FIREBASE_MESSAGING_SENDER_ID=185349758929
   VITE_FIREBASE_APP_ID=1:185349758929:web:ecbd1eb36813dfb2544af0p
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
