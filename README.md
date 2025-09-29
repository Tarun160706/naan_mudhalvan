# Interactive Form Validation System

This project implements a real-time form validation system that provides immediate feedback to users as they complete a registration form.

## Features

- **Real-time Validation**: Input is validated as users type or when they leave a field
- **Inline Error Messages**: Specific, helpful error messages appear directly below relevant input fields
- **Visual Feedback**: Input field borders change color to indicate validation status (red for errors, green for valid entries)
- **Password Strength Meter**: Visual indicator of password strength with helpful feedback
- **Form Submission Control**: Form cannot be submitted until all fields are valid
- **User-Friendly Messages**: Clear, actionable feedback for validation errors

## Form Fields

The registration form includes the following fields:

- Full Name (required)
- Email Address (required)
- Phone Number (required)
- Password with strength indicator (required)
- Confirm Password (required)
- Website URL (optional)
- Date of Birth (required)

## Implementation Details

- **HTML**: Structured form with appropriate input types and error message containers
- **CSS**: Styling for form elements and validation states
- **JavaScript**: Real-time validation logic with specific rules for each field type

## How to Use

1. Open `index.html` in a web browser
2. Fill out the registration form
3. Observe real-time validation feedback as you type
4. Submit the form once all fields are valid

## Validation Rules

- **Full Name**: Must contain only letters, spaces, and common punctuation
- **Email**: Must be a valid email format (e.g., name@example.com)
- **Phone Number**: Must be a valid phone number format with area code
- **Password**: Must be at least 8 characters long with strength evaluation
- **Confirm Password**: Must match the password field
- **Website**: If provided, must be a valid URL format
- **Date of Birth**: Must be a valid date not in the future

## Future Enhancements

- Backend integration for server-side validation
- Additional form field types and validation rules
- Accessibility improvements
- Internationalization support
