# Water Tank Problem – Rainwater Trapping Visualization

## Project Overview

This project is a frontend web application that calculates the amount of rainwater trapped between blocks of different heights. It uses HTML, CSS, and Vanilla JavaScript to calculate the result and visualize the blocks and trapped water using SVG.

## Features

- Accepts comma-separated block heights as input.
- Calculates the total units of trapped rainwater.
- Displays a visual representation of blocks and trapped water.
- Uses SVG to draw the visualization.
- Validates user input and handles invalid values.
- Provides an interactive and responsive user interface.

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- SVG (Scalable Vector Graphics)
- Google Colab

## Algorithm

For each block, the amount of trapped water depends on the tallest block to its left and the tallest block to its right.

**Formula:**

`Water at position i = max(0, min(leftMax[i], rightMax[i]) - height[i])`

The total trapped water is the sum of the water stored at every position.

## Example

**Input:**

`[0,4,0,0,0,6,0,6,4,0]`

**Output:**

`18 Units`

## How to Run

1. Clone or download this repository.
2. Open the `index.html` file in a modern web browser.
3. Enter the block heights separated by commas.
4. Click **Calculate Water**.
5. View the total trapped water and its visualization.

No additional libraries or installations are required.

## Project Structure

```text
water-tank-problem/
├── index.html
└── README.md
```

## Learning Outcomes

- Understanding arrays and loops in JavaScript.
- Implementing an algorithmic problem-solving approach.
- Working with HTML and CSS to build a user interface.
- Creating dynamic SVG visualizations.
- Validating user input and displaying calculated results.

## Author

K. Surendar
