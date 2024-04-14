![FRED API](https://github.com/Sathyam-Kakodkar/Fetch-API/blob/main/Images/API%20Image.png)


# Fetching Data From An API

## What is an API 

APIs are mechanisms that enable two software components to communicate with each other using a set of definitions and protocols.

## FRED API

The FRED® API is a web service that allows developers to write programs and build applications that retrieve economic data from the FRED® and ALFRED® websites hosted by the Economic Research Division of the Federal Reserve Bank of St. Louis.


**Website** --> [FRED API](https://fred.stlouisfed.org/docs/api/fred/)

To fetch data from an API using Python's Requests library, follow these steps:

1. Import the Requests module: Import the Requests library in your Python script.
2. Send a GET request: Use `requests.get()` to send a GET request to the API endpoint.
3. Check the response status code: Verify that the request was successful (status code 200).
4. Access the response data: Use `response.json()` to parse the JSON response into a Python dictionary.
5. Process the data: Once you have the data, you can process it as needed for your application.

**Disclaimer** : This project is for educational purposes only. It is only intended to demonstrate data extraction techniques. Always respect website terms of service and use responsibly.




