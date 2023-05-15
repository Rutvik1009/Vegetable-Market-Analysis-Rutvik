# Vegetable-Market-Analysis-Rutvik

1) Extracted all vegetable data of Noida Vegetable Market from the available URL, between 15th November 2021 and 31 March 2023. 
      
-  To retrieve the data, the code utilized the requests library, which allows making HTTP requests and retrieving data from websites. The user-agent header was set to mimic a web browser, ensuring smooth retrieval without any restrictions or anti-scraping measures.
-  The code specified the URL of the API endpoint containing the desired data. The URL included parameters such as the start date, end date, and vegetable IDs to filter the data based on the requirements.Using the requests.get() method, an HTTP GET request was made to the specified URL with the user-agent header included. The response from the API request was stored in the res variable.
- To extract the data, the code employed the res.json() method, which parsed the response content as JSON. The extracted data was then stored in the data variable for further analysis or processing.
- By following these steps, the code successfully retrieved the data from the API endpoint and made it available for subsequent operations.
