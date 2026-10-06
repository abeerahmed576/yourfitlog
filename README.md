# 🏋️‍♂️ Your FitLog

A modern, responsive workout library and daily workout planning application built with **Next.js**. FitLog allows users to explore workouts, view detailed exercise information, build a daily workout plan, save exercises for later, and track completed workouts.

## 🔗 Live Project

**Live Demo:** [Add your deployed project URL here]

**Repository:** [Add your GitHub repository URL here]

## 📖 About The Project

**YourFitLog** is a dark-themed workout library designed to make workout planning simple and focused.

Users can browse a collection of exercises, inspect detailed workout information, add exercises to their daily plan, save workouts for later, and mark planned workouts as completed.

The application is fully responsive and designed to provide a consistent experience across **mobile, tablet, and desktop devices**.

## ✨ Key Features

### 🏋️ Workout Library

* Fetches workout data dynamically from the FitLog API.
* Displays workouts in a responsive card-based grid.
* Sort workouts by:

  * Duration
  * Calories
  * Rating
* Each workout card displays its image, category, equipment, duration, calories, and rating.

### 🔎 Workout Details

* Dedicated detail page for every workout.
* Displays workout image, description, categories, specifications, and instructions.
* Users can add a workout to **Today's Plan**.
* Users can save workouts for later.
* Toast notifications provide feedback after user actions.

### 📋 Today's Plan

* Build a personalized daily workout plan.
* Displays live statistics for:

  * Exercises
  * Total minutes
  * Total calories
* Maximum of five workouts can be added to today's plan.
* Mark workouts as completed.
* Remove workouts from the plan.
* View details of any planned workout.

### 💾 Saved Workouts

* Save workouts for later.
* View all saved workouts from the **My Plan** page.
* Remove saved workouts when no longer needed.

### 📱 Fully Responsive

* Optimized for:

  * 📱 Mobile
  * 📲 Tablet
  * 🖥️ Desktop

### 🔔 User Feedback

* Toast notifications for important actions, including:

  * Adding a workout to today's plan
  * Saving a workout
  * Marking a workout as done
  * Removing a workout
  * Duplicate/addition attempts

### ⚡ Loading & Error States

* Loading animation while workout data is being fetched.
* Loading state on the My Plan page.
* Custom 404 page for invalid routes.
* Error handling for failed data requests.

## 🛠️ Technologies Used

| Technology             | Purpose                                     |
| ---------------------- | ------------------------------------------- |
| **Next.js**            | Building the application and UI             |
| **React**              | Building reusable components                |
| **TypeScript**         | Type-safe development                       |
| **Next.js App Router** | Application routing and page navigation     |
| **Tailwind CSS**       | Utility-first styling and responsive design |
| **DaisyUI**            | UI components built on top of Tailwind CSS  |
| **Font Awesome**       | Icons throughout the application            |
| **React Toastify**     | Toast notifications and user feedback       |
| **REST API**           | Fetching workout data                       |

## 📂 Main Application Routes

| Route          | Description                        |
| -------------- | ---------------------------------- |
| `/`            | Workout library / Home page        |
| `/workout/:id` | Workout details page               |
| `/my-plan`     | Today's Plan and Saved workouts    |
| `/*`           | Custom 404 page for invalid routes |

---

## 🎯 Application Flow

```text
Home
 │
 ├── Browse Workouts
 │       │
 │       └── Workout Details
 │              │
 │              ├── Add to Today's Plan
 │              │
 │              └── Save for Later
 │
 └── My Plan
        │
        ├── Today's Plan
        │      ├── View Details
        │      ├── Mark as Done
        │      └── Remove
        │
        └── Saved
               └── View Details
```

## 🚀 Getting Started

### Prerequisites

Make sure you have **Node.js** and **npm** installed on your system.

### Clone the repository

```bash
git clone https://github.com/abeerahmed576/yourfitlog

cd yourfitlog

npm install

npm run dev
```

Open the application in your browser:

```text
http://localhost:3000
```

---

## 🏗️ Build for Production

To create a production build:

```bash
npm run build
```

To start the production server:

```bash
npm start
```

## 📄 License

This project was created for educational and assignment purposes.
