# JS_DOM_task18
# Interactive Greeting Page

A simple web page built with HTML, CSS and JavaScript to practise DOM manipulation and event handling.

## Objective

Design a web page with interactive elements that:
- Shows a header with a greeting message
- Has four boxes labelled Red, Blue, Green and Yellow
- Has an input field to enter the user's name
- Has a button to greet the user

## Features

- **Greeting header:** shows "Hello" initially. After you enter a name and click **Greet**, it changes to "Hello, [name]".
- **Colour boxes:** clicking a box fills its background with the colour named in it. The text turns white.
- **Styled layout:** the elements are centered and styled with CSS.

## Project Structure

```
project-folder/
├── index.html    # Page structure and JavaScript
├── style.css     # Styling
└── README.md     # Project description
```

## Technologies Used

- HTML5
- CSS3
- JavaScript (DOM and event handling)

## How to Run

1. Download or clone the project folder.
2. Keep `index.html` and `style.css` in the same folder.
3. Open `index.html` in any web browser.
   - Or, in VS Code, right-click `index.html` and choose **Open with Live Server**.

## How It Works

JavaScript uses the DOM (Document Object Model) to:

| Method / Property | Purpose |
|---|---|
| `document.getElementById()` | Select the header, input and button |
| `document.querySelectorAll()` | Select all four colour boxes |
| `addEventListener("click", ...)` | Run code when the button or a box is clicked |
| `input.value` | Read the name typed by the user |
| `element.textContent` | Change the greeting text |
| `element.style.backgroundColor` | Fill a box with its colour |

## Usage

1. Type your name in the input field.
2. Click **Greet**. The header changes to "Hello, [your name]".
3. Click any box. It fills with the colour written in it.

## Author

Your Name
