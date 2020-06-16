# Collecting Weather Data and Hotel Information to Plan the Perfect Vacation
This repository contains two Jupyter notebooks that employ API calls, various data manipulation tools, error checking, and the Python programming language to carry out several analyses of world data in order to plan a hypothetical vacation. The first notebook examines weather trends by generating a list of random cities around the world based on randomly-selected latitude/longitude coordinates and picking the city closest to those coordinates. Weather data is then collected via a call to a global weather API. These data are fed into Matplotlib to allow the user to compare data on the climates in the various locales (for the purpose of the second half of the project) and then to produce some interesting graphs about various climatic conditions as a function of latitude. These graphs are ultimately used in a subsequent web design project.

The second notebook selects those locations around the world that fit user-defined criteria (pleasant temperatures, limited rainfall, etc) and uses the GMaps service from Google to identify hotels in the various locations. The code then plots the hotels on a map. Using this code you can plan a hypothetical vacation.

### Resources Employed
* Python
* Pandas
* Matplotlib
* Numpy
* Requests / API
* GMaps
