# Currency Converter

A web-based Currency Converter application that allows users to convert amounts between various currencies. This project utilizes an external currency API for real-time exchange rates and includes country flags for enhanced user experience.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Key Components](#key-components)


## Project Overview
The Currency Converter application provides an easy-to-use interface where users can:
1. Enter an amount to convert.
2. Choose currencies from dropdown menus, with each option displaying a corresponding country flag.
3. Instantly view the conversion result based on current exchange rates.

## Features
- Conversion of any amount between multiple currencies.
- Real-time exchange rate updates via an external API.
- Automatic display of country flags based on the selected currency.
- Intuitive design and responsive layout.

## Technologies Used
- **HTML**: Markup structure.
- **CSS**: Styling and layout.
- **JavaScript**: Logic and API interaction.
- **Font Awesome**: Icons for UI enhancements.
- **Currency API**: Real-time exchange rates.

## Usage
1. **Enter Amount**: Type the amount you want to convert in the "Enter Amount" field.
2. **Select Currencies**:
   - Use the **From** dropdown to select the currency you wish to convert from.
   - Use the **To** dropdown to select the currency you wish to convert to.
3. **View Exchange Rate**: Click the **Get Exchange Rate** button to fetch the latest conversion rate.
4. **Conversion Result**: The converted amount and exchange rate will be displayed in the message box below the dropdowns.

The flags of the selected currencies are displayed next to each dropdown for easy identification.

## Project Structure
- **index.html**: Main HTML file that includes the structure of the Currency Converter, dropdowns, and the result display area.
- **style.css**: CSS file that defines the layout, colors, font styles, and responsive design for the app interface.
- **app.js**: JavaScript file containing the main logic for fetching exchange rates, updating the currency conversion, and dynamically changing country flags.
- **codes.js**: JavaScript file that includes a list of currency codes and their corresponding country codes used to update flags based on currency selection.

## Key Components
- **Dropdown Menus**: Populated with all available currency options, displaying the currency code and updating with a country flag based on selection.
- **Flag Images**: Dynamically updated for each currency selection using an external API for flag images.
- **Conversion Message**: A message area that displays the calculated conversion result in the format `1 [Currency] = X [Currency]`.

