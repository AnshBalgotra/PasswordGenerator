# Password Generator

## Overview

The Password Generator is a user-friendly web application designed to create secure, random passwords tailored to individual preferences. Built using HTML, CSS, and JavaScript, this tool allows users to customize the password length and select from various character types such as uppercase letters, lowercase letters, numbers, and symbols. Additionally, the application features a convenient "Copy to Clipboard" function for easy password management.

## Features

- **Customizable Password Length:** Users can define the length of the password to fit their specific needs.
- **Selectable Character Types:** Options to include uppercase letters, lowercase letters, numbers, and symbols in the password.
- **Random Password Generation:** Generates passwords based on user-defined preferences.
- **Copy to Clipboard:** Easily copy the generated password for immediate use.
- **Responsive Design:** Compatible with various devices and screen sizes.

## How to Use

### Open the Password Generator Website

1. Navigate to the URL where the Password Generator website is hosted.

### Adjust Password Length

2. Use the "Password Length" slider to select the desired length of the password. You can adjust from a specified minimum to maximum value.

### Select Character Types

3. Choose from the checkboxes labeled "Include Uppercase letters," "Include Lowercase letters," "Include Numbers," and "Include Symbols" to define the character types you want in your password.

### Generate Password

4. Click the "Generate Password" button to create a password based on your settings. The password appears in the designated display area.

### Copy to Clipboard

5. Click the "Copy" button next to the password display to copy it to your clipboard, making it ready to paste into a login form or password manager.

### Password Strength Indicator

6. A color-coded strength indicator shows the password's strength, updating as you modify length and character types.

### Generate Another Password

7. If unsatisfied with the password, adjust settings and click "Generate Password" again for a new password.

### Responsive Design

8. The site is designed for seamless use across desktops, tablets, and mobile devices.

## JavaScript Functions and Properties

### JavaScript Functions

- **generateRandomInteger():** Generates a random integer between 0 and 9.
- **generateLowerCase():** Creates a random lowercase letter.
- **generateUpperCase():** Creates a random uppercase letter.
- **generateSymbols():** Selects a random symbol from a predefined set.
- **calculateStrength():** Evaluates the password strength, updating the indicator color.
- **copyContent():** Copies the password to the clipboard, displaying a success or failure message.
- **handleSlider():** Updates the password length display and adjusts the slider's background.
- **handleCheckBoxChange():** Adjusts the count of selected character types and modifies password length if needed.
- **shufflePassword(array):** Uses the Fisher-Yates algorithm to shuffle password characters.

### JavaScript Properties

- **password:** Stores the generated password.
- **passwordLength:** Represents the desired password length.
- **checkCountor:** Counts selected character type checkboxes.
- **symbols:** Contains predefined symbols for password generation.

These functions and properties are critical to the Password Generator's operation, ensuring secure, user-specific password generation.
