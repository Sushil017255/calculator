# 🧮 Calculator App

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> A sleek and functional calculator built with vanilla HTML, CSS, and JavaScript

## ✨ Features

- **🔢 Basic Operations**: Addition, subtraction, multiplication, and division
- **📱 Responsive Design**: Works seamlessly on desktop and mobile devices
- **⌨️ Keyboard Support**: Use your keyboard for quick calculations
- **🎨 Modern UI**: Clean and intuitive user interface
- **⚡ Real-time Calculations**: Instant results as you type
- **🧹 Clear Function**: Reset your calculations with a single click

## 🚀 Demo

![Calculator Preview](https://via.placeholder.com/600x400/4285f4/ffffff?text=Calculator+Preview)

*Screenshot of the calculator in action*

## 🛠️ Technologies Used

| Technology | Purpose | Version |
|------------|---------|---------|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure | HTML5 |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Styling | CSS3 |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Functionality | ES6+ |

## 📁 Project Structure

```
calculator/
├── 📄 index.html          # Main HTML file
├── 🎨 styles/
│   └── style.css          # CSS styles
├── ⚙️ scripts/
│   └── calculator.js      # JavaScript logic
├── 🖼️ assets/
│   └── images/           # Images and icons
└── 📖 README.md          # Project documentation
```

## 🔧 Installation & Setup

### Prerequisites
- 🌐 A modern web browser (Chrome, Firefox, Safari, Edge)
- 📝 A code editor (VS Code, Sublime Text, etc.)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/sushil/calculator-app.git
   ```

2. **Navigate to project directory**
   ```bash
   cd calculator-app
   ```

3. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   # Or use a local server
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## 🎮 Usage

### Basic Operations
- **➕ Addition**: Click numbers and the `+` button
- **➖ Subtraction**: Click numbers and the `-` button
- **✖️ Multiplication**: Click numbers and the `×` button
- **➗ Division**: Click numbers and the `÷` button

### Keyboard Shortcuts
| Key | Function |
|-----|----------|
| `0-9` | Enter numbers |
| `+` | Addition |
| `-` | Subtraction |
| `*` | Multiplication |
| `/` | Division |
| `Enter` or `=` | Calculate result |
| `Escape` or `C` | Clear display |
| `.` | Decimal point |

## 🏗️ Code Structure

### HTML Structure
The calculator uses semantic HTML with proper accessibility attributes:

```html
<div class="calculator">
  <div class="display">
    <input type="text" id="result" readonly>
  </div>
  <div class="buttons">
    <!-- Calculator buttons -->
  </div>
</div>
```

### CSS Highlights
- **Flexbox Layout**: For responsive button grid
- **CSS Grid**: For precise button positioning
- **Custom Properties**: For consistent theming
- **Smooth Animations**: For button interactions

### JavaScript Features
- **Event Listeners**: For button clicks and keyboard input
- **Error Handling**: For division by zero and invalid operations
- **Input Validation**: To prevent invalid calculations

## 🎨 Customization

### Changing Colors
Edit the CSS custom properties in `styles/style.css`:

```css
:root {
  --primary-color: #4285f4;
  --secondary-color: #34a853;
  --background-color: #f8f9fa;
  --text-color: #202124;
}
```

### Adding New Functions
Extend the JavaScript in `scripts/calculator.js`:

```javascript
function newFunction() {
  // Your custom function here
}
```

## 🐛 Known Issues

- ⚠️ Very large numbers may cause display overflow
- ⚠️ Decimal precision limited to 10 places

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **🍴 Fork** the repository
2. **🌿 Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **💾 Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **📤 Push** to the branch (`git push origin feature/AmazingFeature`)
5. **🔄 Open** a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Sushil**
- 🌐 Website: [sushil.dev](https://sushil.dev)
- 📧 Email: sushil@example.com
- 🐙 GitHub: [@sushil](https://github.com/sushil)
- 🐦 Twitter: [@sushil](https://twitter.com/sushil)

## 🙏 Acknowledgments

- Thanks to [MDN Web Docs](https://developer.mozilla.org/) for excellent documentation
- Inspiration from various calculator designs on [Dribbble](https://dribbble.com/)
- Icons provided by [Font Awesome](https://fontawesome.com/)

## 📊 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/sushil/calculator-app)
![GitHub last commit](https://img.shields.io/github/last-commit/sushil/calculator-app)
![GitHub issues](https://img.shields.io/github/issues/sushil/calculator-app)
![GitHub stars](https://img.shields.io/github/stars/sushil/calculator-app)

---

<div align="center">
  <strong>⭐ Don't forget to star this repository if you found it helpful! ⭐</strong>
</div>

---

<div align="center">
  Made with ❤️ and lots of ☕
</div>
