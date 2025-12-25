# Random Password Generator

A simple and intuitive web-based password generator that creates secure, customizable passwords with a few clicks.

## Features

- **Customizable Password Length** - Generate passwords from 1 to 32 characters
- **Character Type Selection** - Choose which character types to include:
  - Uppercase Letters (A-Z)
  - Lowercase Letters (a-z)
  - Numbers (0-9)
  - Symbols (!@#$%^&* etc.)
- **Real-time Generation** - Click to instantly generate a new password
- **Validation** - Ensures at least one character type is selected
- **Responsive Design** - Clean, centered UI that works on different screen sizes

## Technologies Used

- **HTML5** - Structure and layout
- **CSS3** - Styling and responsive design
- **JavaScript (Vanilla)** - Password generation logic and interactivity

## How to Use

1. Open `index.html` in your web browser
2. Set your desired password length using the input field (default: 12 characters)
3. Select which character types to include using the checkboxes:
   - All types are selected by default
   - Deselect any you don't want in your password
4. Click the **"Generate Password"** button
5. Your new password will appear in the display box
6. Click again to generate another password

## Project Structure

```
├── index.html      # Main HTML file with form controls
├── index.js        # Password generation logic and event handlers
├── style.css       # Styling and layout
└── README.md       # Project documentation
```

## Installation

No installation required! Simply:
1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start generating passwords

## How It Works

The `generatePassword()` function:
1. Builds a string of allowed characters based on user selections
2. Randomly selects characters from that string
3. Repeats the process for the specified password length
4. Returns the generated password

## Browser Compatibility

Works on all modern browsers that support:
- ES6 JavaScript
- CSS Flexbox
- HTML5 input elements

## Future Enhancements

- Copy to clipboard functionality
- Password strength indicator
- Save favorite passwords
- Dark mode theme
- Generate multiple passwords at once

## License

This project is open source and available for personal and educational use.

---

**Created for learning and practical password generation needs.**
