---

# 🌦️ Real-Time Weather Web Application

## 📌 Overview
This project is a real-time weather web application that allows users to search for any city and instantly view current weather conditions. It uses a Python backend built with Flask and fetches live data from the OpenWeather API.

---

## 🚀 Features
- 🌍 Search weather by city name  
- 🌡️ Displays temperature, humidity, wind speed  
- ☁️ Shows weather condition with icon  
- ⚡ Real-time API data fetching  
- ❌ Handles invalid city and network errors  
- 🔒 Secure API key handling (environment variable support)

---

## 🛠️ Technologies Used
- Backend: Python, Flask  
- Frontend: HTML, CSS, JavaScript  
- API: OpenWeather API  
- HTTP Requests: Requests Library  

---

## 📂 Project Structure

real_time_weather_app/ │ ├── app.py ├── templates/ │   └── weather.html ├── static/ │   └── (CSS/JS if any) ├── requirements.txt └── README.md

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

git clone https://github.com/your-username/real_time_weather_app.git cd real_time_weather_app

---

### 2. Create Virtual Environment (Optional but Recommended)

python -m venv venv venv\Scripts\activate   # Windows

---

### 3. Install Dependencies

pip install flask requests

---

### 4. Get API Key
- Sign up at https://openweathermap.org/
- Generate your API key

---

### 5. Configure API Key

#### Option A (Quick)
Edit `app.py`:

API_KEY = "your_api_key_here"

#### Option B (Recommended)
Set environment variable:

**Windows (PowerShell):**

setx OPENWEATHER_API_KEY "your_api_key_here"

---

### 6. Run the Application

python app.py

---

### 7. Open in Browser

http://127.0.0.1:5000/

---

## 🧪 Testing
- ✅ Enter a valid city → Weather displayed  
- ❌ Empty input → Error message  
- ❌ Invalid city → “City not found”  
- ❌ No internet → Network error  

---

## 📸 Output
Displays:
- City Name  
- Temperature (°C)  
- Feels Like  
- Humidity  
- Wind Speed  
- Weather Condition + Icon  

---

## 🔮 Future Enhancements
- 📊 5-day weather forecast  
- 🌍 Auto-detect location (GPS)  
- 🌙 Dark/Light mode  
- 📱 Mobile responsive UI  
- ☁️ Deployment on cloud (Render / Vercel)

---

## 👨‍💻 Author
Mohammed Nouman  
Computer Science Engineering Student  

---

## 📄 License
This project is open-source and available for learning and educational purposes.


---
