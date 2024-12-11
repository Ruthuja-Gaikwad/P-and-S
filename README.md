# Currency Converter
A simple currency converter web application that allows users to convert currencies based on the latest exchange rates. The application fetches real-time exchange rate data from the open.er-api.com API.
# Features
1. Convert currency from one type to another (e.g., USD to INR, EUR to JPY).
2. Display the real-time exchange rate for selected currencies.
3. Select the base currency and the target currency from a dropdown.
4. Input the amount to be converted.
5. Displays the result with the converted amount.
# Tech Stack
HTML - For structuring the web page.
CSS - For styling the page.
JavaScript - For handling user interactions and fetching data from the API.
open.er-api.com - Used to get real-time currency exchange rates.
# API Used
The currency conversion rates are fetched using the open.er-api.com API. The endpoint used is:
https://open.er-api.com/v6/latest/USD
This API provides real-time exchange rates for multiple currencies based on USD as the base currency.
# How to Use
Clone the repository:
1. git clone https://github.com/Ruthuja-Gaikwad/currency-converter.git
2. Open the index.html file in your browser to view the application.
3. Select the currencies you want to convert between using the dropdown menus.
4. Enter the amount you wish to convert.
5. Click the "Convert" button, and the result will be displayed with the converted amount.
# How It Works
1. Dropdown Menus: The user can select the source (from) and target (to) currencies from the dropdown lists. The currencies are populated dynamically using JavaScript.
2. Amount Input: Users input the amount they wish to convert, and the system will calculate the equivalent amount in the selected target currency.
3. Exchange Rate API: The app fetches the latest exchange rates from the API (https://open.er-api.com/v6/latest/USD), which returns the rates for multiple currencies in relation to USD.
4. Conversion Calculation: The selected amount is multiplied by the exchange rate for the selected target currency to get the converted amount.
