
# Calorie Counter

Welcome to the Calorie Counter web application! This simple tool allows users to track their daily calorie intake, set a budget, add food items or exercise, and calculate remaining calories.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [JavaScript Logic](#javascript-logic)
- [Contributing](#contributing)
- [License](#license)

## Features

- Set a daily calorie budget.
- Add entries for breakfast, lunch, dinner, snacks, and exercise.
- Dynamically add multiple entries for each category.
- Calculate remaining calories based on the budget and consumed calories.
- Visual indication of a calorie surplus or deficit.
- Clear all entries and reset the form.

## Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>

Open the index.html file in your preferred web browser.

Usage
-Enter your daily calorie budget in the "Budget" field.
-Use the dropdown menu to select the type of entry (breakfast, lunch, dinner, snacks, or exercise).
-Click the "Add Entry" button to add food or exercise entries dynamically.
-Fill in the entry name and calories for each added entry.
-Click the "Calculate Remaining Calories" button to see the results.
-Use the "Clear" button to reset the form and start over.

JavaScript Logic
The application logic is implemented in the index.js file. Here's a brief overview of the key functions:

-`addEntry`: Dynamically adds input fields for entry name and calories based on the selected entry type.

-`cleanInputString`: Cleans input strings by removing unwanted characters.

-`isInvalidInput`: Checks if the input contains invalid characters, preventing scientific notation.

-`calculateCalories`: Calculates the remaining calories based on the budget, consumed calories, and exercise calories.

-`getCaloriesFromInputs`: Summarizes the calorie values from a list of input elements.

-`clearForm`: Clears all input fields and resets the form.

Contributing
If you find a bug, have suggestions for improvement, or want to contribute to the project, please feel free to open an issue or submit a pull request. Your contributions are welcome!

License
This project is licensed under the MIT License.
