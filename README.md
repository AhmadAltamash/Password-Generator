# Random Password Generator

This project is a web-based random password generator that allows users to create strong and customizable passwords. Users can select different character types (lowercase letters, uppercase letters, numbers, symbols) and additional options such as removing duplicate characters and adding spaces after every 8 characters.

## Features

- **Character Types:**
  - Lowercase Letters
  - Uppercase Letters
  - Numbers
  - Symbols

- **Customization Options:**
  - Remove Duplicate Characters
  - Add Spaces After Every 8 Characters

- **Password Length:**
  - The generated password is 16 characters long.

## Usage

1. **Select Character Types:**
   - Choose one or more character types by checking the appropriate checkboxes (Lowercase, Uppercase, Numbers, Symbols).

2. **Customization Options:**
   - Check "Remove Duplicates" to ensure the password contains no duplicate characters.
   - Check "Add Spaces" to insert a space after every 8 characters in the password.

3. **Generate Password:**
   - Click the "Generate Password" button to create a password based on your selected options.
   - The generated password will be displayed in the input field.

## Implementation Details

### Key Functions

- **getRandomElement(array)**: Returns a random element from the provided array.
- **generatePassword()**: Generates a password based on selected character types and options. If no character types are selected, an alert is shown.
- **removeDuplicates(str)**: Removes duplicate characters from the generated password.
- **addSpaces(str)**: Adds a space after every 8 characters in the password.

### HTML Structure

- **Checkboxes**: For selecting character types and customization options.
- **Input Field**: Displays the generated password.
- **Button**: Triggers password generation.

## Setup

To run this project locally:

1. Clone the repository:
   ```bash
   git clone (https://ahmadaltamash.github.io/Password-Generator/)
2. Open index.html in your web browser.

## Contribution
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Thanks to the open-source community for providing useful libraries and resources.
Inspired by the need for secure password management.
<hr>
Created by [Altamash Ahmad](https://github.com/AhmadAltamash)
