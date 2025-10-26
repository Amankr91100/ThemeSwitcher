🌗 ThemeSwitcher Project (Dark / Light Mode)

A **React Theme Switcher** project demonstrating the **Context API** to manage global state for theme (light/dark mode) across the entire application.  
Built with **React**, **Tailwind CSS**, and **Vite**.

🚀 Live Demo  
 [View Live Project Here](https://theme-switcher-ten-gray.vercel.app/)  

📘 About the Project

This project showcases a **dark/light theme toggle** that works globally in the app.  
It leverages **React Context API** to avoid prop drilling, making it easy for any component to read or update the theme.

🧠 How It Works: Context API Flow

The **Context API** allows you to create a “global box” to store data that can be accessed anywhere in your component tree.

1️⃣ Create Context

import { createContext } from "react";

export const ThemeContext = createContext({
    themeMode: "light",
    darkTheme: () => {},
    lightTheme: () => {},
});


⚡ Features

Toggle Dark / Light mode globally

Context API used for state management

Tailwind CSS dark: classes to automatically style components

Fully responsive card component showcasing theme changes

🛠 Technologies Used

⚛️ React (with Hooks)

🌈 Tailwind CSS (v4 latest)

🧩 React Context API

⚡ Vite for fast development

📂 Project Structure
src/
├─ components/
│  ├─ Card.jsx
│  └─ ThemeBtn.jsx
├─ contexts/
│  └─ theme.js
├─ App.jsx
└─ index.css

🎯 Key Learnings

Using React Context API for global state

Dynamically applying Tailwind dark: classes

Avoiding prop drilling in medium/large React apps

Creating reusable components (Card, ThemeBtn)

📷 Preview
<img width="764" height="575" alt="Screenshot 2025-10-26 225035" src="https://github.com/user-attachments/assets/cd2ab916-d71c-48e3-b7f1-0789a0792d9c" />


