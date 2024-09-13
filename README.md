# My Business Card

This project is a simple and responsive business card webpage created using HTML and CSS. The card showcases a personal profile, including a profile image, name, job title, and location, all styled to look like a professional business card.

https://startling-cajeta-7954ba.netlify.app

## Project Overview

- **Author:** Serena Park
- **Role:** Frontend Developer
- **Location:** Sydney, Australia

## Project Structure

- **`index.html`**: The main HTML file containing the structure of the business card.
- **`styles.css`**: The CSS file that provides styling for the business card layout, colors, and fonts.
- **`Linkedin Headshots_3.jpg`**: The profile image used on the business card.

## File Descriptions

### `index.html`

This file defines the structure of the business card using HTML. It includes:
- A `header` with metadata and links to external stylesheets.
- A `body` containing a card with a profile image, name, job title, and location.

### HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Business Card</title>
    <link rel="stylesheet" href="styles.css" />
  </head>

  <body>
    <div class="card">
      <img
        class="profile-img"
        src="Linkedin Headshots_3.jpg"
        alt="Per Harald's Borgen profile picture"
      />
      <div>
        <h3>Serena Park</h3>
        <p>Frontend Developer</p>
        <h4>Sydney, Australia</h4>
      </div>
    </div>
  </body>
</html>
