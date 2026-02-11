## 🚀 Live Demo

🔗 **Live Demo:** [https://lithish-s.github.io/CodeAlpha_Calculator/](https://lithish-s.github.io/CodeAlpha_Calculator/)

## 📋 Task Requirements Met

# 🧮 CodeAlpha Scientific Calculator

![Scientific Calculator](https://img.shields.io/badge/CodeAlpha-Calculator-blueviolet)
![HTML5](https://img.shields.io/badge/HTML5-Orange)
![CSS3](https://img.shields.io/badge/CSS3-Blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-6-teal)

A powerful, feature-rich scientific calculator with calculation history, scientific functions, keyboard support, and a sleek dark-themed interface. Built with pure HTML, CSS, and JavaScript as part of the CodeAlpha Frontend Development Internship (Task 2).

### ✅ Core Features (100% Complete)
| Feature | Implementation |
|---------|----------------|
| **Basic Arithmetic** | Addition, subtraction, multiplication, division, percentage |
| **User Interface** | Clean button layout with dual display (expression + result) |
| **Real-time Display** | Shows current input and ongoing expression |
| **Clear Screen** | AC (clear all) and ⌫ (delete last character) |
| **Responsive Design** | Desktop, tablet, and mobile optimized |

### ✅ Bonus Features (100% Complete)
| Bonus Feature | Implementation |
|---------------|----------------|
| **Keyboard Support** | Numbers, operators, Enter, Escape, Backspace, % |
| **Scientific Functions** | x², √x, x^y, sin, cos, tan, log, ln, π |
| **Calculation History** | Persistent storage (localStorage), up to 10 items with timestamps |
| **Error Handling** | Graceful error messages, auto-reset after 1 second |
| **Decimal Precision** | Results rounded to 10 decimal places |
| **Dark Theme** | Modern dark UI with gradient accents |
| **Percentage Calculation** | Direct % operator support |
| **Power Function** | Interactive prompt for exponent input |

## ✨ Key Features

### 🎯 Basic Operations
- **Arithmetic** – Addition (+), subtraction (−), multiplication (×), division (/)
- **Percentage** – Calculate percentages directly (e.g., 200 × 10% = 20)
- **Clear Functions** – C (clear all), ⌫ (delete last character)
- **Decimal Support** – Floating point calculations with `.` button
- **Expression Preview** – Shows ongoing expression above main result

### 🔬 Scientific Functions
| Function | Description | Example |
|----------|-------------|---------|
| **x²** | Square | 5² = 25 |
| **√x** | Square root | √25 = 5 |
| **x^y** | Power (with prompt) | 2³ = 8 |
| **sin** | Sine (degrees) | sin(30) = 0.5 |
| **cos** | Cosine (degrees) | cos(60) = 0.5 |
| **tan** | Tangent (degrees) | tan(45) = 1 |
| **log** | Base-10 logarithm | log(100) = 2 |
| **ln** | Natural logarithm | ln(e) = 1 |
| **π** | Pi constant | π = 3.1415926535 |

### 📊 Calculation History
- **Persistent Storage** – History saved in browser's localStorage
- **Timestamps** – Each entry shows time of calculation
- **Quick Reference** – View last 10 calculations
- **Clear History** – One-click removal with confirmation

### ⌨️ Keyboard Support
| Key | Action |
|-----|--------|
| `0-9` | Number input |
| `+ - * /` | Basic operators |
| `.` | Decimal point |
| `Enter` / `=` | Calculate result |
| `Escape` | Clear all |
| `Backspace` | Delete last character |
| `%` | Percentage |

## 💻 Technologies Used

| Technology | Purpose | Key Features |
|------------|---------|--------------|
| **HTML5** | Structure | Semantic layout, accessibility |
| **CSS3** | Styling | Custom properties, grid, flexbox, animations |
| **JavaScript ES6+** | Logic | Event handling, localStorage, math operations |
| **Bootstrap 5** | Layout | Responsive grid, spacing utilities |
| **Font Awesome 6** | Icons | Back button, history, scientific icons |

## 📱 Responsive Breakpoints

| Device | Layout | Calculator Size | History Panel |
|--------|--------|-----------------|---------------|
| Desktop (>992px) | 2-column (calc + history) | Full | Side-by-side |
| Tablet (768-992px) | 2-column stacked | Compact | Below calculator |
| Mobile (<768px) | 1-column | Full width | Below calculator |

## 🎮 How to Use

### 📖 Basic Usage
1. **Enter numbers** – Click digit buttons or use keyboard number keys
2. **Select operation** – Click +, −, ×, /, or % 
3. **Get result** – Press `=` button or `Enter` key
4. **Clear** – Use `C` (clear all) or `⌫` (delete last character)
5. **View history** – Previous calculations appear in the right panel

### 🔬 Scientific Functions
```javascript
// Single-argument functions (sin, cos, tan, log, ln, √, x²)
1. Enter a number (e.g., 30)
2. Click function button (e.g., "sin")
3. Result appears immediately

// Power function (x^y)
1. Enter base number (e.g., 2)
2. Click "x^y" button
3. Enter exponent in prompt (e.g., 3)
4. Click OK → Result = 8

// Pi constant
Click "π" to insert 3.1415926535
