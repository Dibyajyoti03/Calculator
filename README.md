# Calculator Web App

A sleek, modern calculator web application with dark/light theme toggle functionality. Built with vanilla HTML, CSS, and JavaScript featuring a beautiful gradient background and smooth animations.

## Features

- **Basic Arithmetic Operations** - Addition (+), subtraction (-), multiplication (×), division (÷)
- **Parentheses Support** - Use ( and ) for complex calculations
- **Dark/Light Theme Toggle** - Switch between dark and light modes with a toggle button
- **Clear Function** - 'C' button to clear the entire display
- **Backspace Function** - '<' button to delete last entered character
- **Responsive Design** - Clean table-based button layout
- **Smooth Animations** - Button hover effects with scale transformation
- **Gradient Background** - Beautiful purple-pink gradient backdrop
- **Auto-scrolling Display** - Horizontal scroll for long calculations

## Demo

Open `index.html` in your browser to see the calculator in action!

## Installation

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Quick Start

1. **Download/Clone the files**

   ```
   calculator/
   ├── index.html
   ├── style.css
   └── script.js
   ```

2. **Open in browser**
   - Simply double-click `index.html` or
   - Right-click and select "Open with" → your preferred browser

## File Structure

```
calculator/
│
├── index.html          # Main HTML structure with calculator layout
├── style.css           # Styling, themes, and animations
├── script.js           # Calculator functionality and theme toggle
└── README.md           # This documentation
```

## Usage

### Basic Operations

1. **Numbers** - Click buttons 0-9 to input digits
2. **Operators** - Click +, -, ×, ÷ for arithmetic operations
3. **Parentheses** - Use ( and ) buttons for grouping operations
4. **Clear** - Click 'C' to clear the display completely
5. **Backspace** - Click '<' to delete the last character
6. **Calculate** - Click '=' to evaluate the expression

### Theme Toggle

- Click the **theme toggle button** (top-right corner) to switch themes
- **Dark Mode**: Dark calculator with colorful buttons (default)
- **Light Mode**: Light theme with contrasting colors

### Example Calculations

```
Simple: 7 + 3 = 10
Multiplication: 6 × 9 = 54
With parentheses: (4 + 5) × 2 = 18
Division: 15 ÷ 3 = 5
```

## Technical Details

### HTML Structure

- **Calculator Container** - Main wrapper with centered layout
- **Theme Toggle** - Positioned absolutely in top-right
- **Display Screen** - Shows current input and results
- **Button Grid** - 4×5 table layout for calculator buttons
- **Special Buttons** - Equal button spans 2 rows for better UX

### CSS Features

- **Gradient Background** - Linear gradient from purple to pink
- **Flexbox Layout** - Centered calculator with `place-items: center`
- **Button Styling** - Rounded buttons with color-coded functions
- **Theme Classes** - `.dark` class for theme switching
- **Hover Effects** - Buttons scale to 1.1x on hover
- **Scrollable Display** - Horizontal scrolling for long expressions

### JavaScript Functionality

- **Button Event Handling** - Click listeners for all calculator buttons
- **Display Management** - Updates display based on button clicks
- **Clear Function** - Empties display when 'C' is clicked
- **Backspace Function** - Removes last character with string manipulation
- **Calculation** - Uses `eval()` to evaluate mathematical expressions
- **Theme Toggle** - Switches between dark and light themes
- **Error Handling** - Shows "Empty" message when equals is pressed on empty display

## Code Highlights

### Button Color Scheme

- **Clear (C)**: Light pink background, red text
- **Numbers (0-9)**: Light blue background, dark text
- **Operators (+,-,×,÷,(,))**: Light purple background, purple text
- **Equal (=)**: Light green background, dark text

```

## Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

## Known Issues

1. **Theme Toggle Bug** - There's a typo in `script.js` line 25: `calculate.classList.toggle('dark')` should be `calculator.classList.toggle('dark')`
2. **CSS Selector Typo** - Line 73 in CSS: `#dispaly::-webkit-scrollbar` should be `#display::-webkit-scrollbar`
3. **HTML Syntax Error** - Extra semicolon in line 25: `<td><button class ="btn-operator" id="backspace"><</button></td;` should end with `>`
4. **Button ID Issue** - The '0' button has `class="btn-operator"` but should probably be `class="btn-number"`
5. **Equal Button Logic** - Space in condition: `item.id == ' equal'` should be `item.id == 'equal'`


```

## Future Enhancements

- [ ] Fix the identified bugs
- [ ] Add keyboard input support
- [ ] Implement memory functions (M+, M-, MR, MC)
- [ ] Add scientific calculator functions
- [ ] Calculation history feature
- [ ] Better error handling for invalid expressions
- [ ] Accessibility improvements

### Local Usage

**No server needed!** This calculator works perfectly by:

- Double-clicking `index.html` in your file explorer
- Opening `index.html` directly in any web browser
- Works offline - no internet connection required

## Contributing

Found a bug or want to add a feature?

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Fix bugs or add features
4. Test thoroughly
5. Commit changes (`git commit -m 'Add some AmazingFeature'`)
6. Push to branch (`git push origin feature/AmazingFeature`)
7. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

- 🐛 **Bug Reports**: Create an issue describing the problem
- 💡 **Feature Requests**: Suggest new features or improvements
- 📧 **Contact**: 21btcse25@suiit.ac.in

---

⭐ **Enjoyed using this calculator? Give it a star!**
