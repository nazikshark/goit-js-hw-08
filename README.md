# GoIT JavaScript Homework #08 — Image Gallery

This project is a fully functional, responsive image gallery built using JavaScript. It focuses on the concepts of event delegation and integrating third-party libraries to enhance user experience.

## 📋 Project Overview
The main objective was to create a gallery where users can click on an image to view its full-size version in a professional modal window.

## 🚀 Key Features & Implementation:

### 1. Dynamic Rendering
- The gallery is generated dynamically from a data array (`images`).
- Efficient DOM manipulation: all items are added in a single operation to minimize reflow and repaint.

### 2. Event Delegation
- Implemented a single event listener on the `ul.gallery` container.
- This pattern ensures high performance and easier management of child elements.
- Included logic to prevent the default browser behavior (downloading the image on link click).

### 3. Professional Modal with basicLightbox
- Integrated the `basicLightbox` library via CDN for high-quality modal functionality.
- Implemented logic to dynamically swap the `src` of the modal image based on the clicked element's `data-source` attribute.

### 4. Advanced Logic
- Used **object destructuring** to handle image properties cleanly.
- Implemented checks to ensure the modal only opens when a valid gallery image is clicked.

## 🛠 Technologies & Tools:
- **JavaScript (ES6+)**: Event delegation, data attributes, DOM manipulation.
- **Library**: [basicLightbox](https://github.com/electerious/basicLightbox) (for modal windows).
- **CSS**: Flexbox/Grid for gallery styling according to the provided layout.
- **HTML5**: Semantic markup and data-attributes.

## 🔗 Live Demo:
[Link to your GitHub Pages here]
