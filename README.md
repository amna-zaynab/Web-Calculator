# Web Calculator

A sleek, minimalist web calculator built using Flask for backend routing, and handcrafted HTML, CSS, and JavaScript for the frontend. This app allows users to perform basic arithmetic operations with a clean, responsive interface.

---

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, division, and percentage
- Clear (C), backspace (⌫), and decimal support
- Responsive, modern UI designed with pure CSS
- Server runs on Flask, serving a simple frontend with all calculations handled client-side
- Graceful error handling for invalid expressions

---

## Demo

<img width="313" height="471" alt="image" src="https://github.com/user-attachments/assets/0e29e26b-d9d0-4a48-81ba-68395e66c087" />

---

## Technologies Used

- **Flask** - Lightweight Python web framework  
- **HTML5** - Markup structure  
- **CSS3** - Styling with grid layout and modern design  
- **JavaScript** - Client-side interaction and calculation logic  

---

## Getting Started

### Prerequisites

- Python 3.x installed on your machine  
- Flask installed (if not, install via pip)

### Installation & Running

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/flask-web-calculator.git
   cd flask-web-calculator

2. Install Flask:
   pip install flask
   
3. Run the Flask app:
   python app.py

4. Open your browser and navigate to:
   http://localhost:5000

5. Start calculating!

# Project Structure
```
flask-web-calculator/
│
├── app.py              # Flask application
├── templates/
│   └── index.html      # HTML template served by Flask
├── static/
│   └── style.css       # CSS styles
└── README.md           # Project documentation
```

# How It Works

- Flask serves the HTML page with the calculator UI.
- All arithmetic operations and interactions are handled client-side using JavaScript.
- The calculator supports chaining operations and handles common errors like division by zero.
- The design uses CSS Grid for the button layout and modern styling for a smooth user experience.

### Website Link:  
https://calculator-l6da.onrender.com
