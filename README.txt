# Vanmala Herbal Static Website

Simple static website built with:

- HTML
- CSS
- JavaScript

## Folder structure

vanmala-herbals/
├── index.html
├── style.css
├── script.js
└── assets/
    └── images/
        ├── hero-banner.jpg
        ├── product-front.jpg
        ├── product-angle.jpg
        ├── product-pack.jpg
        └── product-combo.jpg

## Important replacements

### 1. Logo
The website currently uses a text placeholder.

In `index.html`, replace:

<div class="logo-placeholder">
    <span>vanmala</span>
    <small>HERBAL</small>
</div>

with:

<img src="assets/images/logo.png" alt="Vanmala Herbal">

Add your actual logo as:

assets/images/logo.png

### 2. Contact information
The provided details did not include a phone number, email or exact address. Replace the placeholder contact information in the Contact section.

### 3. Google Maps
The About section currently searches Google Maps for "Vanmala Herbal".

Replace the iframe `q=` value with the exact business address/location when available.

## Run

Simply open `index.html` in a browser.

For development, VS Code + Live Server can be used.
