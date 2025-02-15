# API-INTEGRATION-AND-DATA-VISUALIZATION

COMPANY: CODTECH IT SOLUTIONS

NAME: TANISHQ PARKHE

INTERN ID: CT08ROX

DOMAIN: PYTHON

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

# OVERVIEW OF THE PROJECT

Introduction:
Asteroids, also known as minor planets, are small celestial objects orbiting the Sun. Some of them come very close to Earth, and tracking these near-Earth objects (NEOs) is important for planetary defense, space exploration, and scientific research. NASA provides real-time asteroid tracking data through its Near-Earth Object Web Service (NeoWs) API, which allows developers and researchers to access up-to-date asteroid information.

This project focuses on retrieving asteroid data from NASA's API and visualizing the closest asteroids using Matplotlib. The visualization helps understand which asteroids are passing near Earth by displaying their names and distances in a simple bar chart. This graphical representation provides an easy-to-understand comparison of asteroid distances from our planet.

Objectives:
1. The main goals of this project are:
2. Fetch real-time asteroid data from NASA’s public API.
3. Extract relevant information such as asteroid names and distances.
4. Sort the data to find the 10 closest asteroids to Earth.
5. Visualize the asteroid distances using a bar chart.
6. Ensure clarity in the graphical representation for easy interpretation.

Project Workflow:
1. Fetching Data from NASA’s API
The first step is to connect to NASA’s Near-Earth Object API. The script makes a GET request to the API, retrieving asteroid data in JSON format for the current date. The API response contains a list of asteroids, along with details such as:

Asteroid name
Closest approach date
Miss distance (in kilometers)

2. Processing the Data
Once the data is fetched, the script processes it by:

Extracting relevant information (name, distance).
Sorting the asteroids by their closest approach distance.
Selecting the 10 closest asteroids for visualization.
Since some asteroids may have distances in the millions of kilometers, this step ensures that only the most relevant asteroids are displayed in the graph.

3. Visualization with Matplotlib
Matplotlib is used to create a horizontal bar chart, where:

The asteroid names are placed on the Y-axis.
The miss distance from Earth (in km) is plotted on the X-axis.
Bars are color-coded for clarity.
Grid lines are added to improve readability.
The chart allows users to compare asteroid distances visually and quickly identify which ones are the closest to Earth.

Conclusion:
This project provides a clear and simple way to explore near-Earth asteroid data using NASA’s API. By fetching and visualizing asteroid distances, it helps in better understanding asteroid movements and their proximity to Earth. The combination of Python, API integration, and data visualization makes this a useful project for learning and scientific analysis.



# OUTPUT

![Image](https://github.com/user-attachments/assets/a64061ee-3ee8-4f60-b7cf-161899bfd41a)
