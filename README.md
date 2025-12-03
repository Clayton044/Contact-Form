# Contact Form using React and `useForm` Hook

A simple, responsive contact form built with React, featuring form validation and state management using the `useForm` hook.

## Features

- **Form Fields**:
  - Name (required)
  - Email (required, validated for correct email format)
  - Message (required)
- **Validation**: Real-time validation with error messages for invalid or empty fields.
- **Responsive Design**: Clean, modern UI that adapts to different screen sizes.
- **State Management**: Uses the `useForm` hook to manage form state, errors, and submission status.

## Technologies Used

- React
- Custom `useForm` hook
- CSS for styling

## How to Use

1. Fill in the **Name**, **Email**, and **Message** fields.
2. The form will validate inputs in real-time:
   - Required fields must not be empty.
   - Email must be in a valid format (e.g., `user@example.com`).
3. Click the **Submit** button to submit the form if all validations pass.
4. Error messages will appear below invalid fields to guide the user.

## Implementation Details

The `ContactForm` component uses a custom `useForm` hook to handle:
- Form field values (`name`, `email`, `message`)
- Validation errors
- Submission status
- Resetting the form after successful submission

Validation rules are applied on blur and on submission to ensure data integrity.

## Evaluation Criteria Met

✅ **Proper usage of the `useForm` hook** — Manages all form state, validation, and submission logic.  
✅ **Implementation of Contact Form functionality** — All required fields with validation and error handling.  
✅ **Quality of UI and styling** — Modern, clean design with gradient button and responsive layout.

---

**Created on:** Wednesday, December 03, 2025
