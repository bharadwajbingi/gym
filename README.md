# 100-Day Workout & Boxing Plan Visualizer

![Workout Plan](https://bharadwajbingi.github.io/gym/favicon.ico)

## Live Demo
Try the project live here:  
🔗 [https://bharadwajbingi.github.io/gym/](https://bharadwajbingi.github.io/gym/)

---

## Overview

This is a **personal fitness web application** designed to track and visualize a comprehensive 100-day workout and boxing training plan. The app helps me stay consistent and motivated by combining detailed daily workouts with progress tracking and an interactive UI — all packed into a single-page app hosted on GitHub Pages.

The project demonstrates skills in **JavaScript, HTML5 Canvas, localStorage management, responsive UI design, CSS animations, and Progressive Web App (PWA) basics**.

---

## Key Features

- **100-Day Workout Calendar:**  
  Displays daily workouts including push-pull-legs (PPL) cycles and boxing sessions with detailed exercises for each day.

- **Rest Day Marking:**  
  Sundays are designated as rest days with distinct styling.

- **Progress Tracking:**  
  Interactive progress bar updates dynamically as you mark days completed or pending.

- **Collapsible Workout Details:**  
  Each day’s workout details can be expanded or collapsed for a clean view.

- **State Persistence:**  
  All progress and UI state (completed days and expanded/collapsed workout details) are saved in browser localStorage — so your data is retained between sessions.

- **Canvas Visualization:**  
  A colorful, dynamic bar chart representing daily activity is rendered on an HTML5 canvas element.

- **PPL Workout Templates:**  
  Push, Pull, and Legs workout routines with two alternating variations each, displayed automatically according to the day.

- **Mark Completed / Pending Buttons:**  
  Easily toggle workout completion status for each day.

- **Responsive & Accessible Design:**  
  Clean, modern UI with semantic HTML and accessible controls.

- **Progressive Web App (PWA) Ready:**  
  Includes manifest and service worker registration boilerplate for offline support and installability.

---

## Technologies Used

- **HTML5** and **CSS3** (including Google Fonts - Lato)  
- **Vanilla JavaScript** for DOM manipulation and logic  
- **HTML5 Canvas API** for drawing activity visualization  
- **LocalStorage API** for persisting user data  
- **Service Worker API** for PWA capabilities  
- Hosted on **GitHub Pages**

---

## How It Works

1. The app initializes with a 100-day calendar starting from June 5, 2025.  
2. Each day is automatically assigned a workout routine or rest day based on weekday and a rotating PPL cycle.  
3. Users can expand/collapse workout details and mark each day as completed or pending.  
4. The progress bar updates to reflect the percentage of completed workouts.  
5. State is saved locally, so your progress is retained on page reload or browser restart.  
6. The canvas bar chart provides a visual daily activity summary.

---

## Project Structure

- **index.html:** Main HTML page with markup and embedded CSS & JS.  
- **manifest.json:** PWA manifest file (linked in `<head>`) to enable installability.  
- **service-worker.js:** Service worker registration script for offline support.  
- **Templates:** Hidden `<template>` tags inside HTML hold workout routines for reusability.

---

## Future Improvements

- Add user authentication and cloud sync for cross-device progress tracking.  
- Enable workout customization and notes per day.  
- Add notifications and reminders for workout days.  
- Improve mobile responsiveness and add animations.  
- Integrate with fitness trackers or health apps via APIs.

---

## How to Run Locally

1. Clone the repository:  
   ```bash
   git clone https://github.com/bharadwajbingi/gym.git
