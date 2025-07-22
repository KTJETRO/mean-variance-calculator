
# Mean-Variance-Standard Deviation Calculator

This project calculates the **mean**, **variance**, **standard deviation**, **maximum**, **minimum**, and **sum** of a 3×3 matrix using **NumPy** in Python.

It was built as part of the [freeCodeCamp Data Analysis with Python Projects](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/mean-variance-standard-deviation-calculator) certification.

---

## How It Works

- The program defines a function named `calculate()` inside `mean_var_std.py`.
- It accepts a list of **9 numerical values**.
- The list is reshaped into a **3×3 NumPy matrix**.
- It returns a dictionary with the **mean**, **variance**, **standard deviation**, **maximum**, **minimum**, and **sum**:
  - across columns (`axis=0`)
  - across rows (`axis=1`)
  - for all elements combined (flattened)

---

## 🔁 Example

```python
from mean_var_std import calculate

result = calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])
print(result)
```

---

## Output

```python
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [[6.0, 6.0, 6.0], [0.666..., 0.666..., 0.666...], 6.666...],
  'standard deviation': [[2.44..., 2.44..., 2.44...], [0.81..., 0.81..., 0.81...], 2.58...],
  'max': [[6, 7, 8], [2, 5, 8], 8],
  'min': [[0, 1, 2], [0, 3, 6], 0],
  'sum': [[9, 12, 15], [3, 12, 21], 36]
}
```

---

## Project Structure

```
📁 mean-variance-calculator
├── mean_var_std.py       # Main logic (calculate() function)
├── main.py               # Manual testing script
├── test_module.py        # Auto test cases for freeCodeCamp
└── README.md             # Project description (this file)
```

---

## How to Run the Project

In Gitpod or your terminal:

```bash
python3 main.py
```

---

## To Run the Test Cases and Validate the Solution

```bash
python3 -m unittest test_module.py
```

You should see output like:

```
...
----------------------------------------------------------------------
Ran 3 tests in 0.001s

OK
```

---

## License

This project is licensed under the **MIT License**, meaning it's open for anyone to use, modify, and share.

---

## Author

Kelvin Tinashe Chada  
[https://github.com/KTJETRO](https://github.com/KTJETRO)

---

## Learn More

This project is part of the freeCodeCamp: Data Analysis with Python Certification.

Explore more projects and challenges to improve your Python + data skills!

---

## ⚠️ Disclaimer

> This project was developed as part of the [freeCodeCamp Data Analysis with Python certification](https://www.freecodecamp.org/learn/data-analysis-with-python/).  
> I do **not claim ownership** of the original project idea or instructions.  
> This repository contains **my solution only**, written for educational purposes.
