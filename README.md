# Word Color Finder

The aim of this project is to create a front-end web application with a responsive UI. When given a word as input, it provides a list of colors related to that word.

## Technologies Used

- HTML
- CSS
- JavaScript

## Dependencies

- [Poppins Font](https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap)

## How It Works

1. The user enters a word in the input field and clicks the "Search" button.
2. The JavaScript code fetches color details from the [color-name-list API](https://unpkg.com/color-name-list/dist/colornames.json) in JSON format.
3. It filters the colors based on the input word (case-insensitive) and dynamically generates color cards with their corresponding hex values.
4. The color cards are displayed in the UI.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository

2. Open `app.html` in your preferred web browser.

## Project Structure

- `style.css`: Contains the CSS code for styling the application.
- `app.js`: Contains the JavaScript code for fetching color data and dynamically generating color cards.
- `app.html`: The main HTML file that contains the structure of the web application.


