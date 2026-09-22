# Password Strength Checker

A simple yet effective password strength checker built with Python and Tkinter. This application provides real-time feedback on password security with visual indicators and detailed requirements.

## Features

✨ **Real-time Analysis** - Get instant feedback as you type your password

📊 **Visual Progress Bar** - Color-coded strength meter (red → lime green)

✅ **Detailed Requirements** - Check against 5 security criteria:
- Minimum 8 characters
- Uppercase letters
- Lowercase letters
- Numbers
- Special characters

👁️ **Show/Hide Toggle** - Switch between masked and visible password

🎨 **Modern UI** - Dark-themed interface with intuitive design

📈 **Strength Score** - Clear 0-5 scoring system

## Screenshots

The application displays:
- Password input field with show/hide button
- Real-time strength meter with color coding
- Strength rating (Very Weak, Weak, Medium, Strong, Very Strong)
- Checklist of requirements with color-coded indicators
- Check Password and Clear buttons

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

## Installation

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/password-strength-checker.git
cd password-strength-checker
```

2. **Verify Python and Tkinter are installed:**
```bash
python --version
python -m tkinter  # Opens a small test window
```

## Usage

1. **Run the application:**
```bash
python project.py
```

2. **Enter a password** in the input field

3. **Click "Check Password"** to analyze the strength

4. **View the results:**
   - Strength rating
   - Score out of 5
   - Visual progress bar
   - Requirements checklist

5. **Use "Show"** to reveal the password (click again to hide)

6. **Click "Clear"** to reset and start over

## How It Works

The checker evaluates passwords based on five criteria:

| Criterion | Points |
|-----------|--------|
| Length ≥ 8 characters | 1 |
| Contains uppercase | 1 |
| Contains lowercase | 1 |
| Contains number | 1 |
| Contains special character | 1 |

**Strength Levels:**
- **Very Weak** (0-1 points): Red
- **Weak** (2 points): Red
- **Medium** (3 points): Orange
- **Strong** (4 points): Yellow
- **Very Strong** (5 points): Lime Green

## Technical Details

- **Language:** Python
- **GUI Framework:** Tkinter
- **Pattern Matching:** Regular Expressions
- **Color Scheme:** Dark theme (#0b1118, #142231)
- **Font:** Segoe UI

## Code Structure

```
check_password()      # Main validation logic
show_password()       # Toggle password visibility
clear_password()      # Reset form
[UI Components]       # Tkinter widgets setup
```

## Customization

You can easily customize:

- **Window size:** Modify `root.geometry("600x650")`
- **Colors:** Change hex color codes in the code
- **Font:** Edit font names and sizes (currently Segoe UI)
- **Requirements:** Add or remove validation criteria

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to:
- Report issues
- Submit pull requests
- Suggest improvements
- Add new features

## Author

Created with Python and Tkinter

---

**Made with ❤️ for better password security**
