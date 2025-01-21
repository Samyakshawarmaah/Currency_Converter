# Currency Converter

A simple web-based currency converter application that allows users to convert amounts between various currencies using live exchange rates.

---

## Features
- **Live Exchange Rates**: Fetches real-time exchange rates from an API.
- **User-Friendly Interface**: Easy-to-use dropdown menus to select currencies.
- **Dynamic Conversion**: Converts entered amounts instantly.
- **Responsive Design**: Works across various devices with a Bootstrap-based layout.

---

## Installation and Setup

1. Clone the repository or download the source files.
    ```bash
    git clone https://github.com/your-username/currency-converter.git
    ```
2. Navigate to the project directory.
    ```bash
    cd currency-converter
    ```
3. Open the `index.html` file in a browser to run the application.

---

## Technologies Used

### Frontend
- **HTML5**: Markup for the structure of the app.
- **CSS3**: Styling, including Bootstrap for responsiveness.
- **JavaScript**: Logic for fetching exchange rates and performing calculations.
- **Google Fonts**: Custom fonts for an elegant UI.

### External Libraries
- **Bootstrap**: For responsive design.
- **jQuery**: Simplified DOM manipulation.
- **Popper.js**: Required for Bootstrap functionalities.

### API
- **Exchange Rate API**: Fetches real-time exchange rates. URL: `https://api.exchangerate-api.com/v4/latest/USD`

---

## Usage

1. Open the application in your browser.
2. Enter the amount you want to convert in the input field.
3. Select the currencies you want to convert from and to using the dropdown menus.
4. Click the `Convert` button to see the converted amount.
5. Use the `Reset` button to clear values and start over.

---

## File Structure

```plaintext
Currency-Converter/
│
├── index.html         # Main HTML file
├── style.css          # Custom CSS styles
├── script.js          # JavaScript for functionality
├── README.md          # Project documentation
└── assets/            # Optional: Place for additional assets (e.g., images)


## License
This project is open-source and available under the MIT License.