# bambusnetz Basic Webpage

> **NOTE:** This webpage and its stylesheet were mostly designed and organized with the help of AI (GitHub Copilot).  
> Please review and adapt as needed for your own use.

## Overview

This is a modern, responsive, dark-mode-only demo webpage called **bambusnetz**. It demonstrates a clean layout, a fixed animated footer with an extended Impressum, and interactive placeholder elements. The site is designed for easy customization and learning.

---

## Features

- **Dark Mode Only:** All styles use a dark color palette for comfortable viewing.
- **Responsive Layout:** Works well on desktop and mobile devices.
- **Header with Dropdown Navigation:** Use the dropdown in the header to switch between Home and About pages.
- **Animated Footer:** The footer is fixed to the bottom and pops up on hover or focus, revealing the Impressum (legal notice).
- **Impressum:** Contains extended legal information, only visible when the footer is hovered or focused.
- **Image Placeholders:** Each content row has an image placeholder with a subtle, randomized hover animation. You can use your own images by placing them in the project folder and referencing them in the HTML.
- **No JavaScript Frameworks:** Only vanilla HTML, CSS, and a small amount of JavaScript.

---

## Usage

### Navigation

- Use the dropdown menu in the header to switch between the Home and About pages.

### Footer & Impressum

- The footer is always visible at the bottom of the page.
- Hover over or focus the footer to reveal the Impressum with extended legal details.
- The footer has a cooldown after hiding, so it can't be immediately re-triggered.

### Image Placeholders

- To use your own images, place them in the project folder (e.g., `my-image.jpg`).
- Reference them in the HTML like this:
  ```html
  <div class="placeholder-image" style="background-image: url('my-image.jpg');"></div>
  ```
- If no image is set, a default dark placeholder is shown.
- Hovering over an image placeholder triggers a subtle, randomized animation.

---

## Customization

- **Colors and Layout:** Adjust variables in `style.css` under the `:root` selector.
- **Content:** Edit `index.html` and `about.html` to change text, add sections, or update images.
- **Legal Info:** Update the Impressum in the footer of each HTML file as needed for your project.

---

## File Structure

```
basic-webpage/
├── index.html
├── about.html
├── style.css
├── my-image.jpg (your custom images)
```

---

## Accessibility

- The footer and Impressum can be accessed with keyboard navigation (focus).
- The dropdown navigation is accessible and labeled.

---

## License

This project is a demonstration and uses fictitious data. You may use and modify it freely for learning or as a template.
