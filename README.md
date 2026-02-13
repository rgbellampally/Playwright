# Playwright

A comprehensive guide and project repository for learning and working with Playwright, a modern end-to-end testing framework for web applications.

## About Playwright

Playwright is a framework for writing reliable end-to-end tests for modern web apps. It provides:
- **Multiple Browser Support**: Test across Chromium, Firefox, and WebKit
- **Cross-Platform**: Works on Windows, macOS, and Linux
- **Headless & Headed Modes**: Run tests with or without a visible browser
- **Fast & Reliable**: Automatic wait for elements and network activity
- **Mobile Emulation**: Test mobile experiences on desktop
- **Screenshots & Videos**: Capture test failures for debugging

## Project Structure

```
Playwright/
├── chapter01/
│   └── basics.js       # Basic Playwright concepts and examples
├── .gitignore          # Git ignore file
└── README.md           # This file
```

## Prerequisites

- **Node.js**: Version 14 or higher
- **npm** or **yarn**: Package manager

## Installation

1. Clone the repository:
```bash
git clone https://github.com/rgbellampally/Playwright.git
cd Playwright
```

2. Install dependencies:
```bash
npm install
```

3. Install Playwright browsers:
```bash
npx playwright install
```

## Getting Started

### Running Tests

To run tests in headless mode:
```bash
npx playwright test
```

To run tests in headed mode (visible browser):
```bash
npx playwright test --headed
```

To run a specific test file:
```bash
npx playwright test chapter01/basics.js
```

## Directory Contents

### Chapter 01: Basics
- Introduction to Playwright
- Basic navigation and interactions
- Finding elements
- User interactions (click, fill, type, etc.)
- Taking screenshots

## Resources

- [Official Playwright Documentation](https://playwright.dev)
- [Playwright GitHub Repository](https://github.com/microsoft/playwright)
- [Playwright API Reference](https://playwright.dev/docs/api/class-playwright)

## Contributing

Feel free to fork this repository and contribute with improvements or additional examples.

## License

MIT License - Feel free to use this project for learning and educational purposes.

## Author

Rajesh Goud Bellampally

---

Happy Testing! 🚀
