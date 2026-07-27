# Temperature Converter

A responsive and user-friendly **Temperature Converter** built using **HTML, CSS, and JavaScript**. This application allows users to quickly convert temperatures between **Celsius (°C)**, **Fahrenheit (°F)**, and **Kelvin (K)**. It features real-time conversion, input validation, and an interactive thermometer that visually represents the temperature.

## Features

- Convert temperatures between:
  - Celsius (°C)
  - Fahrenheit (°F)
  - Kelvin (K)
- Real-time conversion while typing
- Interactive thermometer display
- Highlights the selected input unit
- Displays clear error messages for invalid input
- Prevents values below absolute zero
- Responsive design for desktop, tablet, and mobile devices
- Clean and modern instrument-panel inspired interface

## Technologies Used

- **HTML5** – Structure of the application
- **CSS3** – Styling, responsive layout, and animations
- **JavaScript (ES6)** – Conversion logic, validation, and dynamic updates

## Project Structure

```
Temperature-Converter/
│── index.html
└── README.md
```

## How It Works

1. Enter a temperature value in the input field.
2. Select the unit (Celsius, Fahrenheit, or Kelvin).
3. The application automatically converts the value into the other two units.
4. The thermometer updates based on the equivalent Celsius temperature.
5. Invalid inputs or temperatures below absolute zero display an error message.

## Temperature Conversion Formulas

### Celsius to Fahrenheit

```
°F = (°C × 9/5) + 32
```

### Fahrenheit to Celsius

```
°C = (°F − 32) × 5/9
```

### Celsius to Kelvin

```
K = °C + 273.15
```

### Kelvin to Celsius

```
°C = K − 273.15
```

## Input Validation

The application validates user input by:

- Accepting only valid numeric values
- Allowing decimal numbers and negative values where applicable
- Rejecting invalid characters
- Preventing temperatures below absolute zero:
  - **−273.15 °C**
  - **−459.67 °F**
  - **0 K**

## Responsive Design

The interface is designed to work smoothly across different screen sizes, including:

- Desktop
- Laptop
- Tablet
- Mobile devices

## How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Double-click **index.html** or open it in any modern web browser.
4. Start converting temperatures instantly.

No installation or external libraries are required.

## Browser Compatibility

This project works on all modern browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

## Future Improvements

- Dark/Light theme switch
- Temperature conversion history
- Copy results to clipboard
- Additional temperature scales
- Progressive Web App (PWA) support
- Improved accessibility features

## License

This project is open source and available for learning, personal use, and further development.

## Author

Developed using **HTML**, **CSS**, and **JavaScript** to demonstrate temperature conversion with a modern, responsive, and interactive user interface.