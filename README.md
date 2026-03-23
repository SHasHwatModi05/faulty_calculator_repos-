# 🧮 Faulty Calculator

A lightweight and fun JavaScript-based calculator that intentionally produces incorrect results at random intervals. This project demonstrates the use of randomness, dynamic evaluation, and basic user interaction in JavaScript.

---

## 🚀 Live Demo

🔗 https://your-username.github.io/faulty-calculator/

> Replace the above link with your deployed GitHub Pages URL

---

## 📌 Overview

The Faulty Calculator behaves like a normal calculator most of the time, but occasionally returns incorrect results by modifying the operator behind the scenes. This introduces a playful twist to standard arithmetic operations.

---

## ⚙️ Features

* Accepts user input via `prompt()`
* Supports basic arithmetic operations:

  * Addition (`+`)
  * Subtraction (`-`)
  * Multiplication (`*`)
  * Division (`/`)
* 80% probability of correct calculation
* 20% probability of incorrect calculation (intentional fault)
* Uses JavaScript's `Math.random()` for randomness

---

## 🧠 Working Logic

* A random number between `0` and `1` is generated.
* If the value is greater than `0.2`, the calculator works normally.
* Otherwise, the operator is replaced using a predefined mapping:

```js
{
"+": "-",
"*": "+",
"-": "/",
"/": "**"
}
```

* The calculation is then executed using the `eval()` function.

---

## 🛠️ Tech Stack

* HTML5
* Vanilla JavaScript

---

## 📂 Project Structure

```
Faulty-Calculator/
│── index.html
│── index.js
│── README.md
```


---

## ⭐ Acknowledgement

If you found this project interesting, consider giving it a star ⭐ on GitHub.
