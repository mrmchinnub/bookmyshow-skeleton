# Assignment: BookMyShow Skeleton App

### What do you need to start working with this project

- Install VSCode
- Install `EsLint` Extension from VSCode Extensions

## Getting started

`npm install`

##### Start using the project

### How to check for errors & warnings?

`npm run lint`

### How to fix errors & warnings forcefully?

`npm run lint:fix`

## Overview

The purpose of this assignment is to create a basic skeleton for a movie ticket booking app, resembling BookMyShow. The focus is on functionality rather than aesthetics. The app will consist of three main pages:

1. Login Page
2. Seat Selection Page
3. Payment Summary Page

The application should be designed with simplicity in mind, using basic HTML, CSS, and JavaScript. The use of Flexbox for layout is required to demonstrate understanding of CSS Flexbox layout. Local storage will be used to simulate database operations. Below are the detailed requirements for each page.

---

## 1. Login Page

### Objectives:

- Create a simple login form.
- Validate user input.
- Redirect to the Seat Selection Page upon successful login.

### Requirements:

- **Form Fields:** Username and Password.
- **Validation:** Check if the username and password fields are not empty.
- **Local Storage:**
  - Store user credentials in local storage for validation.
- **Actions:**
  - **Login Button:** On click, validate the fields against local storage. If validation passes, redirect to the Seat Selection Page.
  - **Error Handling:** Display error messages for invalid inputs.

---

## 2. Seat Selection Page

### Objectives:

- Display a grid of seats using Flexbox.
- Allow users to select and deselect seats.
- Show the total number of selected seats and the corresponding price.
- Store the selection in local storage.

### Requirements:

- **Seat Layout:** Use Flexbox to create a grid of seats.
- **Seat Selection:**
  - **Selectable Seats:** Clicking on a seat should toggle its selection status.
  - **Visual Feedback:** Selected seats should be visually distinct from available and unavailable seats.
- **Summary:**
  - Display the total number of selected seats.
  - Calculate and display the total price based on the number of selected seats.
- **Local Storage:**
  - Store the selected seats and the total price in local storage.

---

## 3. Payment Summary Page

### Objectives:

- Show a summary of the selected seats and the total amount.
- Provide a button to confirm the booking.
- Store the booking information in local storage.

### Requirements:

- **Booking Summary:**
  - Retrieve and list the selected seats from local storage.
  - Display the total amount for the booking.
- **Actions:**
  - **Confirm Booking Button:** On click, store the booking information in local storage and show a confirmation message indicating successful booking.
  - **Cancel Button:** On click, redirect back to the Seat Selection Page.

---

## Additional Notes:

- **Responsiveness:** The pages should be minimally responsive and ensure usability on various devices.
- **Validation:** Perform basic client-side validation where applicable.
- **Code Quality:** Focus on writing clean, maintainable code.

## Submission:

- Commit your code changes to the feature branch.
- Submit your work as a Pull Request to the main branch of the original repository.
- Assign `saikksub` as the reviewer for your Pull Request.

Include a README file with instructions on how to run the application, how to use the app, and any other necessary documentation.

Good luck!
