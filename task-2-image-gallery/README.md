# Responsive Image Gallery with Lightbox

A responsive pastel-themed image gallery built as part of the **CodeAlpha** task using HTML, CSS, and Vanilla JavaScript. It features a clean grid layout, fluid typography, a full-screen lightbox modal, and circular **Previous / Next** image navigation.

## Features

* **Responsive Grid Layout:** Adapts smoothly across desktop, tablet, and mobile viewports.
* **Uniform Image Framing:** Uses `object-fit: cover` with fixed dimensions so thumbnails stay aligned without distortion.
* **Fluid Typography:** Scales headings and text smoothly across screen sizes using CSS `clamp()`.
* **Interactive Lightbox Modal:** Opens a full-screen preview on clicking any image and closes cleanly via the close button.
* **Previous & Next Navigation:** Tracks the active image using `currentIndex` and modular arithmetic (`%`) for seamless looping between the first and last image.

## Tech Stack

* **HTML5**
* **CSS3** (`clamp()`, `object-fit`, Flexbox / Grid layout)
* **Vanilla JavaScript** (DOM selection, event listeners, index tracking)

## Project Structure

```text
image-gallery/
├── index.html
├── style.css
├── README.md
└── images/
    ├── image1.avif
    ├── image2.avif
    ├── image3.avif
    ├── image4.avif
    ├── image5.avif
    ├── image6.avif
    ├── image7.avif
    └── image8.avif