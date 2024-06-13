# Weather App

## Description
The Weather App is a web application that allows users to check the current weather conditions for any city worldwide. It integrates with the OpenWeather API to fetch real-time weather data and displays it in a user-friendly interface.

The application is built using Java Servlets and JSP for backend logic and dynamic content rendering, while the frontend utilizes HTML, CSS, and JavaScript.

## Features
- **Current Weather:** Displays current temperature, weather condition, humidity, and wind speed.
- **Search Functionality:** Users can input any city name to get weather information.
- **Responsive Design:** Ensures the app is usable across different devices and screen sizes.
- **API Integration:** Uses the OpenWeather API to fetch weather data.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Java, Servlets, JSP
- **API:** [OpenWeather API](https://openweathermap.org/api)

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ayaank7/Weather-App.git
   cd Weather-App

2. **Configuration:**
   - Obtain an API key from [OpenWeather API](https://openweathermap.org/api).
   - Replace `"your_api_key"` in `MyServlet.java` with your actual API key:
     ```java
     String apiKey = "your_api_key";
     ```
   - Save and close the file.

3. **Build and Deploy:**
   - Ensure you have Java Development Kit (JDK) installed and configured.
   - Deploy the application on a Servlet container (e.g., Apache Tomcat):
     - Place the WAR file or project folder in the appropriate directory of your Servlet container.

4. **Run the Application:**
   - Start your Servlet container.
   - Access the application in your browser at `http://localhost:8080/Weather-App` (adjust the URL as per your deployment settings).

## Directory Structure
```
weather-app/
├── images/                 # Directory for images used in the application
│   └── Clouds.png          # clouds image file 
├── WEB-INF/
│   ├── lib/               # Directory for libraries and dependencies
│   │   └── gson-2.8.5.jar  # gson library file
│   └── web.xml            # Servlet configuration file
├── index.jsp              # JSP file for displaying weather information
├── MyServlet.java         # Servlet code for handling API requests
├── style.css              # CSS file for styling the application
├── script.js              # JavaScript file for client-side functionality
└── README.md              # Project documentation file

```

## Screenshots
<img src="https://github.com/Ayaank7/Weather-App/assets/142133833/97d8a363-f0d3-480d-8563-26d31bc53990" alt="Screenshot 1" width="600">
<img src="https://github.com/Ayaank7/Weather-App/assets/142133833/926accce-cd0a-44d2-800a-8f24e4fc087b" alt="Screenshot 2" width="600">

## Author
- [Ayaan Khan](https://www.linkedin.com/in/ayaan-khan-9a0a711b0/)

## Acknowledgements
- [OpenWeather API](https://openweathermap.org/api) for providing weather data.
