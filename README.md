# REST-API-CLIENT

*COMPANY*:CODTECH IT SOLUTIONS

*NAME* : JAGADEESHWARAN T

*INTERN ID*: CT04DZ410

*DOMAIN*: JAVA PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

## 📄 Description

This project demonstrates how to:

- Make HTTP GET requests in Java
- Consume a public REST API (Open-Meteo)
- Parse JSON responses using the `org.json` library
- Display data like temperature, windspeed, and time in a clean format

---

## 🛠 Tools & Technologies Used

- **Java** (JDK 17+)
- **org.json** (for JSON parsing)
- **Open-Meteo API** (No API key required)
- **VS Code / Command Line** (for development & running)
- **HTTPURLConnection** (built-in Java class for HTTP requests)

---

## 🌍 Where This is Used

This project is useful for:

- 🔰 Beginners learning REST API integration in Java
- 🎓 Academic/college assignments and demos
- 🌐 Small-scale weather info tools or automation
- 🧪 Testing Java-based network connectivity and parsing

---

## 🚀 How to Run

```bash

# Compile
javac -cp ".;lib/json-20240303.jar" src/WeatherApiClient.java -d bin

# Run
java -cp ".;lib/json-20240303.jar;bin" WeatherApiClient
