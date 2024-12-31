# Statistics Calculator

This project is a web-based Statistics Calculator that allows users to 
compute key statistical metrics including mean, median, mode, range, 
variance, and standard deviation. Users can input a list of numbers, 
separated by commas, and the calculator dynamically displays the results.

## Features

- Mean Calculation: Computes the average of the input numbers.
- Median Calculation: Finds the middle value in a sorted list.
- Mode Calculation: Identifies the number(s) that appear most frequently.
- Range Calculation: Determines the difference between the largest and smallest numbers.
- Variance Calculation: Measures the spread of the numbers from the mean.
- Standard Deviation Calculation: Calculates the square root of the variance.
- Responsive and user-friendly interface.

## Technologies Used

- HTML5: For the structure of the webpage.
- CSS: For styling the page.
- JavaScript: For implementing the statistical calculations and DOM manipulation.

## Installation

Clone this repository to your local machine:
    git clone https://github.com/JackSawyerWATX/statistics-calculator.git

## Navigate to the project directory:

cd statistics-calculator
Open the index.html file in your browser to use the calculator.

## Usage

- Enter a list of numbers separated by commas in the input field.
- Click the Calculate button.
- View the calculated results under each statistical metric in the results section.

## Project Structure

statistics-calculator/
├── index.html       # Main HTML file
├── styles.css       # Styles for the project
├── script.js        # JavaScript for calculations
└── README.md        # Project documentation

## Code Overview

- HTML: Provides the input field, submit button, and placeholders for displaying results.
- CSS: Styles the form, results section, and page layout.
- JavaScript: Implements the following functions:
- getMean(numbers) - Calculates the mean.
- getMedian(numbers) - Calculates the median.
- getMode(numbers) - Finds the mode.
- getRange(numbers) - Computes the range.
- getVariance(numbers) - Calculates the variance.
- getStandardDeviation(numbers) - Computes the standard deviation.

## Future Improvements

- Add error handling for invalid inputs.
- Allow users to input numbers in different formats (e.g., space-separated).
- Enhance the UI with Bootstrap or another CSS framework.
- Add the ability to export results as a file (e.g., CSV or PDF).
- Add unit tests for the JavaScript functions.

## License

- This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributions

- Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request with your changes.

## Contact

For any questions or suggestions, please feel free to contact:

    Email: contact@jonathanfausset.com
    GitHub: JackSawyerWATX