# 🎬 NetflixGPT

An AI-powered Netflix-like application built with **React**, **Redux**, **TailwindCSS**, **Firebase**, and integrated with **TMDB** & **OpenAI APIs**. This app features movie recommendations, trailer previews, and even GPT-based smart search!

---

## 🚀 Features

### 🔐 Authentication
- Login / Sign Up functionality
- Form validation with `useRef`
- Firebase authentication
- Redirect to Browse Page after login
- User profile update (display name & photo)
- Sign out functionality

### 🎥 Browse Page (After Authentication)
- Beautiful Header
- Main Movie section
  - Auto-playing trailer in background
  - Title & Description
- Movie Suggestions
  - Dynamically fetched from TMDB API
  - Movie lists rendered using reusable `MovieList` & `MovieCard` components

### 🧠 NetflixGPT (AI Search)
- GPT-powered Movie Search Bar
- Fetch GPT movie suggestions
- Reuse `MovieList` to display results
- Multi-language support

---

## 🛠️ Tech Stack

- ⚛️ **React** (with Hooks)
- 🎨 **TailwindCSS**
- 🔥 **Firebase** (Auth)
- 🌐 **TMDB API**
- 🤖 **OpenAI GPT API**
- 🧰 **Redux Toolkit** (with `userSlice`, `movieSlice`, `gptSlice`)
- 📦 Environment Variables (`.env`)
- 🧹 ESLint / Code Cleanup
- 🌍 Responsive Design

---



