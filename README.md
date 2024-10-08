
# AIESEC Account Creation Form

This project is a web-based form designed to allow users to create an account with AIESEC. The form includes fields for personal information and program selection and features form validation, email verification, and password strength checking. It also uses AIESEC's API to fetch specific data and submit user information.

## Features

- **Responsive Design**: Built with Bootstrap for a mobile-friendly experience.
- **Email Validation**: Checks if the email is valid and already registered.
- **Password Strength Checker**: Visual feedback on password strength.
- **Dynamic Dropdowns**: University and referral type dropdowns are populated from JSON data.
- **Animated Popup**: A welcome popup with a countdown timer.
- **API Integration**: Uses AIESEC’s GraphQL API for account creation and validation.

## Installation

1. Clone the repository or download the files to your local machine.
2. Ensure you have an internet connection, as Bootstrap and Font Awesome are included via CDN.
3. Open `index.html` in a web browser.

## Usage

1. Enter all required information in the form fields.
2. The password field will indicate the strength of the password entered.
3. Upon form submission, the data will be validated and sent to the AIESEC API for account creation.
4. If successful, the user will be redirected to a thank you page.

## Files

- `index.html`: The main file containing the form and embedded JavaScript for validation and submission.
- `universities.json` and `referrals.json`: External JSON files containing data for dropdowns.
- `favicon2.svg`: The favicon for the website.
  
## Dependencies

- **Bootstrap v5.3.0-alpha3**: For responsive styling.
- **Font Awesome**: For icons used in the form.
- **JavaScript**: Used for form validation and API interaction.

## Customization

- Modify the AIESEC API endpoint or token in the JavaScript as needed.
- Adjust styling in the `<style>` section within `index.html` or add a custom stylesheet.

## License

This project is licensed under the MIT License.
