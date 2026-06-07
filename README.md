# Hotel Booking Website

A responsive hotel booking website built with React and Tailwind CSS. This project includes pages for home, hotels, rooms, booking, and about sections, along with a featured hotel slider and booking form.

## Project Description

This student project demonstrates a hotel booking UI built using:
- React for the frontend
- React Router for multi-page navigation
- Tailwind CSS for styling
- Create React App project structure

The website allows users to explore hotels, view room options, and access booking details in a clean, mobile-friendly layout.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/JaafarSabra/Hotel-Booking-website.git
   cd "Hotel-Booking-website"
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm start
   ```
4. Build the production package:
   ```bash
   npm run build
   ```
5. Deploy to GitHub Pages (optional):
   ```bash
   npm run deploy
   ```

## Available Scripts

- `npm start` - starts the app in development mode
- `npm run build` - builds the app for production
- `npm test` - runs the test runner
- `npm run eject` - ejects the Create React App config
- `npm run deploy` - deploys the `build` folder using `gh-pages`

## Screenshots of the UI

> Add actual screenshot images to a `screenshots/` folder and update the paths below for display.

### Home Page

![Home Page](screenshots/home-page.png)

### Hotels Page

![Hotels Page](screenshots/hotels-page.png)

### Booking Page

![Booking Page](screenshots/booking-page.png)

## Notes for Students

- Start the app locally before taking screenshots.
- If you want to update the UI, edit files under `src/components` and `src/pages`.
- `public/index.html` contains the HTML template for the app.
- `src/index.js` is the React entry point.

## Project Structure

- `public/` - static files and images
- `src/` - React application source code
  - `components/` - reusable UI components
  - `pages/` - page-level components
- `package.json` - project metadata and scripts
- `tailwind.config.js` - Tailwind CSS configuration
- `postcss.config.js` - PostCSS configuration
