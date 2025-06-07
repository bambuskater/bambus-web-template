# bambusnetz Basic Webpage

> **NOTE:** This webpage and its stylesheet were mostly designed and organized with the help of AI (GitHub Copilot).  
> Please review and adapt as needed for your own use.

## Overview

**bambusnetz** is a modern, responsive demo webpage featuring both dark and light modes. It demonstrates a clean layout, animated fixed footer with extended Impressum, interactive placeholder elements, and a focus on accessibility and customization. The site is ideal for learning or as a starting point for your own projects.

---

## Features

- **Dark & Light Mode:**  
  - The site defaults to dark mode for comfortable viewing.
  - Users can toggle between dark and light mode using the round button (☀️/🌙) at the bottom left of the page.
  - Light mode uses a soft gray color palette (not pure white) for reduced eye strain.
  - The current mode is remembered across pages and browser sessions.
  - Smooth fade-in and fade transition effects are applied when switching modes, including a fade between the sun and moon icons.
- **Responsive Layout:** Works seamlessly on desktop and mobile devices.
- **Header with Dropdown Navigation:** Easily switch between Home and About pages using the header dropdown.
- **Animated Footer:** Fixed at the bottom, the footer pops up on hover or focus to reveal the Impressum (legal notice).
- **Extended Impressum:** Legal information is hidden by default and shown on footer interaction.
- **Image Placeholders:** Content rows include image placeholders with subtle, randomized hover animations. You can easily swap in your own images.
- **Smooth Fade-In Animation:** The entire page content fades in on load for a polished look.
- **No JavaScript Frameworks:** Built with vanilla HTML, CSS, and minimal JavaScript for interactivity.

---

## Usage

### Navigation

- Use the dropdown menu in the header to switch between the Home and About pages.

### Dark & Light Mode

- Click the round button at the bottom left to toggle between dark and light mode.
- The icon will fade between ☀️ (dark mode) and 🌙 (light mode).
- Your preference is saved and will persist across all pages and browser sessions.

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

- **Colors and Layout:** Adjust variables in `style.css` under the `:root` selector for dark mode and in the `.light-mode` section for light mode.
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
- Sufficient color contrast for readability in both modes.

---

## License

This project is a demonstration and uses fictitious data. You may use and modify it freely for learning or as a template.
