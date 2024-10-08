---
layout: post-wide
hero-bg-color: "#D22E1E"
uid: flights
title:  "Flight Data Visualization Project"
worktype: "Coding"
date:   2013-07-01 12:00:00
categories: portfolio
progress: 100
---
# (Flight Data Visualization Project)[https://github.com/takline/Home/tree/main/Analytics%2C%20Reporting%20%26%20Visualization/Flight_DataViz]

## Overview

This project was developed for a hackathon competition (I got second place 😐). It's designed to provide an insightful visualization of flight data using D3.js for interactive graphics and Python for data processing. The focus was on creating an engaging experience that is both informative for engineers and accessible to non-technical users.

To see the project in action, visit [this page](https://takline.github.io/Demos/Analytics,%20Reporting%20&%20Visualization/Flight_DataViz/).

## Features

- **Interactive Flight Data Visualizations**: Utilizes D3.js to present data in an engaging and interactive manner.
- **Data Processing with Python**: Employs Python for efficient and accurate data manipulation and preparation.
- **Comprehensive Analysis**: Offers insights into flight delays, cancellations, and overall travel experiences.

## How It Works

The project is divided into two main components:

1. **Data Processing (Python)**
   - The Python script processes flight data, calculating various metrics like flight counts, travel times, and experience scores.
   - Outputs processed data into a CSV file for use in visualizations.

2. **Visualization (HTML, JavaScript)**
   - HTML and JavaScript with D3.js render the data into interactive charts and graphs.
   - Users can explore different aspects of the data through interactive elements.

## Installation and Setup

1. **Python Environment Setup**
   - Ensure Python >=2.7 is installed.
   - Install required packages: `pandas`.
   - Run the Python script to generate the CSV file.

2. **Web Server Setup**
   - Host the HTML files on a web server.
   - Ensure the CSV file generated by the Python script is accessible to the HTML/JavaScript code.

## Usage

- **For Technical Users**: Run the Python script to process the latest data. Host the HTML files on a server and open them in a web browser.
- **For Non-Technical Users**: Simply navigate to the hosted web page and interact with the visualizations. Hover over elements for detailed info.

## File Structure

- `flights.py`: Python script for processing flight data.
- `index.html`: Main HTML file for the visualization.
- `iframe.html`: Embedded HTML for specific visual components.
- `js/`: JavaScript files, including D3.js for rendering visualizations.
- `css/`: Style sheets for the web interface.

## Contributing

Contributions to enhance this project are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes with clear, descriptive messages.
4. Create a pull request.

## Acknowledgements

I'm grateful for the support of my peers and mentors during the hackathon. Their insights and feedback were invaluable and the competion was a blast.

## Contact

For more information, queries, or suggestions, please reach out to me at [tylerkline@gmail.com].

