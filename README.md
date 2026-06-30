# 🌤️ Weather App

> **Sleek, Fast & Modern Weather Experience**

---

## 🚀 Overview

The **Weather App** is a simple yet powerful React-based application designed to provide real-time weather updates for cities across the globe. Built with a focus on usability and performance, it allows users to quickly search for any location and instantly view accurate weather details.

Whether you're planning your day, checking travel conditions, or just curious about the weather somewhere else, this app delivers essential information in a clean and intuitive interface. It leverages the OpenWeatherMap API to fetch reliable data and presents it in a user-friendly format that works seamlessly across devices.

---

## 🖼️ Preview

<img width="1919" height="929" alt="Screenshot 2026-06-27 000726" src="https://github.com/user-attachments/assets/0ac8a49f-adfd-485e-87f3-edc548fc4c58" />

## ✨ Features

* 🔍 **Quick City Search**
  Easily search for any city worldwide and get instant weather updates.

* 🌡️ **Real-Time Temperature Data**
  Displays current temperature along with "feels like" conditions for better accuracy.

* 💨 **Detailed Weather Metrics**
  Includes wind speed, humidity, and atmospheric pressure to give a complete overview.

* 📍 **Location Information**
  Shows city and country details for clarity and context.

* 🌥️ **Dynamic Weather Icons**
  Visual indicators that change based on current weather conditions.

* 📱 **Responsive Design**
  Optimized for mobile, tablet, and desktop devices for a smooth experience everywhere.

* ⚡ **Fast & Reliable Performance**
  Handles loading states and errors gracefully to ensure a seamless user experience.

---

## 🔄 Workflow

```text
🌤️ Open Application
      │
      ▼
🔍 Enter City Name
      │
      ▼
🌐 Request Weather Data from API
      │
      ▼
📊 Display Weather Information
```

---

## 🛠️ Tech Stack

* ⚛️ **React.js** – Frontend framework for building interactive UI
* 🎨 **CSS3** – Styling and responsive layout
* 🌐 **OpenWeatherMap API** – Source of real-time weather data

---

## 🚀 Installation

Follow these steps to run the project locally:

```bash
git clone <repository-url>

cd Weather-App

npm install

npm start
```

Create a `.env.local` file in the root directory and add your API key:

```env
REACT_APP_WEATHER_API_KEY=your_api_key
```

> 💡 Make sure to get your API key from OpenWeatherMap before running the app.

---

## 📂 Project Structure

```text
Weather-App/
├── src/
│   ├── components/   # Reusable UI components
│   ├── styles/       # CSS files
│   ├── utils/        # Helper functions
│   ├── App.js        # Main application component
│   └── index.js      # Entry point
├── public/           # Static assets
├── .env.example      # Environment variable template
├── package.json      # Project dependencies
└── README.md         # Project documentation
```

---

## 📜 License

**MIT License**
