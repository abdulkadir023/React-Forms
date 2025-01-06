# Dynamic Form Component

This repository contains a React-based dynamic form component that adapts based on the user's registration status. The project serves as a foundation for further development, where additional features and enhancements will be added over time.

## Features

- **Dynamic Fields:**

  - If the user is registering, the form includes a "Confirm Password" field.
  - If the user is logging in, the "Confirm Password" field is omitted.

- **Dynamic Button Text:**

  - Displays "Register" or "Login" based on the user's status.

- **Reusable Component:**
  - The `Form` component is highly reusable and accepts a `userIsRegistered` prop to adjust its behavior.

## Current Functionality

- Basic structure with conditional rendering using React props.
- Component designed to handle both registration and login workflows.

## Technologies Used

- **React**: For building the user interface.
- **CSS** (basic styling): For minimal styling and layout.

## Future Enhancements

- Implement controlled inputs with state management using React hooks.
- Add client-side validation (e.g., password confirmation).
- Integrate with a backend service for form submission.
- Improve styling with responsive design.
- Add unit and integration tests.

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm (v6 or higher) or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd dynamic-form-component
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Running the App

Start the development server:

```bash
npm start
```

The app will be available at `http://localhost:3000` in your browser.

## File Structure

```
src/
  components/
    Form.jsx       # Dynamic form component
    App.jsx        # Main app component
  index.js         # Entry point
```
