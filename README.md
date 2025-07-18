# REST-API-CLIENT

*COMPANY*:CODTECH IT SOLUTIONS

*NAME* : JAGADEESHWARAN T

*INTERN ID*: CT04DZ410

*DOMAIN*: JAVA PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

-------------

## 📄 Description

This project was created to demonstrate the integration of Java applications with public web APIs using native libraries and external dependencies. The key focus is on using the `HttpURLConnection` class to send HTTP requests, and the `org.json` library to parse the JSON response. The application sends a GET request to a publicly accessible weather API (Open-Meteo), which returns current weather data for a specified set of geographical coordinates.

The project is ideal for beginners who are learning Java and want to understand real-world applications of networking, APIs, and JSON handling. It is also helpful for developers looking to build lightweight microservices or automation tools that fetch external data in Java.

The program is written in a single Java file (`WeatherApiClient.java`) and demonstrates best practices for reading API data, error handling, and formatting output for terminal display. The application does not require an API key, making it an excellent choice for educational and prototype purposes.

---

## 🛠 Tools & Technologies Used

- **Java (JDK 17+)**: Primary programming language for building and running the application.
- **Open-Meteo API**: Free public weather API that provides real-time weather data based on latitude and longitude.
- **org.json (JSON-Java)**: Open-source library used to parse JSON data in Java.
- **HTTPURLConnection**: Java’s built-in class for making HTTP requests.
- **VS Code / IntelliJ / Eclipse**: Compatible IDEs that can be used to develop and test the project.
- **Command-Line Interface (CLI)**: Used for compiling and running the application outside of an IDE.

---

## 🌍 Where This is Used

This project can be applied in several practical scenarios:

- ✅ **Learning Tool**: Perfect for students and beginners to understand how Java communicates with external APIs.
- ✅ **Prototypes**: Used in early-stage development of weather-based services, dashboards, or bots.
- ✅ **Automation Scripts**: Could be embedded in larger tools to automate weather-based tasks (e.g., notifications, alerts).
- ✅ **Academic Projects**: Easily adaptable into college-level mini-projects or demonstration apps.
- ✅ **Microservice Components**: Acts as a basic data-fetching service in a distributed or cloud-based architecture.

---

## 🚀 How to Run

Follow the steps below to compile and run the application:

### 1. Download the org.json Library

Download `json-20240303.jar` from:  
https://repo1.maven.org/maven2/org/json/json/20240303/json-20240303.jar

Place it in the `lib/` folder of your project.

### 2. Compile the Java Code

``bash
javac -cp ".;lib/json-20240303.jar" src/WeatherApiClient.java -d bin

##OUTPUT

<img width="1919" height="1022" alt="Image" src="https://github.com/user-attachments/assets/4551353a-671d-4750-ab0e-38098131db3b" />

