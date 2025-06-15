# 🌡️ Temperature Converter Web App
This project is a responsive and interactive temperature conversion tool built using HTML, CSS (Bootstrap), JavaScript, and jQuery. It allows users to convert temperature values between Celsius, Fahrenheit, and Kelvin instantly with real-time updates.

# 🌐 Live Demo
https://convert-temperaturee.netlify.app/

# 📌 Features
Input temperature in Celsius (°C), Fahrenheit (°F), or Kelvin (K)

Convert to any of the other two units

Real-time conversion as you type or change selection

Responsive layout with clean UI using Bootstrap 4.6

No page reload — handled entirely on the client side

# 🧱 Project Structure
├── index.html        # Main HTML file containing structure and layout

├── style.css         # (Optional) Custom styles if provided separately

├── script.js         # JavaScript for all interactive logic and conversions

├── output.png        # Screenshot of the app (used in documentation or repo)

├── assets/

│   └── icon.png      # Favicon

│   └── right.svg     # Icon used in the convert button

└── README.md         # Project documentation (optional basic version included)

# ⚙️ How It Works
User Input: User enters a numeric value and selects the input temperature unit.

Select Output Unit: Choose the desired conversion unit (°C, °F, or K).

Live Conversion: The converted result is displayed instantly below using proper formulas depending on the selected input/output combination.

# 🔢 Conversion Logic
The application supports:

Celsius ↔ Fahrenheit

Celsius ↔ Kelvin

Fahrenheit ↔ Kelvin

Conversions are handled using standard formulas in script.js, with functions:

cTo() – Celsius to others

fTo() – Fahrenheit to others

kTo() – Kelvin to others

Each function returns a precise value rounded to two decimal places.

# 🚀 Technologies Used
HTML5 – For semantic structure

CSS3 / Bootstrap 4.6 – For responsive design and styling

JavaScript & jQuery – For logic and interactivity

# 📦 Deployment
This project is fully static and can be deployed on platforms like:

Netlify

GitHub Pages

Vercel

# 🧾 License
This project is open-source and available under the MIT License.


