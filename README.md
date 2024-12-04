# Flucky Source

Welcome to **Flucky Source**!  
A collection of utility CSS styles designed to streamline your web design and development process. This repository offers a set of highly flexible styles, grids, and components to enhance your projects.

**Author:** [@hexakleo](https://github.com/hexakleo)

---

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
- [Styles](#styles)
- [Components](#components)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Getting Started

To use **Flucky Source** in your project, simply download the CSS file or clone this repository.

```bash
git clone https://github.com/hexakleo/flucky-source.git
```

Link the CSS file to your HTML:

```html
<link rel="stylesheet" href="path/to/flucky.css">
```

---

## Features

- **Responsive Grid System**: Built with Flexbox for adaptive layouts.
- **CSS Utilities**: Easily customizable classes for margin, padding, and alignment.
- **Dark Mode Support**: Built-in styles for dark and custom themes.
- **Components**: Buttons, Alerts, Cards, Progress Bars, and more.

---

## Styles

### Reset Styles
Standardize your layouts by removing margin and padding across all elements.

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

### Layout Styles
Easily control the width and layout of containers with flexible classes.

```css
.container {
  width: 80%;
  margin: 0 auto;
}

.flex {
  display: flex;
  flex-wrap: wrap;
}
```

### Grid System
A simple Flexbox-based grid system to create flexible and responsive layouts.

```css
.grid {
  display: flex;
  flex-wrap: wrap;
}

.grid .cell-1of12 {
  flex: 1 0 8.33%;
}

.grid .cell-2of12 {
  flex: 1 0 16.67%;
}
```

### Typography
Consistent typography with headers and blockquotes.

```css
h1, h2, h3, h4, h5, h6 {
  font-family: Arial, sans-serif;
  font-weight: bold;
}

blockquote {
  font-style: italic;
  border-left: 5px solid #ccc;
  margin: 1em 0;
  padding-left: 1em;
}
```

### Form Styles
Form styling with custom error, success, and warning states.

```css
.form-control {
  width: 100%;
  padding: 8px;
  border: 1px solid #ccc;
}

.form-group.form-success .form-control {
  border-color: green;
}

.form-group.form-error .form-control {
  border-color: red;
}
```

---

## Components

### Buttons
Quickly style buttons with predefined classes.

```css
.btn-primary {
  background-color: #007bff;
  color: white;
}

.btn-success {
  background-color: #28a745;
  color: white;
}
```

### Alerts
Create responsive alerts with success, error, and warning themes.

```css
.alert-success {
  background-color: #d4edda;
  border-color: #c3e6cb;
}

.alert-error {
  background-color: #f8d7da;
  border-color: #f5c6cb;
}
```

### Loading Spinner
A simple loading spinner for your application.

```css
.loading {
  border: 4px solid #f3f3f3;
  border-top: 4px solid #3498db;
  border-radius: 50%;
  width: 24px;
  height: 24px;
  animation: spin 1s linear infinite;
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
```

---

## Usage

1. **Include the CSS**: Link the `flucky.css` file in your HTML or import it in your project.
2. **Apply Classes**: Use the available classes for layout, typography, components, and utilities.
3. **Customize**: Feel free to override styles or extend them for your project's needs.

---

## Contributing

If you'd like to contribute to **Flucky Source**, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

---

## License

**Flucky Source** is open-source and released under the [MIT License](LICENSE). Feel free to modify and use it in your own projects.
