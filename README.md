Functional Modules
1. Earthquake Data Retrieval
    • Inputs: North, South, East, and West geographic boundaries.
    • Backend endpoint: fetch.php
    • Functionality:
        ◦ Sends bounding box coordinates to the server.
        ◦ Receives a list of earthquake events.
        ◦ Dynamically renders each event’s metadata (datetime, depth, latitude, longitude, magnitude, and source) into the UI.
2. Timezone Information Lookup
    • Inputs: Latitude and Longitude.
    • Backend endpoint: get_timezone.php
    • Functionality:
        ◦ Fetches timezone-related data for a specific location.
        ◦ Displays timezone ID, country name, local time, sunrise, and sunset.
3. Weather Observation Query
    • Input: Weather station name.
    • Backend endpoint: weather.php
    • Functionality:
        ◦ Retrieves current weather observations for the specified station.
        ◦ Displays meteorological data such as temperature, humidity, wind speed, and weather conditions.
Error Handling & User Feedback
    • Network or server-side errors are handled using AJAX error callbacks.
    • User-friendly error messages are displayed directly in the results container.
    • Successful and unsuccessful responses are clearly differentiated based on the status field.
Key Technologies Used
    • JavaScript / jQuery – DOM manipulation, event handling, AJAX requests
    • PHP – Server-side processing and API integration
    • JSON – Data exchange format
    • HTML/CSS – User interface and layout

   
Summary
This project demonstrates effective use of asynchronous web communication, clean separation of frontend and backend responsibilities, and dynamic UI updates. It is designed for responsiveness, scalability, and ease of integration with external geospatial and environmental data sources.
