# 💰 Smart Loan Calculator

A modern, responsive web application built with vanilla JavaScript that calculates loan repayments with real-time accuracy and smooth number animations.

![Project Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)

## 📖 Description

The **Smart Loan Calculator** is a lightweight tool designed to help users estimate their monthly loan payments, total repayment amounts, and total interest accrued over time. It features a clean, glassmorphism-inspired UI and handles mathematical computations instantly on the client side.

## ✨ Features

- **💸 Amortization Calculation**: Uses standard financial formulas to calculate monthly installments.
- **⚡ Smooth Animations**: Custom JavaScript implementation to animate numerical results from 0 to the final value.
- **📱 Fully Responsive**: Built with CSS Grid and Flexbox to work seamlessly on mobile and desktop.
- **🛡️ Input Validation**: Prevents calculation errors by validating user inputs (NaN and Infinity checks).
- **🎨 Modern UI**: Features a dark-themed gradient background with a glass-effect container.

## 🛠️ Technologies Used

- **HTML5**: Semantic structure.
- **CSS3**: Custom variables, Flexbox, Grid, and Media Queries for responsiveness.
- **JavaScript (ES6+)**: DOM manipulation, event handling, and mathematical logic.

## 🧮 How It Works

The application uses the standard Loan Amortization formula to calculate the monthly payment:

$$M = P \frac{r(1+r)^n}{(1+r)^n - 1}$$

Where:
- **M** = Monthly Payment
- **P** = Principal Loan Amount
- **r** = Monthly Interest Rate (Annual Rate / 12)
- **n** = Number of Payments (Loan Term in Years × 12)

### The Animation Logic
Instead of snapping directly to the result, the application uses a custom `animateValue` function utilizing `requestAnimationFrame` to increment the numbers smoothly over 1000ms, providing a polished user experience.

## 🚀 Getting Started

To run this project locally, simply clone the repository and open the HTML file.

1. **Clone the repository**
   ```bash
   git clone [https://github.com/your-username/smart-loan-calculator.git](https://github.com/your-username/smart-loan-calculator.git)
2. **Navigate to the project directory** 
   ```bash
   cd smart-loan-calculator
3. **Open index.html file in your preferred web browser (Chrome, Firefox, Edge, etc.).**


