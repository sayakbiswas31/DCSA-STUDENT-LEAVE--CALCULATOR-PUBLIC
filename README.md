# DCSA-STUDENT-LEAVE--CALCULATOR-PUBLIC

## 🌟 Overview  
The **Student Leave Calculator** is a web-based tool designed for students of the *Department of Computer Science and Applications, Panjab University, Chandigarh*. It helps track and manage attendance by calculating how many lectures a student can miss in a given month while still maintaining the mandatory 75% attendance threshold.

---

## 🚀 Features

- Select **semester**: Odd (July–December) or Even (January–May)  
- Choose a **target month** for leave calculation  
- Input **total lectures delivered** and **lectures attended**  
- Get **real-time calculation** of:
  - Missable lectures
  - Missable days (assuming 6 lectures/day)
  - Remaining lectures
- **Modern UI** using Tailwind CSS with Inter font and gradient background  
- **Institutional branding** with college name and customizable logo support 🌈

---

## 💻 Technologies Used

- **Python** – Core backend logic  
- **Flask** – Lightweight web framework  
- **Tailwind CSS** – Utility-first CSS framework for styling  
- **Inter Font** – Clean, modern typography via Google Fonts  
- **HTML & JavaScript** – Dynamic frontend interactions ⚙️  

---

## 📋 Prerequisites

- Python 3.8 or higher  
- Flask (install via: `pip install Flask==3.0.3`)  

---

## 🎯 Installation

1. **(Optional)** Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **(Optional)** Add a logo:
   - Create a `static/` folder in the project root
   - Place your logo (e.g., `logo.png`) inside it
   - In `app.py`, add:
     ```python
     app.static_folder = 'static'
     ```
   - Update `<img src>` in `index.html` to:
     ```html
     <img src="/static/logo.png">
     ```

---

## 🎮 Usage

1. Run the Flask app:
   ```bash
   python app.py
   ```

2. Open your browser and go to: [http://127.0.0.1:5000](http://127.0.0.1:5000)

3. Use the form to:
   - Select a semester
   - Choose a target month
   - Enter total and attended lectures

4. View the result:
   - Missable lectures
   - Missable days
   - Remaining lectures for the month 📊

---

## 🌐 Live Demo

Try the live version here:  
👉 [https://dcsa-student-leave-calculator.onrender.com](https://dcsa-student-leave-calculator.onrender.com) 🚀  

---

## 📧 Request the Code

Interested in the source code?  
Email: **sayakbiswas@example.com**  
Subject: `"Request for Student Leave Calculator Code"` 😄  

---

## 📞 Contact

- **Email**: sayakbiswas@example.com  
- **Availability**: Mon–Fri, 9 AM – 5 PM IST (subject to change) ⏰  
- **Social**: Follow updates on Instagram: [@sayakbiswas31](https://www.instagram.com/sayakbiswas31) 🚀  

---

## 🗂️ Project Structure

```
project_folder/
├── app.py
├── requirements.txt
├── static/        # (Optional: logo goes here)
│   └── logo.png
└── templates/
    └── index.html
```

---

## 🤝 Contributing

Have ideas or suggestions?  
New feature ideas like leave history tracking or export options are welcome!  
Just drop an email to the address above. 🌟  


---

## 🙌 Acknowledgments

- Built using **Flask** and **Tailwind CSS**  
- Font: *Inter* via Google Fonts  
- Inspired by real-world attendance needs at **Panjab University** 🎓  

