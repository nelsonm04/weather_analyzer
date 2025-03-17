Project Overview
-The Weather Data Analyzer is a Java-based application that reads weather data from a CSV file and provides insightful weather statistics. It utilizes modern Java features such as:
-Records for data representation
-Enhanced switch statements for weather categorization
-Streams & lambdas for data processing
-Pattern Matching & Functional Programming
-Features
-Average Temperature Calculation: Computes the average temperature for a given month.
-Hot Days Detection: Lists days where the temperature exceeded a specified threshold.
-Rainy Days Count: Counts the number of rainy days.
-Weather Categorization: Uses an enhanced switch statement to classify weather conditions as "Cold", "Cool", "Warm", or "Hot".

How to Run
Prerequisites
Ensure you have Java 17+ installed.
Place your weather data CSV file inside the src/resources/ folder.
Compile and run the program:

java Main src/resources/weatherdata.csv

Example Output

Average Temperature for month 8: 32.5°C
Days with temperature above 30.0°C:
2023-08-02
2023-08-05
Number of rainy days: 2
Weather Categories:
2023-08-01 → Warm
2023-08-02 → Hot
2023-08-03 → Cool

Project Structure
weather-data-analyzer/
│── src/
│   ├── Main.java  # Main program file
│   ├── resources/
│   │   ├── weatherdata.csv  # Sample weather data
│
└── README.md  # Documentation

Technologies Used
-Java 17+
-Streams & Functional Programming
-Java Records
-Enhanced Switch Statements
