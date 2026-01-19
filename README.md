# Weather Alert & Observation XML Project

## 📌 Project Description (App & API)

This project defines a **Weather Information System** based on XML technologies.  
The system is composed of:

- A **Weather App** that consumes structured weather data.
- A **Weather API** that provides weather observations and weather alerts in XML format.

The communication between the App and the API is fully based on **XML documents**, validated using **DTD** and **XML Schema (XSD)** to ensure data integrity, correctness, and consistency.

Two main XML documents are used:
- `weather_observation.xml` → current weather data.
- `weather_alert.xml` → weather warnings and alerts.

---

## 🔄 Data Exchanged Between the App and the API

The information exchanged between the App and the API includes:

### 🌤 Weather Observations
- City name
- Geographic coordinates (latitude and longitude with cardinal points)
- Observation date
- Temperature (with unit attribute)
- Humidity
- Wind speed (with unit attribute)
- Weather condition (rain, clear, etc.)

### ⚠ Weather Alerts
- Alert identifier
- Generation date and time
- Severity level (High, Moderate, etc.)
- Alert type (Strong Wind, Heavy Rain, etc.)
- Description of the alert
- Affected geographic areas
- Optional alert period (start and end date-time)

All date and time values follow the **ISO 8601 format**, as required by `xs:dateTime`.

---

## ✅ XML Validation Evidence (Screenshots)

The following screenshots demonstrate that the XML files are **well-formed and valid** according to their DTD and XSD definitions:

### Weather Observation XML Validation
![Weather Observation Validation](screenshots/weather_observation_validation.png)

### Weather Alert XML Validation
![Weather Alert Validation](screenshots/weather_alert_validation.png)

### XSD Validation
![XSD Validation](screenshots/xsd_validation.png)

> 📷 Screenshots were obtained using XML validation tools and IDE validators.

---

## 🛠 Tools and Websites Used

The following tools and websites were used during the development of this project:

1. **W3Schools XML Tutorials**  
   https://www.w3schools.com/xml/

2. **XML Schema (XSD) Specification**  
   https://www.w3.org/TR/xmlschema11-1/

3. **XML Validation Tool**  
   https://www.xmlvalidation.com/

4. **Visual Studio Code**  
   https://code.visualstudio.com/

5. **GitHub**  
   https://github.com/

6. **Online XML Formatter & Validator**  
   https://www.freeformatter.com/xml-validator-xsd.html

---

## 📁 Project Structure
├── XSD-XML-DTD---WeatherApp---JoanaRam-rez/

│ weather_observation.xml

│ weather_alert.xml

│ information.dtd

│  weather-schema.xsd

│ weather_observation_validation.png

│ weather_alert_validation.png

│ xsd_validation.png

└── README.md


---

## 📄 Author

Student project for XML, DTD, and XSD validation practice.




