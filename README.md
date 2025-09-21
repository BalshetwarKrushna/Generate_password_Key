# Generate_password_Key
🔐 React Password Generator

A simple yet powerful Password Generator built with React. It allows users to generate random secure passwords with customizable options like length, numbers, and special characters, and copy them with one click.

🚀 Features

Generate random strong passwords

Adjustable password length (6–100)

Option to include/exclude:

Numbers

Special Characters

Copy-to-clipboard functionality

Auto-regeneration when options change

Simple and responsive UI

🛠️ Technologies Used

React.js (Vite) → for building UI and state management

JavaScript (ES6+) → logic for password generation & clipboard

CSS3 → styling the app

React Hooks: useState, useEffect, useCallback, useRef

⚡ React Hooks Used

useState

length → stores the current password length (default: 8)

numberAllowed → boolean to allow/disallow numbers

charAllowed → boolean to allow/disallow special characters

password → stores the generated password

useRef

passwordRef → references the password input field to copy the text

useCallback

passwordGenerator → memoized function to generate passwords efficiently

copyPasswordToClipboard → memoized function to copy password

useEffect

Automatically triggers passwordGenerator() whenever length, numberAllowed, or charAllowed changes

🔑 How It Works

By default, a password of length 8 is generated.

Use the range slider to change the password length (between 6 and 100).

Toggle checkboxes to include/exclude numbers and characters.

Click the Copy button to copy the generated password to the clipboard.

Every change in options automatically generates a new password.
