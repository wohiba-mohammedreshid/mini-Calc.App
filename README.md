# 🧮 Pro Scientific Calculator

A sleek, high-performance **Scientific Calculator** built with modern web technologies. This application features a premium "Glassmorphism" interface, persistent calculation history, and full PWA (Progressive Web App) support.

## ✨ Features

* **Scientific Suite:** Support for Trigonometry (`sin`, `cos`, `tan`), `log`, `sqrt`, and exponents (`xʸ`).
* **Persistent History:** Tracks your last 10 calculations using browser `localStorage`.
* **Dual Mode Logic:** Toggle between **Degrees (DEG)** and **Radians (RAD)** for precise trigonometric results.
* **Smart Parsing:** * Automatic closing of unclosed parentheses.
    * Decimal precision limited to 8 places to prevent floating-point errors.
    * Real-time equation preview.
* **Premium UI:** macOS-style window controls, dark mode aesthetic, and responsive grid layout.
* **PWA Ready:** Manifest and Service Worker integration for offline use and "Install to Home Screen" capability.

## 🚀 Quick Start

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/pro-scientific-calculator.git](https://github.com/your-username/pro-scientific-calculator.git)
    ```
2.  **Open the App**
    Simply open `index.html` in any modern web browser.

## 🛠️ Built With

* **HTML5** - Semantic structure.
* **CSS3** - Custom variables, Flexbox, and CSS Grid.
* **JavaScript (Vanilla)** - Core calculation logic and history management.

## 📂 File Structure

* `index.html` - The core application (UI & Logic).
* `manifest.json` - PWA configuration for mobile/desktop installation.
* `sw.js` - Service Worker for offline caching (highly recommended to add).

## 📝 Usage Notes

* **AC:** Clears the entire display and equation history.
* **⌫:** Removes the last character entered.
* **History:** Click the "History" button to slide down a log of your recent calculations.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
