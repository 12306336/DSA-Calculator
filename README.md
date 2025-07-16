# 🧠 DSA-Powered Smart Expression Calculator

## Project Overview
An advanced, interactive calculator web app that solves mathematical expressions, explains each step, and visualizes DSA concepts (stack, tree, recursion). Calculation history is stored in the browser (localStorage). No authentication or database required.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Backend:** Flask (Python)
- **Storage:** Browser localStorage
- **Optional:** Chart.js for graph/tree visualization

## Features
- Smart expression input (parentheses, decimals, negatives)
- Infix to postfix conversion (stack-based)
- Postfix evaluation with step-by-step stack operations
- Expression tree visualization (optional)
- Calculation history (localStorage, last 10–20 calculations)
- Error detection (syntax, divide-by-zero)
- Light/Dark theme toggle
- Scientific functions (sin, cos, log, sqrt, etc.)
- Graph plotting (optional)

## File Structure
```
smart-calculator/
├── templates/
│   └── index.html
├── static/
│   ├── css/style.css
│   └── js/script.js
├── app.py
├── utils/
│   ├── parser.py
│   └── evaluator.py
├── README.md
└── requirements.txt
```

## Usage
1. Run the Flask backend: `python app.py`
2. Open the app in your browser.
3. Enter expressions, view step-by-step solutions, and see your calculation history.

---

**This project is designed for learning, DSA demonstration, and easy extension.**
 
> Today, I’m excited to present my project: a DSA-powered Smart Calculator web app.
Problem & Motivation:
> Traditional calculators are limited—they only compute results, with no insight into the process or underlying logic.
> My goal was to build a modern calculator that not only solves expressions, but also teaches and visualizes the data structures and algorithms (DSA) behind the scenes.
Key Features:
> - Step-by-step Evaluation:
> The app shows how each expression is processed, using stack-based infix-to-postfix conversion and evaluation.
>
> - Expression Tree Visualization:
> It builds and displays the expression tree, helping users understand how complex expressions are parsed and solved.
>
> - Graph Plotting:
> Users can plot mathematical functions, including inequalities, with interactive zoom and pan.
>
> - Advanced Math:
> The calculator supports matrices, complex numbers, equation solving, and variable assignment.
>
> - Modern UI:
> The interface is responsive, mobile-friendly, and visually appealing, with theme options and quick-access features like voice input and formula bank.
Tech Stack:
> - Backend: Python Flask, using DSA concepts like stacks, trees, and recursion for parsing and evaluation.
> - Frontend: HTML, Tailwind CSS, and JavaScript for interactivity and visualization.
> - Libraries: NumPy for matrices, SymPy for symbolic math, Chart.js for graphing.
Demo/Walkthrough:
> Here’s a quick walkthrough:
> - Enter an expression, and see the result, step-by-step stack operations, and the expression tree.
> - Switch to the graph panel to plot functions.
> - Use the matrix and complex number calculators for advanced operations.
> - All actions are logged in history, and variables can be assigned and reused.
Impact & Learning:
> This project not only helps users calculate, but also learn how algorithms and data structures work in real time.
> It’s a great educational tool for students and anyone interested in the logic behind calculators.
