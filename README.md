# Namma Mitra - AI-Powered Campus Student Assistant

## Overview
**Namma Mitra** is an intelligent, responsive web application designed specifically for university students living and studying in Bangalore. The platform acts as a digital companion to help students navigate the unique daily challenges of college life—focusing on local traffic and transit optimization, smart expense/budget tracking, and seamless academic schedule management.

The application features a modern, intuitive user interface designed to streamline a student's daily routine and maximize productivity.

## Features

### 🗺️ Smart Transit & Traffic Navigation
* **Bangalore Traffic Insights:** Helps students plan their commute by tracking local traffic patterns and suggesting optimal travel times.
* **Transit Optimization:** Assists in finding the best routes using local transport options (Metro, BMTC buses) to save time and commuting costs.

### 💰 Student Budget & Expense Manager
* **Expense Tracking:** Dedicated module for students to log daily expenses (food, travel, materials).
* **Budget Alerts:** Helps students stay within their monthly allowance with interactive breakdowns.

### 📅 Academic Schedule Management
* **Timetable Tracker:** Keeps track of lectures, labs, and assignment deadlines.
* **Smart Reminders:** Ensures students never miss important academic submissions or exam dates.

### 🧠 AI-Assisted Capabilities (Future Scope)
* **Intelligent Assistant:** Designed to integrate autonomous, agentic AI workflows to predict personalized student schedules and optimize budget recommendations based on past habits.

## Tech Stack
* **Frontend:** React.js, Vite, Tailwind CSS
* **Routing & State:** React Router DOM, React Context API / State Management
* **Icons & Styling:** Lucide React / React Icons, Tailwind Custom Configuration
* **Backend Integration:** Built with a clean architecture ready to interface with Python-based (FastAPI/Django) or Node.js backends.

## Installation & Setup

 Step 1: Clone the Repository
git clone <your-namma-mitra-github-repo-link>
cd Namma-Mitra

Step 2: Install Dependencies
npm install

Step 3: Run the Application Local
npm run dev

Architecture & Project Structure
The project follows a component-driven, modular folder structure for scalability:
  src/components/ - Reusable UI elements (Navbar, Sidebar, Cards).
  src/pages/ - Core views (Dashboard, Transit Tracker, Budget Manager, Schedule).
  src/context/ - Global state for user data and application preferences.

Future Enhancements
Integrating local LLMs via Ollama for offline AI assistance.

Real-time Bangalore metro and bus tracking API integrations.

Shared peer-to-peer expense splitting features.
