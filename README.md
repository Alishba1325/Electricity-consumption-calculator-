Electricity Consumption Calculator
📌 Project Overview

The Electricity Consumption Calculator is a web-based application designed to calculate total electricity consumption based on user-input devices, their quantity, power capacity, and daily operating hours.
The application provides real-time calculation and an option to print the final consumption report.

This project is suitable for academic use, household energy estimation, and frontend logic demonstration.

🎯 Objectives

Calculate electricity consumption for multiple devices

Provide real-time results for each device

Display total consumption and consumption with efficiency loss

Offer a clean, responsive, and printable interface

🛠 Technologies Used

HTML5 – Structure of the application

CSS3 & Bootstrap 3 – Styling and responsive layout

JavaScript (jQuery) – DOM manipulation

Knockout.js – MVVM data binding and real-time calculations

Font Awesome – Icons

📊 Application Features

Add multiple electrical devices dynamically

Input:

Device name

Quantity

Power capacity (Watts)

Daily operating hours

Automatic per-device consumption calculation

Displays:

Total electricity consumption

Total consumption with loss of efficiency

Print-friendly output using CSS print media query

Responsive design for desktop and mobile

⚙️ How It Works

For each device, electricity consumption is calculated using:

Consumption = Quantity × Power (W) × Daily Operating Hours


The total consumption is the sum of all individual device consumptions.
An additional value is calculated by considering loss of efficiency.

📁 Project Structure
Electricity-Consumption-Calculator/
│
├── index.html
├── style/
│   └── main.css
├── js/
│   └── main.js
├── lib/
│   ├── knockout-3.4.2.js
│   └── font-awesome/
└── README.md

🚀 How to Run the Project

Download or clone the repository

Open index.html in any modern web browser

Enter device details

View instant electricity consumption results

Click Print to generate a printable report

🖨 Print Support

The project includes a print-optimized layout using CSS @media print, ensuring:

Only relevant calculation data is printed

Buttons and icons are hidden

Proper alignment and width for reports

🔮 Future Enhancements

Add monthly and yearly consumption calculation

Convert Watts to kWh automatically

Add electricity cost estimation

Store data using local storage or database

Upgrade UI using modern Bootstrap / React

👩‍💻 Author

Alishba Jawaid
Frontend Developer | Data Analyst
HTML | CSS | JavaScript |
