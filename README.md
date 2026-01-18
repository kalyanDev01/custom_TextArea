# Character Counter

A minimal character counter web app built with plain HTML, CSS, and JavaScript.  
It lets users type a message into a textarea and shows the current character count with a 200-character limit.

## Features

- Live character counting as you type.
- Hard limit of 200 characters using the `maxlength` attribute.
- Visual warnings when:
  - You are close to the limit (after 170 characters).
  - You reach the maximum limit (at 200 characters).
- Styled textarea border and background change when the limit is reached.
- Warning message displayed when no more characters can be added.

## How It Works

- The textarea has `maxlength="200"` to prevent typing more than 200 characters.
- A JavaScript function listens to the `input` event and:
  - Updates the count text (`current / 200 characters`).
  - Adds a warning style when the length exceeds 170.
  - Adds an error style and shows a warning message when the length hits 200.

## Technologies Used

- HTML5
- CSS3 (vanilla, no framework)
- JavaScript (vanilla, no libraries)

## Getting Started

1. Clone or download the project.
2. Open the `index.html` file in any modern web browser.
3. Start typing in the textarea to see the character counter in action.

## License

MIT License - feel free to use and modify.
