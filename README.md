# 🧮 Advanced Python Scientific Calculator

This is a multi-purpose scientific calculator developed using Python. It supports a wide range of mathematical computations such as:

### 🧠 Features

- 📐 Basic arithmetic operations: addition, subtraction, multiplication, division, and powers
- 📊 Linear algebra: matrix operations, solving linear systems
- 📈 Differential equations solver
- 📏 Trigonometric functions: sin, cos, tan
- 🔁 Inverse trigonometric functions: asin, acos, atan
- 🧮 Logarithmic and exponential functions: log, ln, exp

---

### ⚙ Technologies Used

- Python 3.x  
- math library  
- sympy  
- numpy (for matrix operations)  

---

### 🧪 Example Usage

```python
# Solve a differential equation
from sympy import symbols, Function, dsolve, Eq
x = symbols('x')
y = Function('y')
solution = dsolve(Eq(y(x).diff(x), y(x)), y(x))
print(solution)
📚 How to Run
	1.	Clone the repository:
git clone https://github.com/your_username/advanced-python-calculator.git
cd advanced-python-calculator
Install required libraries:
numpy
👨‍💻 Author
	•	Rayan Ayman Shihab
Student at Applied Science University – Robotics & AI Engineer in the making 🤖💡

⸻

📌 Notes

This calculator was originally developed as part of a university project and has grown into a handy tool for solving many advanced mathematical problems with ease.
