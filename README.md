# Frontend-002--Contest-2--Aug-24
Form Setup: The form contains two input fields (email and password) and a submit button.
Validation on Change:
validateEmail(): Checks if the email is valid (more than 3 characters, contains "@" and ".").
validatePassword(): Checks if the password is more than 8 characters long.
Displaying Errors/Success:
If the email or password doesn't meet the criteria, an error message is shown in red.
If both fields are valid, a success message is shown in green.
Submit Button:
When the submit button is clicked, it checks if the email and password are valid.
If valid, it prompts the user with a confirmation window.
If the user confirms, it shows a "Successful Signup!" alert.
If the user cancels, it resets the form fields.