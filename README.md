# Login Form (Login-Form-126)

A clean, modern, and responsive login form built with plain HTML, CSS and JavaScript.

![Login Form Screenshot](./Screenshot%202025-02-20%20221235.png)

## Table of contents

- About
- Features
- Built with
- Screenshot
- Getting started
- Usage
- Customization
- Accessibility
- Contributing
- License

## About

This repository contains a small, easy-to-read example of a login form implementation using vanilla HTML, CSS, and JavaScript. It's intended as a learning example or a starting point for prototypes that need a lightweight authentication UI.

## Features

- Responsive layout for desktop and mobile
- Client-side validation for required fields
- Show / hide password toggle
- Simple, modern styling that's easy to customize

## Built with

- HTML
- CSS
- JavaScript (vanilla)

## Screenshot

![Login Form Screenshot](./Screenshot%202025-02-20%20221235.png)

## Getting started

These instructions will help you run the project locally.

### Prerequisites

A modern web browser (Chrome, Firefox, Safari, Edge).

### Run locally

1. Clone the repository:

```bash
git clone https://github.com/BinaryVortex/Login-Form-126.git
```

2. Open the project folder:

```bash
cd Login-Form-126
```

3. Open the HTML file in your browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows (PowerShell)
start index.html
```

Alternatively, serve the folder with a simple static server for testing (optional):

```bash
# Python 3
python -m http.server 8000
# then visit http://localhost:8000
```

## Usage

- Enter a username/email and password and click the login button to exercise the client-side validation.
- Use the show/hide password control (eye icon) to toggle visibility while typing.
- This form is a front-end demo only and does not submit to a backend by default—hook it up to your authentication API as needed.

## Customization

- Colors and typography: edit the CSS file(s) to change variables, fonts, and spacing.
- Validation rules: enhance the JavaScript to add stronger checks (e.g., password complexity) or integrate with server-side validation.
- Layout: modify containers and media queries to fit your app's design system.

## Accessibility

- Ensure labels are associated with inputs and aria attributes are used for interactive controls (the demo includes basic labeling; consider expanding for full WCAG compliance).
- Increase color contrast as needed and test with keyboard navigation.

## Contributing

Improvements are welcome — open an issue or submit a pull request with changes. Suggestions:

- Add unit tests for validation functions
- Improve keyboard and screen-reader accessibility
- Add an optional “remember me” flow and form state handling

## License

This project is provided under the MIT License. See the LICENSE file for details, or add one if you prefer a different license.

---

Created by @BinaryVortex
