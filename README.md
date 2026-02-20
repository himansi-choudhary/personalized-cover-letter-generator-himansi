# 🎨 CoverLetter AI Pro – Frontend Module

This repository contains the complete frontend implementation of the **CoverLetter AI Pro** project.
It provides a modern, responsive, and interactive user interface for generating AI-powered cover letters.

---

## 📌 Overview

The frontend is built using:

* **HTML5**
* **Tailwind CSS**
* **Custom CSS (Glassmorphism + Gradient UI)**
* **Vanilla JavaScript**
* **Font Awesome Icons**
* **Google Fonts (Inter)**

It connects with backend APIs to generate personalized cover letters based on user input.

---

## 📁 Folder Structure

```
templates/
├── home.html      # Landing page
└── index.html     # Cover letter generator interface
```

---

# 🏠 home.html – Landing Page

A visually advanced animated landing page designed to create strong first impressions.

### Key Features:

* Animated gradient background
* Glassmorphism UI design
* Floating orb animations
* Typing text animation
* Feature showcase section
* Testimonials section
* Statistics counter animation
* Smooth scroll navigation
* CTA section
* Contact modal popup
* Responsive layout

### UI Highlights:

* Hero section with animated headline
* Dynamic counters using Intersection Observer
* Hover animations and glow effects
* Fully responsive across devices

---

# 📝 index.html – Cover Letter Generator Interface

This page handles the entire user interaction flow for generating cover letters.

---

## 🔹 Generation Modes (3 Tabs)

### 1️⃣ Skills-Based Generation

* Enter name & skills
* Optional Job Description (Upload or Paste)
* Years of Experience (auto-categorized)
* Target Role selection
* Optional Company Name

---

### 2️⃣ Resume-Based Generation

* Upload Resume (PDF, DOCX, TXT)
* OR Paste Resume Text
* Paste Job Description
* Experience auto classification
* Role selection
* Company name field

---

### 3️⃣ Manual Input Mode

* Paste Job Description
* Enter personal details manually
* Experience auto classification
* Role selection
* Company name

---

## 🔧 Functional Features

* Drag & Drop File Upload
* Multi-format support (PDF, DOCX, TXT)
* Dynamic tab switching
* Loading spinner state
* Error message display
* Copy to clipboard functionality
* Download generated cover letter
* Clean result display with formatting
* Auto experience level categorization

---

## 🎨 Design System

* Gradient theme with dark UI
* Glassmorphism components
* Smooth hover animations
* Custom styled select dropdown
* Custom file upload UI
* Animated background

---

## 📱 Responsiveness

* Fully responsive layout
* Optimized for desktop and mobile
* Flexible grid system using Tailwind

---

## 🔗 Backend Integration

The frontend connects to backend APIs via:

```
/static/js/index.js
```

It sends user input to the backend and displays:

* Generated Cover Letter
* Status messages
* Errors (if any)

---

## 🧠 UX Considerations Implemented

* Clear tab separation
* Input validation
* Optional vs Required field clarity
* Visual loading feedback
* Clean typography
* User-friendly upload interactions
* Minimal clutter

---

# 👩‍💻 Contribution

**Frontend Development:**
Himansi

Responsibilities:

* Complete UI/UX design
* Responsive layout implementation
* Animation implementation
* Tab switching logic
* File upload UI
* Loading & error state handling
* Result display system
* Copy & download functionality
* Integration with backend endpoints

---

## 🚀 How to Run (With Backend)

1. Clone main project repository
2. Install backend dependencies
3. Start backend server
4. Open:

```
http://localhost:5000/
```

---

## 📌 Notes

This repository contains only the **frontend module** of the project.
