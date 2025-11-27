# 🌤️ Weather-Based Email Notifier

[![Python](https://img.shields.io/badge/Python-3.9+-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

An automated workflow that fetches current weather data for a specified location and sends an email notification based on temperature conditions (cold or warm). Stay informed about weather changes without manually checking the forecast.  

---

## 📸 Screenshot / Diagram

You can add an image to your README like this:

![Weather Notifier](images/weather_email_flow.png)

> Place your image in a folder called `images` in your repository.

---

## 🔹 Features

- Fetches real-time weather data using [OpenWeatherMap API](https://openweathermap.org/api).  
- Sends a cold or warm weather email based on configurable temperature thresholds.  
- Fully automated and can be scheduled daily or multiple times per day.  
- Customizable email content.  

---

## ⚙️ Prerequisites

- Python 3.9+  
- [OpenWeatherMap API Key](https://home.openweathermap.org/api_keys)  
- Email account credentials (SMTP)  

---

## 💻 Installation

1. Clone the repository:

```bash
git clone https://github.com/Huzaifashah08/weather-email-notifier.git
cd weather-email-notifier
