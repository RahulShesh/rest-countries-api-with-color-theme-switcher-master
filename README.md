# Country Details Website

## Overview
This project is a **Country Details Website**  that provides detailed information about different countries. It features a dark mode toggle, a responsive design, and interactive UI elements.

## Features
- 🌎 **Country Details**: Displays flag, population, region, subregion, capital, and border countries.
- 🌑 **Dark Mode**: Users can switch between light and dark themes.
- 📱 **Responsive Design**: Works on all screen sizes.
- 🎨 **Modern UI**: Uses CSS for smooth transitions and clean styling.

## Technologies Used
- **HTML**: Structure of the web pages.
- **CSS**: Styling and dark mode implementation.
- **JavaScript**: Handles theme toggling and interactive elements.
- **Google Fonts**: Uses *Nunito Sans* for typography.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/country-details.git
   ```
2. Open the project folder:
   ```sh
   cd country-details
   ```
3. Open `index.html` in your browser.

## Dark Mode Implementation
- Dark mode is applied by toggling a `.dark` class on `<body>`.
- Uses CSS variables to switch between light and dark themes.
- JavaScript updates the theme and switches icons accordingly.

### JavaScript for Theme Toggle
```js
const themeToggle = document.getElementById("theme-mode");

themeToggle.addEventListener("click", () => {
    document.body.classList.toggle("dark");
});
```

## File Structure
```
├── assets/
│   ├── darkmode.svg
│   ├── lightmode.svg
│   ├── back.svg
│   ├── search.svg
│   
│   
├── index.html
├── country.html
├── script.js
├── styles.css
├── styles2.css
├── README.md
```

## Future Improvements
✅ API Integration for live country data.
✅ Search functionality to find specific countries.
✅ More UI enhancements and animations.

## License
This project is open-source and available under the **MIT License**.

---

💡 **Contributions & Feedback** are welcome! Feel free to submit pull requests or suggest improvements. 🚀

