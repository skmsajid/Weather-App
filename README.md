# 🌤️ Weather App

### A Sleek & Responsive Weather Experience

---

## 🚀 Overview

This React-powered weather application provides real-time weather information for cities worldwide through a clean, responsive, and user-friendly interface.

---

## 🖼️ Preview
<img width="1919" height="929" alt="Screenshot 2026-06-27 000726" src="https://github.com/user-attachments/assets/4994c2d6-d113-4134-97d8-dd0f32cba4ef" />
## ✨ Features

| 🌤️ Core Features            | 🎨 User Experience  | 📱 Responsive Design |
| ---------------------------- | ------------------- | -------------------- |
| 🔍 Search by city            | ⚡ Loading state     | 📱 Mobile            |
| 🌡️ Real-time weather        | ❌ Error handling    | 📲 Tablet            |
| 🌡️ Temperature & Feels Like | 🎯 Input validation | 💻 Desktop           |
| 💨 Humidity, Wind & Pressure | 👋 Welcome screen   |                      |
| 📍 City & Country            | ♿ Accessibility     |                      |
| 🌥️ Weather icons            | 🎨 Modern UI        |                      |

---

## 🔄 Application Workflow

```text
                🚀 Start
                   │
                   ▼
          🌤️ Open Weather App
                   │
                   ▼
            🔍 Search City
                   │
                   ▼
           ✅ Validate Input
                   │
         ┌─────────┴─────────┐
         │                   │
         ▼                   ▼
   ❌ Invalid Input     🌐 Request API
         │                   │
         ▼                   ▼
   Show Validation     Receive Response
      Message                 │
                              ▼
                    ┌─────────┴─────────┐
                    │                   │
                    ▼                   ▼
              📊 Success           ❌ Failure
                    │                   │
                    ▼                   ▼
          Display Weather       Show Error Message
                    │                   │
                    └─────────┬─────────┘
                              ▼
                          🔍 Search Again
```

---

## 🛠️ Tech Stack

| Technology            | Purpose      |
| --------------------- | ------------ |
| ⚛️ React.js           | Frontend     |
| 🎨 CSS3               | Styling      |
| 🌐 OpenWeatherMap API | Weather Data |

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
│
├── src/
│   ├── components/
│   ├── styles/
│   ├── utils/
│   ├── App.js
│   └── index.js
│
├── public/
├── .env.example
├── package.json
└── README.md
```

---

## 🚀 Future Enhancements

| Planned Features          |
| ------------------------- |
| 📅 5-Day Forecast         |
| ⏰ Hourly Forecast         |
| 🌙 Dark Mode              |
| 📍 Auto Location          |
| ⭐ Favorite Cities         |
| 🌍 Multi-language Support |

---

## 📜 License

**MIT License**
