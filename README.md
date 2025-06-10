Digital clock
A real-time digital clock displaying hours, minutes, seconds, and AM/PM, crafted with HTML, CSS, and JavaScript.
A sleek, real-time digital clock displaying hours, minutes, seconds, and AM/PM, built with HTML, CSS, and JavaScript.
This project presents a simple yet elegant digital clock application that accurately displays the current time. It's a fantastic demonstration of how foundational web technologies—HTML for structure, CSS for styling, and JavaScript for dynamic functionality—can be combined to create practical and visually appealing web components.
##Features
Real-time Display: Continuously updates to show the current hour, minute, and second.
12-Hour Format: Displays time in the standard 12-hour format (e.g., 03:45:20 PM).
AM/PM Indicator: Clearly shows whether the time is AM or PM.
Responsive Design: Adapts gracefully to different screen sizes, ensuring a good look on both desktop and mobile devices.
Clean & Modern UI: Features a minimalist and easy-to-read design, making the time instantly legible.
Zero Dependencies: Built purely with vanilla HTML, CSS, and JavaScript, ensuring a lightweight and efficient application.
##Technologies Used
HTML5: Provides the semantic structure for the clock's display elements, such as containers for hours, minutes, seconds, and the AM/PM indicator.
CSS3: Styles the digital clock, giving it its aesthetic appeal. This includes typography, spacing, background colors, and responsive adjustments for various screen sizes.
JavaScript: The core of the clock's functionality. JavaScript is responsible for:
Fetching the current time from the user's system.
Formatting the time into the desired 12-hour format with leading zeros.
Updating the display elements in real-time, typically using setInterval().
##How It Works
The digital clock's functionality is primarily driven by JavaScript. Upon page load, a JavaScript function is executed that retrieves the current Date object. From this object, it extracts the current hours, minutes, and seconds. These values are then formatted to ensure a consistent two-digit display and to determine the AM/PM status.

