# Digital Clock App: React

Welcome to the **Digital Clock App**, a simple React-based application that displays the current time in a 12-hour format with AM/PM. The clock updates every second, providing a live, interactive experience.

You can access the deployed app here: [Digital Clock App](https://sudhasai783.github.io/Digital-Clock--React-App/)

## Features

- **Live Clock**: Displays the current time that updates every second.
- **12-Hour Format**: Shows the time in 12-hour format (e.g., 02:05:07 PM).
- **AM/PM Display**: Automatically switches between AM and PM based on the current time.
- **Zero Padding**: Ensures that single-digit hours, minutes, and seconds are padded with leading zeros (e.g., 09:05:03).
- **Minimal Design**: Simple, clean, and user-friendly design.

## Tech Stack

- **Frontend**: React
- **State Management**: React's `useState` Hook
- **Side Effects**: React's `useEffect` Hook
- **Styling**: CSS (basic styles for layout)
- **Deployment**: GitHub Pages

## Access the app

[Digital Clock App](https://sudhasai783.github.io/Digital-Clock--React-App/)

---

## How it Works

This app uses React hooks to manage the state and lifecycle of the clock component.

1. **`useState`**: Stores the current time (`new Date()`) in the state.
2. **`useEffect`**: Sets up an interval that updates the clock every second and cleans it up on component unmount.
3. **Time Formatting**: The `formatTime` function formats the current time into a 12-hour format with AM/PM.
4. **Zero Padding**: The `padZero` function adds a leading zero to numbers less than 10.
