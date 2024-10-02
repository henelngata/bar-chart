# United States GDP Bar Chart

This project visualizes the United States Gross Domestic Product (GDP) data from 1947 to 2015 using a bar chart. It's built with HTML, CSS, and JavaScript, utilizing the D3.js library for data visualization.

## Project Description

This bar chart displays the quarterly GDP data of the United States over time. Each bar represents the GDP value for a specific quarter, with the x-axis showing the time and the y-axis showing the GDP value in billions of dollars.

## Features

- Interactive bar chart showing US GDP data
- Tooltip displaying exact date and GDP value on hover
- Responsive design
- Meets freeCodeCamp's Data Visualization Project requirements

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- D3.js (Data-Driven Documents)

## Data Source

The GDP data is fetched from the following URL:
[https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json](https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json)

## Setup and Usage

1. Clone this repository to your local machine.
2. Open the `index.html` file in a modern web browser.
3. The chart should load automatically, fetching data from the provided URL.

## User Stories

This project fulfills the following user stories as per freeCodeCamp's requirements:

1. The chart has a title with a corresponding `id="title"`.
2. The chart has a `g` element x-axis with a corresponding `id="x-axis"`.
3. The chart has a `g` element y-axis with a corresponding `id="y-axis"`.
4. Both axes contain multiple tick labels with the `class="tick"`.
5. The chart has `rect` elements for each data point with a corresponding `class="bar"`.
6. Each `.bar` has `data-date` and `data-gdp` properties containing the date and GDP values.
7. The `.bar` elements' `data-date` properties match the order of the provided data.
8. The `.bar` elements' `data-gdp` properties match the order of the provided data.
9. Each `.bar` element's height accurately represents the data's corresponding GDP.
10. The `data-date` attribute and its corresponding `.bar` element align with the x-axis values.
11. The `data-gdp` attribute and its corresponding `.bar` element align with the y-axis values.
12. Hovering over an area shows a tooltip with a corresponding `id="tooltip"` displaying more information about the area.
13. The tooltip has a `data-date` property corresponding to the `data-date` of the active area.

## Testing

This project includes the freeCodeCamp Test Suite. To run the tests:

1. Open the project in your browser.
2. Select the "GDP Bar Chart" from the dropdown menu in the upper left corner.
3. Click "Run Tests" to see the test results.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Data provided by freeCodeCamp
- Built as part of the freeCodeCamp Data Visualization Certification