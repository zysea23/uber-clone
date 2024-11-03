
<div align="center">
  <br />
    <img src="https://i.ibb.co/Bf04Hpd/Readme-thumbnail-from-JS-Mastery.png" alt="Project Banner">
  <br />

  <h3 align="center">Full Stack Uber Clone</h3>
  
  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/-PostgreSQL-black?style=for-the-badge&logoColor=white&logo=postgresql&color=4169E1" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="Expo" />
    <img src="https://img.shields.io/badge/-Stripe-black?style=for-the-badge&logoColor=white&logo=stripe&color=008CDD" alt="Stripe" />
  </div>
</div>

---

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🚀 [Quick Start](#quick-start)

---

## 🤖 Introduction <a name="introduction"></a>

The **Full Stack Uber Clone** app showcases the process of building a complete mobile application using modern development tools. Built with **React Native** for the front-end, **Stripe** for secure payments, **serverless PostgreSQL** for the database, and **Google Maps** for navigation, this project illustrates essential skills for full-stack mobile development. The app’s responsive design works seamlessly across iOS and Android platforms.

---

## ⚙️ Tech Stack <a name="tech-stack"></a>

- **React Native** - Front-end framework for building mobile apps
- **Expo** - Development platform for React Native
- **Stripe** - Payment processing
- **PostgreSQL** - Database management
- **Google Maps** - Map rendering and geolocation
- **Zustand** - Lightweight state management
- **Clerk** - Authentication
- **Tailwind CSS** - Styling framework

---

## 🔋 Features <a name="features"></a>

- **Onboarding Flow**: Smooth and user-friendly onboarding experience.
- **Email & Password Authentication with Verification**: Secure login with verification.
- **OAuth with Google**: Quick login through Google.
- **User Roles & Access Control**: Granular authorization for different user roles.
- **Real-time Location with Google Maps**: Track live location with map markers.
- **Ride History**: View past rides with ease.
- **Google Places Autocomplete**: Quick place search with suggestions.
- **Ride Search**: Enter start and end locations to find available rides.
- **Map-based Car Selection**: Choose cars near you directly from the map.
- **Detailed Ride Information**: View ride details, including fare and estimated time.
- **Stripe Payment Integration**: Secure payments with multiple options.
- **Ride Creation Post-Payment**: Confirm ride after successful payment.
- **User Profile Management**: Manage account details within the app.
- **Fully Responsive on iOS and Android**: Optimized for both platforms.
- **Architecture & Code Reusability**: Clean and reusable code for scalability.

---

## 🚀 Quick Start <a name="quick-start"></a>

### Step 1: Clone the Repository

```bash
git clone https://github.com/zysea23/Uber-Clone.git
cd Uber-Clone
```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Set Up Environment Variables

Create a `.env` file in the project root with the following keys:

```env
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=
EXPO_PUBLIC_PLACES_API_KEY=
EXPO_PUBLIC_DIRECTIONS_API_KEY=
DATABASE_URL=
EXPO_PUBLIC_SERVER_URL=https://uber.dev/
EXPO_PUBLIC_GEOAPIFY_API_KEY=
EXPO_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
```

Replace the placeholder values with your actual keys from [Clerk](https://clerk.com/), [Stripe](https://stripe.com/in), [NeonDB](https://neon.tech/), [Google Maps](https://console.cloud.google.com/), and [Geoapify](https://www.geoapify.com/).

### Step 4: Start the Application

Run the app using Expo:

```bash
npx expo start
```

You're all set! The app should now be running locally, showcasing all its core functionalities.
