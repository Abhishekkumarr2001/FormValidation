# FormValidation

The form validation website is designed to allow users to submit their contact information while ensuring that the entered data is valid. The website incorporates HTML, CSS, and JavaScript to provide a user-friendly and interactive experience. The form consists of fields for the user's full name, phone number, email address, and a message.

The JavaScript code plays a crucial role in validating the form input. Each field has a corresponding validation function that is triggered whenever the user types or modifies the input. For instance, the validateName() function checks whether the name field is empty or contains only alphabetic characters with a space in between for the full name. Similarly, the validatePhone() function verifies that the phone number field contains exactly 10 digits.

To provide feedback to the user, the validation functions update the error messages on the webpage. If a field is invalid, an error message is displayed, prompting the user to enter the correct information. Conversely, when a field is valid, a green checkmark icon is shown, indicating that the input meets the required criteria.

The validateForm() function is responsible for ensuring that all fields pass the respective validations. If any of the fields are invalid, an error message is displayed at the bottom of the form, instructing the user to fill in the form correctly. Additionally, a timeout function clears the error message after 3 seconds, improving the user experience.

The CSS styles applied to the form enhance its appearance and make it visually appealing. The use of icons from the FontAwesome library adds a modern touch to the validation indicators. The layout and positioning of the form elements are carefully designed to ensure a clean and organized look, allowing users to easily understand and interact with the form.

#### Overall, the combination of HTML, CSS, and JavaScript in this form validation website creates a user-friendly experience. Users can fill out the form, receive immediate feedback on their input, and submit their contact information confidently, knowing that the form will validate their data accurately before submission.
