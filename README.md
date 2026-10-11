# Umuseke Café — Landing Page Rebuild

I first built the Umuseke Café landing page using HTML and plain CSS, writing custom styles to control the layout, colors, spacing, and responsiveness.

After completing the original version, I rebuilt the page using Tailwind CSS v4. I configured the Tailwind CLI to generate the CSS output and used utility classes directly in the HTML to style the page.

Working with both versions helped me understand the difference between writing custom CSS rules and using a utility-first CSS framework. I used Git and GitHub to track and publish my project progress.

A café landing page rebuilt using two approaches: plain CSS and Tailwind CSS.

## Project Overview

This project explores how the same landing page can be developed using traditional CSS and a utility-first CSS framework.

## Project Structure

- `plain-css/` — Original landing page built with HTML and plain CSS.
- `tailwind-css/` — Rebuilt landing page using HTML and Tailwind CSS.
- `README.md` — Project documentation.

## Technologies Used

- HTML5
- CSS3
- Tailwind CSS v4
- Git and GitHub

## How to Run the Project

### Plain CSS Version

1. Open `plain-css/index.html` in your browser, or use VS Code Live Server.
2. The page uses `plain-css/style.css` for its styling.

### Tailwind CSS Version

1. Open a terminal in the `tailwind-css/` directory.
2. Install the dependencies:

   ```bash
   npm install
   ```

3. Build the Tailwind CSS:

   ```bash
   npm run build
   ```

4. Open `tailwind-css/index.html` using VS Code Live Server.

## Comparing the Two Approaches

**Plain CSS:** Styling is written using custom CSS rules and reusable selectors.

**Tailwind CSS:** Styling is applied using utility classes directly in the HTML, with Tailwind generating the required CSS.

Both approaches can produce responsive, maintainable web pages. This project demonstrates the differences in their development workflows.

## Learning Outcomes

- Organizing a project with two implementation approaches.
- Building and styling a landing page with HTML and CSS.
- Using Tailwind CSS v4 and its CLI build process.
- Managing project changes with Git and GitHub.
