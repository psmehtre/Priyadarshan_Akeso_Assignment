# Priyadarshan_Akeso_Assignment-

* POSTMAN Collection is exported in JSON Format *
1. Backend API Testing - 

Introduction:
The Postman Collection provided contains a set of API requests for interacting with the OpenWeather API. These requests cover various scenarios for retrieving weather data and performing operations such as creating new weather entries and updating existing ones.
GET Requests:
Get Current Weather:
This request retrieves the current weather data for a specified city.
It validates that the response contains the expected data fields such as temperature, humidity, and weather conditions.

Invalid API Key:
This request tests the scenario where an invalid API key is provided.
It verifies that the API returns a 401 status code along with an appropriate error message.

Missing City Name:
This request tests the scenario where the city name parameter is missing.
It validates that the API returns a 400 status code with an error message indicating the missing parameter.

Boundary Test: Temperature Check for a Specific City:
This request checks the temperature range for a specific city (Siberia).
It ensures that the temperature value falls within the expected range.

Successful Request with Celsius Units:
This request demonstrates a successful weather data retrieval with units specified as Celsius.
It verifies that the response includes temperature data in Celsius units.

Successful Request with Fahrenheit Units:
This request demonstrates a successful weather data retrieval with units specified as Fahrenheit.
It verifies that the response includes temperature data in Fahrenheit units.

Successful Request with Humidity Data:
This request demonstrates a successful weather data retrieval with humidity data included.
It validates that the response contains humidity information.

POST Request:
New Request:
This request creates a new weather entry for a specified city.
It includes a sample request body with the necessary data fields.


PATCH Request:
Update City Weather Entry:
This request updates an existing weather entry for a specific city.
It includes a sample request body with updated weather data fields.


2. Manual Testing 
Wrote detailed Test cases for all features of mobile apps that can cover Edge cases and negative scenarios.

- *Test Scenarios for Online Doctor Appointment and Consultation Mobile App.xlsx.pdf*
