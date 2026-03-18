<p align="center">
  <a href="https://bismillahcss.github.io/">
    <img src="https://github.com/user-attachments/assets/090a4b96-d98f-4fdb-98c4-e46815ca20e7" alt="BismillahCSS" />
  </a>

<img width="1329" height="258" alt="image" src="" />

  
  <br />
  <br />
  <br />
  <a href="https://www.npmjs.com/package/bismillahcss">
    <img src="https://img.shields.io/npm/v/bismillahcss?color=blue&style=flat-square" alt="npm version" />
  </a>
  <a href="https://www.npmjs.com/package/bismillahcss">
    <img src="https://img.shields.io/npm/dt/bismillahcss?color=green&style=flat-square" alt="downloads" />
  </a>
  <a href="https://github.com/BismillahCSS/bismillahcss-framework/blob/main/LICENSE">
    <img src="https://img.shields.io/npm/l/bismillahcss?style=flat-square" alt="license" />
  </a>
  <a href="https://github.com/BismillahCSS/bismillahcss-framework/stargazers">
    <img src="https://img.shields.io/github/stars/BismillahCSS/bismillahcss?style=flat-square" alt="GitHub stars" />
  </a>
  <a href="https://github.com/BismillahCSS/bismillahcss-framework/issues">
    <img src="https://img.shields.io/github/issues/BismillahCSS/bismillahcss?style=flat-square" alt="GitHub issues" />
  </a>
</p>


A utility-first CSS framework designed for rapid, flexible, and customizable web development. BismillahCSS aims to streamline your design workflow with a focus on ease of use, simplicity, and performance.

## 🌟 Features

- **Utility-first design** – Get the building blocks to craft beautiful designs quickly and efficiently.
- **Custom utilities** – Fully customizable utility classes for layout, typography, colors, shadows, and more.
- **Advanced shadow system** – Implement shadows with fine-grain control using multiple utilities.
- **Button system** – Predefined button styles for consistent UI components.
- **Notification alert system** – Easy-to-use alert system to notify users of important messages.
- **Glassmorphism cards** – Stylish and modern card components based on the glassmorphism design trend.
- **Dark mode support** – Built-in dark mode support for a seamless experience.
- **Customizable** – Easily override defaults to fit your unique design requirements.

## 📦 Installation

### Using npm:

```bash
npm install bismillahcss
```

### CDN:

You can also use BismillahCSS directly via CDN:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bismillahcss/dist/bismillah.min.css">
```

## 🔧 Usage

Start using BismillahCSS by linking the `bismillah.min.css` file in your HTML:

```html
<head>
    <link rel="stylesheet" href="path/to/bismillah.min.css">
</head>
```

Use utility classes like `bismillah-bg-blue`, `bismillah-text-center`, `bismillah-shadow-md`, and more to style your elements quickly.

### Example:

```html
<button class="bismillah-btn bismillah-bg-blue bismillah-text-white bismillah-shadow-md">
    Click Me!
</button>
```

## 📚 Documentation

Detailed documentation of all utilities, components, and configurations is available in the `docs` folder.

### Key Components:

- **Buttons**: Use `bismillah-btn` for styled buttons.
- **Cards**: Glassmorphism cards like `bismillah-card`.
- **Alerts**: Easily implement notifications with `bismillah-alert`.

## ⚙️ Configuration

BismillahCSS is highly configurable. Modify the `default-config.js` file to customize the framework's base styles, utilities, and more.

```javascript
module.exports = {
    colors: {
        primary: '#1D4ED8',
        secondary: '#F97316',
    },
    spacing: {
        small: '8px',
        medium: '16px',
        large: '32px',
    },
    // Customize further...
};
```

## 🧪 Testing

Tests for utilities and components are available in the `tests` folder to ensure all features work correctly. Run the tests with your preferred testing framework.

## 🌱 Contributing

Contributions are always welcome! Feel free to open issues or pull requests to improve BismillahCSS. Here's how you can contribute:

1. Fork the repository  
2. Create a new branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -am 'Add feature'`)  
4. Push to the branch (`git push origin feature-name`)  
5. Open a Pull Request  

## 🔗 Links

- **Website**: [BismillahCSS Documentation](#)  
- **License**: [MIT License](#)

## 📜 License

This project is licensed under the MIT License - see the `LICENSE` file for details.

Thank you for using BismillahCSS! 🙏  
Let's build beautiful, responsive, and efficient websites together!  
