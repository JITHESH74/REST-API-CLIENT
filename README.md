# REST-API-CLIENT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: JITHESH T

*INTERN ID*: CT04DK730

*DOMAIN*: JAVA

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR 

##  Weather API Client using Java HTTPClient

    Project Overview

The Weather API Client is a lightweight Java application designed to fetch and display real-time weather data from an open weather API. This project demonstrates how to make HTTP requests in Java, handle JSON responses, and extract useful weather-related information programmatically. It uses the Open-Meteo API, which provides free access to current weather conditions based on geographic coordinates (latitude and longitude).

The application sends an HTTP GET request to the API endpoint for weather data at the specified coordinates (latitude 22, longitude 79, which corresponds roughly to a central India location). The response is returned in JSON format, which is then parsed using the org.json library to extract and print the current temperature.

This project highlights how easily external APIs can be consumed in Java using modern features introduced in Java 11+, especially the built-in HttpClient class from the java.net.http package.

    Tools & Technologies Used

Java 11+: Required to use the new HttpClient API for asynchronous and synchronous HTTP communication.

Open-Meteo API: A free weather API that doesn’t require authentication or API keys.

org.json (JSON-Java): A third-party Java library used to parse and work with JSON data.

IntelliJ IDEA: IDE used to develop and debug the application.

Maven or Manual JAR Setup: To add the org.json dependency if not using Maven.

Command Line or Terminal: For executing the Java program and observing output.

    Real-World Use Cases

Weather Dashboard or Widget: Can be the backend logic for displaying current temperature in desktop or web dashboards.

Travel Apps: Used to show weather updates for different cities as users plan their trips.

Agricultural IoT Applications: Helpful in fetching real-time environmental conditions for automated crop monitoring systems.

Smart Home Automation: Can trigger actions like closing windows or adjusting thermostats based on real-time weather.

Educational Tools: Demonstrates how students can consume public APIs using Java.

    Learning Outcomes

Through this project, I gained experience in:

Consuming RESTful APIs using Java

Handling HTTP requests/responses using Java 11 HttpClient

Parsing and extracting information from JSON responses using org.json

Understanding geolocation-based API parameters

Exception handling for network and JSON parsing errors

This project builds a strong foundation for more complex applications that consume APIs, such as stock price fetchers, currency converters, news aggregators, or weather forecasting systems with historical data analysis.

    ##OUTPUT
![Image](https://github.com/user-attachments/assets/1c947f8f-99fe-42b7-9cc8-9999e4d1ac0b)