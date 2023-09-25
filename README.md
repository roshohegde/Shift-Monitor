# Employee Shifts Web Application
## Overview
The Employee Shifts Web Application is a simple web page that displays employee schedules based on their shifts. It provides real-time information about which employees are currently working in the morning, evening, and night shifts. This application also considers weekends and employee leave status to display accurate schedules.

## Features
Displays the current date and time.
Automatically determines the current shift (morning, evening, or night) based on the time of day.
Filters and displays only those employees who are scheduled for the current shift, taking into account weekends and leave status.
Provides a clean and organized presentation of employee schedules in separate columns for each shift.
Uniformly resizes employee images for a consistent and appealing display.
Screenshots
Screenshot

## Installation
    1. Clone this repository to your local machine:

        git clone https://github.com/roshohegde/shift-monitor.git

    2. Navigate to the project directory:

        cd shift-monitor

    3. Open the index.html file in your preferred web browser.

## Usage
The web application displays the current date and time at the top.
Below the date and time, you will find employee schedules for the morning, evening, and night shifts.
Employee cards include their name, an image (if available), and weekend days.
Employees who are on leave or have weekend shifts that include the current day will not be displayed in the schedule for the current shift.
Customization
You can customize the employee data and images by modifying the JavaScript code in the index.html file. Simply update the employees array with your own data and make sure to provide valid image file paths.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Akshay Hegde