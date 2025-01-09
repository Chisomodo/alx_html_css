# Responsive Web Page

This project demonstrates a responsive web page design that adapts seamlessly to different screen sizes and user interactions. Below are the key features and implementation details.

---

## Features

1. **Mobile-First Design:**
   - The layout automatically switches to the mobile version when the screen width is 480px or less, ensuring an optimal user experience on smaller devices.

2. **Hover and Active States:**
   - **Links:** Change to `#FF6565` when hovered or active.
   - **Buttons:** Adjust opacity to `0.9` when hovered or active.

3. **Content Width:**
   - The content is constrained to a maximum width of `1000px` and is centered horizontally on the page for better readability.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://https://github.com/Chisomodo/alx_html_css/responsive-web-page.git
   ```

2. Navigate to the project directory:
   ```bash
   cd responsive-web-page
   ```

3. Open `index.html` in your preferred browser.

---

## Usage

- Resize the browser window to see the responsive behavior.
- Hover over links and buttons to observe their visual state changes.

---

## Code Highlights

### CSS Media Query for Responsiveness
```css
@media screen and (max-width: 480px) {
  body {
    font-size: 14px;
    padding: 10px;
  }
  .container {
    flex-direction: column;
  }
}
```

### Link Hover and Active State
```css
a:hover, a:active {
  color: #FF6565;
}
```

### Button Hover and Active State
```css
button:hover, button:active {
  opacity: 0.9;
}
```

### Centered Content
```css
.container {
  max-width: 1000px;
  margin: 0 auto;
}
```

---

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests to improve the design and functionality.

---

## License

This project is licensed under the [MIT License](LICENSE).
