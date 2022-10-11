# Transit Data Application

This project involves:
- Analyzing the data from the MBTA API
- Storing data returned by the MBTA API in a MySQL database inside a Docker container
- Performing change data capture (CDC) on the MySQL database and storing any changes to a MongoDB database
- The server will run for a 12 hour period and store the data in the MySQL database
- The Jupyter Notebook contains the data loaded and analyzed 

See analyzed data [here](transit-data-app.ipynb)
