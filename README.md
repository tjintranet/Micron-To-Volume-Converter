# Micron to Volume Converter

A simple, responsive web application that converts paper thickness in microns to paper volume based on grammage (GSM).

![Micron to Volume Converter Screenshot](screenshot.jpg)

## Overview

This web application helps publishers, printers, and paper industry professionals quickly calculate paper volume from thickness measurements. The tool uses the standard formula:

```
Paper Volume = (Microns / Grammage) * 10
```

The result is displayed with one decimal place for precision.

## Features

- **Simple Interface**: Clean, intuitive user interface built with Bootstrap 5
- **Real-time Calculation**: Results update automatically as values are entered
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Copy Function**: One-click copying of calculation results
- **Form Validation**: Ensures proper numerical inputs
- **Accessibility-Friendly**: Proper labeling and contrast for better accessibility

## How to Use

1. Enter the paper thickness in microns
2. Enter the paper grammage (GSM)
3. View the calculated paper volume result
4. Use the "Copy to Clipboard" button to copy the detailed results
5. Use "Clear Fields" to reset the calculator

## Installation

This is a client-side web application with no server dependencies. To use:

1. Download the HTML file
2. Open it in any modern web browser
3. No installation or internet connection required after initial download

### Direct Deployment

Simply open the HTML file in a web browser. No server setup required.

### Server Deployment

To serve the application from a web server:

1. Place the HTML file in your web server's public directory
2. Access it via the appropriate URL

## Technical Details

- **HTML5**: Semantic markup for better accessibility and SEO
- **CSS3**: Custom styling with Bootstrap 5 integration
- **JavaScript**: Vanilla JS for calculations and UI interactions
- **Bootstrap 5**: For responsive layout and UI components
- **No Dependencies**: No backend requirements or API connections

## Application Logic

The calculator performs the following steps:

1. Captures user input for paper thickness (microns) and grammage (GSM)
2. Validates inputs to ensure they are positive numbers
3. Calculates the volume using the formula: (Microns / Grammage) * 10
4. Displays the result formatted to one decimal place
5. Enables copying of formatted results to clipboard

## Industry Use

This calculator is useful for:

- Paper manufacturers specifying paper characteristics
- Printers selecting appropriate paper for projects
- Publishers determining paper volume for book production
- Print buyers comparing paper specifications

## Browser Compatibility

Tested and compatible with:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Opera 76+

## License

This project is available under the MIT License. Feel free to modify and use in your own projects.

## Acknowledgments

- Built with Bootstrap 5 framework
- Inspired by the Book Spine Calculator tool

---

Created by [Your Name/Company]