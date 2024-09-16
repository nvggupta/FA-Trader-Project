# Responsive Login Page

## Project Overview

This project is a **responsive login page** that consists of two main sections:
- **Login Form Section**: Users can input their email and password to log in. It also includes links for password recovery and sign-up.
- **Welcome Section**: A visually appealing section with a background image and motivational text encouraging users to connect.

The page is styled with **CSS** and includes responsive design adjustments for various screen sizes using media queries.

## Features

- **Login Form**: The form allows users to input their email and password, with an option to recover their forgotten password and a link to sign up.
- **Motivational Section**: A section that displays motivational text with a background image.
- **Responsive Design**: The layout adjusts dynamically to different screen sizes to ensure a seamless experience on desktop, tablet, and mobile devices.

## Technologies Used

- **HTML5**: For structuring the webpage.
- **CSS3**: For styling the layout, responsiveness, and adding effects.
- **Font Awesome**: For the icons used in the email and password input fields.

## Responsive Design

The design is fully responsive, adjusting to screens of various sizes, such as:

- **Large Screens (1024px and above)**: The layout shows both the login section and the motivational section side-by-side.
- **Tablets (768px to 1024px)**: The layout adjusts slightly by resizing the sections to ensure the content fits well.
- **Mobile Screens (below 768px)**: The two sections stack vertically to ensure readability and usability, with elements adjusting in size to fit smaller screens.

### Media Queries

The page uses the following breakpoints for responsive design:
- **1024px and above**: Desktop layout with both sections side by side.
- **768px to 1024px**: Tablet layout with slightly resized sections.
- **Below 768px**: Mobile layout where the sections stack vertically for better visibility.

## Project Structure

## Setup Instructions

To use this project:

1. Clone this repository to your local machine.
2. Open the `index.html` file in any browser to view the login page.

## Customization

- **Form Fields**: You can modify the placeholder text or add more fields in the form section by editing the HTML.
- **Background Image**: To change the background image in the motivational section, update the `background-image` URL in the `.section2` class in the CSS file.
  
## Code Highlights

- **Login Button**:
  The login button changes appearance when clicked, giving a slight "pressed" animation:
  ```css
  .btn button:active {
    transition: all 0.5s;
    transform: translateY(10px);
    transform: scale(0.98);
  }

