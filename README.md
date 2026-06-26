# 🌤️ Weather App

### Modern & Responsive Weather Application

---

## 🚀 Overview

A modern React-based weather application that provides real-time weather information for cities worldwide with a clean UI, responsive design, and seamless user experience.

---

## 🖼️ Preview

<img width="1919" height="929" alt="image" src="https://github.com/user-attachments/assets/beb2ae44-45f5-4a6a-a2ce-a5e17730f738" />


## ✨ Features

### 🌤️ Core Features

| Feature         | Description                            |
| --------------- | -------------------------------------- |
| City Search     | Search weather by city name            |
| Real-time Data  | Fetch live weather updates             |
| Temperature     | Shows current & feels-like temperature |
| Weather Metrics | Humidity, wind speed, pressure         |
| Weather Icons   | Visual representation of conditions    |
| Location Info   | Displays city & country                |

### 🎨 User Experience

| Feature          | Description                          |
| ---------------- | ------------------------------------ |
| Loading State    | Shows loading indicator during fetch |
| Error Handling   | Displays user-friendly errors        |
| Input Validation | Prevents invalid searches            |
| Welcome Screen   | Intro screen for users               |
| Accessibility    | Supports keyboard & screen readers   |

### 📱 Responsive Design

| Device  | Optimization      |
| ------- | ----------------- |
| Mobile  | Compact layout    |
| Tablet  | Balanced spacing  |
| Desktop | Full-width layout |

---

## 🛠️ Tech Stack

| Technology         | Purpose            |
| ------------------ | ------------------ |
| React.js           | Frontend framework |
| CSS3               | Styling            |
| OpenWeatherMap API | Weather data       |

---

## 🚀 Getting Started

```bash
git clone <repository-url>
cd Weather-App
npm install
npm start
```

Create a `.env.local` file:

```env
REACT_APP_WEATHER_API_KEY=your_api_key
```

---

## 📂 Project Structure

```text
Weather-App/
├── src/
│   ├── components/
│   ├── styles/
│   ├── utils/
│   ├── App.js
│   └── index.js
├── public/
├── .env.example
├── package.json
└── README.md
```

---

## 🔄 App Flow

```text
        ┌──────────────┐
        │   Open App   │
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │ Search City  │
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │ Validate Input│
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │ Fetch Weather│
        │     Data     │
        └──────┬───────┘
               │
        ┌──────▼───────┐
        │ Display Data │
        └──────┬───────┘
               │
        ┌──────▼───────┐
        │ Error?       │
        └──────┬───────┘
               │
        ┌──────▼───────┐
        │ Show Error   │
        └──────────────┘
```

---

## 🌟 Future Enhancements

| Feature         | Description                 |
| --------------- | --------------------------- |
| 5-Day Forecast  | Extended weather prediction |
| Hourly Forecast | Hour-by-hour updates        |
| Dark Mode       | Theme toggle                |
| Auto Location   | Detect user location        |
| Favorite Cities | Save preferred cities       |
| Multi-language  | Support multiple languages  |

---

## 📜 License

MIT License
