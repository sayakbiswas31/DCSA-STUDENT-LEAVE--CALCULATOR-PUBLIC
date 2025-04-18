# DCSA-STUDENT-LEAVE--CALCULATOR-PUBLIC

Student Leave Calculator 🎉
Overview 🌟
The Student Leave Calculator is a web-based application designed to help students at the Department of Computer Science and Application, Panjab University, Chandigarh, track and manage their attendance. It calculates the number of lectures a student can miss in a given month while maintaining the required 75% attendance, based on the total lectures delivered and attended. 😊
Features 🚀

Select semester (Odd: July-December, Even: January-May).
Choose a target month for leave calculation.
Input total lectures delivered and attended.
Real-time calculation of missable lectures and days (assuming 6 lectures per day).
Display remaining lectures for the selected month.
Professional UI with Tailwind CSS, Inter font, and a custom gradient background.
Institutional branding with a placeholder logo and college name. 🌈

Technology Used 💻

Python: Core programming language for the backend.
Flask: Lightweight web framework to serve the application.
Tailwind CSS: CSS framework for a responsive and modern UI.
Inter Font: Google Fonts typography for a clean look.
HTML/JavaScript: Frontend structure and dynamic calculations. ⚙️

Prerequisites 📋

Python 3.8 or later.
Flask (pip install Flask==3.0.3).

Installation 🎯

Create a virtual environment (optional but recommended):python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install dependencies:pip install -r requirements.txt


(Optional) Add a logo:
Create a static folder in the project root.
Place your logo (e.g., logo.png) in static/.
Update app.py with app.static_folder = 'static' and change the <img src> in index.html to /static/logo.png.



Usage 🎮

Run the Flask application:python app.py


Open a browser and navigate to http://127.0.0.1:5000/.
Use the form to:
Select a semester.
Choose a target month.
Enter the total lectures delivered and attended.


View the calculated result, which shows missable lectures, days, and remaining lectures. 📊

View Live Page 🌐
Experience the Student Leave Calculator live by clicking the button below to open the hosted version:Visit Live Page 🚀
If You Want the Code 📧
If you’re interested in the code, please send an email to sayakbiswas@example.com with the subject "Request for Student Leave Calculator Code" to receive the full source files. 😄
Contact 📞
For inquiries, support, or collaboration, feel free to reach out:

Email: sayakbiswas@example.com 🌐
Availability: Monday to Friday, 9 AM - 5 PM IST (subject to change) ⏰
Social: Follow updates on X via @SayakBiswasDev 🚀

Project Structure 🗂️
project_folder/
├── app.py
├── requirements.txt
├── static/  (optional)
│   └── logo.png
└── templates/
    └── index.html

Contributing 🤝
Feel free to suggest improvements or new features (e.g., leave history, export options) by emailing the above address! 🌟


Built with Flask and Tailwind CSS.
Font: Inter from Google Fonts.
Inspired by attendance management needs at Panjab University. 🎓

