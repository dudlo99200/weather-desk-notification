# Weather Notification App (Python)

A simple Python script that fetches real-time weather data for a given city and shows a desktop notification with temperature and wind speed.

The app uses the Open-Meteo API (no API key required) and works cross-platform.

---

## Features

- Convert city name to geographic coordinates
- Fetch current weather data (temperature & wind speed)
- Display weather updates as desktop notifications
- Lightweight and beginner-friendly

---

## Tech Stack

- Python 3
- Requests
- Plyer
- Open-Meteo API

---

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/weather-notification-app.git
cd weather-notification-app
```
2. Create and activate a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate  # Linux / Mac
venv\Scripts\activate     # Windows
```
3. Install dependencies
```bash
pip install -r requirements.txt
```

---

## Usage
Open main.py and change the city name:
```bash
city = "Chandpur"
```
Save the file and run:
```bash
python main.py
```

---

## API Used
Open-Meteo (Geocoding & Weather API)
https://open-meteo.com/



















