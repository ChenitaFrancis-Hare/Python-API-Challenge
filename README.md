# Python-API-Challenge

## Background
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

## Advisory
1. Add a .gitignore File
>For this assignment, you will need to add a .gitignore file to your repo. Doing so will prevent the api_keys.py file that contains your API key from being shared with the public. If you skip this step, anyone using GitHub could copy and use your API key, and you may incur charges as a result.

## Instructions
### Part 1: WeatherPy
    >In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.
    > For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.
    > To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

#### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

  * Latitude vs. Temperature
  * Latitude vs. Humidity
  * Latitude vs. Cloudiness
  * Latitude vs. Wind Speed


#### Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship:

  * Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
  * You may find it helpful to define a function in order to create the linear regression plots.
  * Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values


#### You should create the following plots:
  1. Northern Hemisphere: Temperature vs. Latitude
  2. Southern Hemisphere: Temperature vs. Latitude
  3. Northern Hemisphere: Humidity vs. Latitude
  4. Southern Hemisphere: Humidity vs. Latitude
  5. Northern Hemisphere: Cloudiness vs. Latitude
  6. Southern Hemisphere: Cloudiness vs. Latitude
  7. Northern Hemisphere: Wind Speed vs. Latitude
  8. Southern Hemisphere: Wind Speed vs. Latitude
  9. After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.


## References
The data used in this challenge was sourced from OpenWeatherMap API and Geoapify as instructed by edX Boot Camps LLC, and is intended for educational purposes only.
