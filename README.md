# Currency-monitor
Application to monitor currencies and gold prices.
   
## Table of Contents
* [General info](#general-info)
* [Installation](#installation)
* [Example of Use](#example-of-use)
* [Technologies](#technologies)
* [Useful Resources](#useful-resources)


## General Info
With this application you can track the current value of gold and countries' currencies. Additional app provides currency calculator and graphs plotter (for currencies and gold). 
This application is the easiest way to keep up with prices and better understand currencies trading rules.


https://github.com/KrzysztofLin/currency-monitor/assets/102530541/62a99a87-9f1c-4c0f-88a5-77baf0d21ae9



## Installation
To install and run the app on your mobile device, follow these steps:
1. Clone the repository to your local machine
2. Enter directory with cloned repository
3. Type 'npm install'
4. Download Expo Go application to your smarthphone.
5. Asure that your smartphone is in the same network as your computer (for example enable LTE-internet and network sharing from smarthone) 
5. Start the app using 'npx expo start'.
6. Scan the QR code and wait for application boundling.
7. After boundling use App!

## Example of use:
### Gold View
   Visualization of the gold price chart. Chart displays historical gold values over the past 255 days and today's current price. The current gold price is shown in bold text at the top of the chart. Information about gold prices is fetch from NBP API.
![1_5](https://github.com/KrzysztofLin/currency-monitor/assets/102530541/c6e1484a-58c6-4515-8a31-5020d30bd19a)



### Currency
View in which users can convert an amount of cash from złoty to a selected currency. The user enters the amount of cash they want to convert into a text input field. Once the user has selected a currency, the app will convert the amount of cash they entered into the selected currency and display the result on the screen.

In addition to the currency conversion, the app also displays a chart of the currency prices over the past 30 days. This chart provides users with a visual representation of the currency's recent performance, which can help them make informed decisions about their transactions.

Overall, this view provides users with a convenient and informative way to convert currencies and track their performance over time.

![1_3](https://github.com/KrzysztofLin/currency-monitor/assets/102530541/85e87e3c-d8c3-48ce-acbb-db31a8ac464b)


### Currency Calculator
Screenshot of the currency calculator feature in my app, allowing users to quickly convert cash between different currencies. The calculator has two picker fields, one for selecting the initial currency and another for selecting the target currency. The user can then enter the desired amount of cash to convert in the input field below. The app instantly calculates the converted amount and displays it on the screen. This feature is ideal for users who frequently travel abroad or engage in international transactions.

![1_2](https://github.com/KrzysztofLin/currency-monitor/assets/102530541/7f11b8bc-644a-47bd-b8d2-51343bd5c88b)


### Currency List
Screenshot of the currency list feature in my app, displaying a flatlist of currencies with their respective codes, prices, and flags of the countries they represent. The data for the prices is fetched in real-time from the NBP API, ensuring that users always have access to the most up-to-date information. Users can tap on any of the currencies in the list to view a detailed description of that currency. This feature is useful for anyone looking to stay up-to-date on the latest currency exchange rates or make international transactions.

![1_1](https://github.com/KrzysztofLin/currency-monitor/assets/102530541/01810852-7fd1-45f6-a4d3-16ee8e37f90f)


### Drawer Navigation
The drawer navigation menu is accessible by swiping right from the left edge of the screen. Each page can be selected by tapping its corresponding icon in the drawer navigation menu, making it easy for users to switch between different features and functionalities in the app.

The screenshot shows the drawer navigation feature in my app, which provides easy access to three different pages: the currency list, the currency calculator, and the gold view. 

![1_4](https://github.com/KrzysztofLin/currency-monitor/assets/102530541/3706d2d0-9d6a-452f-91c7-572f1df45955)


## Technologies
* React Native
* JavaScript
* Node.js

## Useful Resources
In project was used many external libraries such as:
* react-native-wagmi-charts
(https://www.npmjs.com/package/react-native-wagmi-charts#interactive-cursors)
* react-native-country-flag
(https://www.npmjs.com/package/react-native-country-flag)
* react-native-picker
(https://github.com/react-native-picker/picker)
* Source of data for my application - NBP API
(http://api.nbp.pl)
