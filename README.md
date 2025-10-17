# Product Total Price Calculator

## Project Overview
This project is a simple yet practical web application that calculates and displays the total price of products listed in a CSV file. The project is designed to be a helpful tool for businesses that need to quickly calculate the total price of their products without the need for complex and cumbersome software or extensive coding knowledge. The application is built using HTML, CSS, and JavaScript, and features a responsive design thanks to Bootstrap 5. One of the main features of this application is its use of modern web technologies to simplify tasks that would traditionally require more complex solutions.

## Requirements
For the application to work correctly, the following requirements need to be satisfied:
- A CSV file named 'products.csv', containing product data, needs to be present in the same directory as the application file.
- The total price of all the products in the CSV file should be displayed in a div with the id 'total-price'.
- Bootstrap 5 should be properly loaded and utilized for a responsive design.

## Installation & Setup
Getting this application up and running is quite straightforward. Since it's a client-side application, there's no need for a server setup. Here's a step-by-step guide:
1. Download or clone the project repository to your local machine.
2. Ensure that you have a modern web browser installed. The application has been tested and works well on the latest versions of Chrome, Firefox, and Safari.
3. Place the products.csv file in the same directory as the index.html file. The CSV file should have product data with price being the third column.
4. Open the index.html file in your web browser to run the application.

## Usage Instructions
Once the application is up and running, you should see the calculated total price of all the products displayed on the screen. The calculation is done automatically when the page loads. If there's an error in fetching or parsing the CSV file, an error message will be displayed instead. Refresh the page to recalculate the total price.

## Technical Details
The application is built using HTML for structure, CSS for styling, and JavaScript for functionality. Bootstrap 5 is used for responsive design. The JavaScript fetch API is used to fetch the CSV file and its contents are parsed and calculated in JavaScript. The total price calculation logic is encapsulated inside a fetch promise, which is triggered when the page loads.

## Troubleshooting
If you face any issues while using the application, here are a few potential solutions:
- Make sure the products.csv file is in the same directory as the index.html file.
- Ensure the CSV file has the correct format, with price as the third column.
- Check your internet connection, as the application needs to fetch Bootstrap 5 from a CDN.
- If you see a CORS error in the browser console, it's due to the browser's security restrictions. To bypass this, you can set up a local server or use a service like GitHub Pages to host the files.

## License
This project is licensed under the MIT License. This means you're free to use, modify, and distribute the application as you see fit, provided you include the original copyright and license notice in any copy of the software/source. The full license text can be found in the LICENSE file in the project repository.