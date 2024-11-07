# Random_psd_generator

A simple web application that generates random passwords with uppercase letters, lowercase letters, numbers, and symbols. This project was created as part of a tutorial on the GreatStack YouTube channel. The password generator allows users to generate secure passwords and copy them easily with a click of a button.

Features:
  Password Generation: Generates a random password with a mix of uppercase letters, lowercase letters, numbers, and special characters.
  Copy to Clipboard: Allows users to copy the generated password to the clipboard with a simple click on the copy icon.
  Responsive Design: The layout is mobile-friendly and works on all devices.

Tech Stack
  HTML: Structure of the password generator.
  CSS: Styling for the layout and design.
  JavaScript: Logic to generate random passwords and handle the copy-to-clipboard functionality.

To use the Random Password Generator on your local machine, follow these steps:

1.Clone the repository:
  git clone https://github.com/yourusername/random-password-generator.git
2.Navigate to the project folder:
  cd random-password-generator
3.Open index.html in a web browser:
  Simply double-click the index.html file to open the project in your browser. Alternatively, you can host it on a local server for development using tools like Live Server in VS Code or any other local web server.

Usage
1. Click the Generate Password button to generate a new random password.
2. The password will be displayed in the text box.
3. Click the copy icon to copy the password to your clipboard.
4. After copying, a message will appear informing you that the password has been copied.

Dependencies: No external dependencies are used in this project. All functionality is built using vanilla HTML, CSS, and JavaScript.
Credits:
  Tutorial: The project was created following a YouTube tutorial from the GreatStack channel.
  Icons: The images used in this project (copy and generate icons) were sourced from Icons8.
  
License: This project is licensed under the MIT License.

Explanation of Key Files:
  index.html: Contains the structure of the password generator page, including the text input for displaying the password and the buttons for generating and copying the password.
  style.css: Defines the styling for the password generator, ensuring it looks clean and responsive on all screen sizes.
  script.js: Contains the JavaScript logic that generates the password, handles copying to the clipboard, and displays an alert after the password is copied.
  
How It Works:
1. Password Generation: The createPass() function generates a random password by selecting random characters from predefined sets: uppercase letters, lowercase letters, numbers, and special symbols.
2. Copy to Clipboard: The copyPass() function allows the user to copy the generated password to the clipboard with one click. An alert is displayed once the password is successfully copied.


Feel free to modify or expand on this project. If you have any questions or suggestions, please feel free to open an issue or submit a pull request!
