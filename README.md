# Frontend Mentor Challenge Solution - Huddle landing page with curved sections

![Header/intro section for the Huddle landing page with curved sections](./design/desktop-preview.jpg)

This project is a solution to the **Frontend Mentor Huddle Landing Page** challenge, featuring a unique design with curved sections created using CSS and HTML. The design incorporates pseudo-elements and CSS positioning, giving the page smooth, flowing transitions between sections.


## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [File Structure](#file-structure)
- [How It Works](#how-it-works)
- [Customization Options](#customization-options)
- [Resources](#resources)

## Overview

- **Challenge**: Implement a landing page with visually appealing curved sections.
- **Objective**: Practice using pseudo-elements, CSS positioning, and animation effects to enhance design and interactivity.

## Features

1. **Curved Section Design**:
   - Smoothly curved edges between sections using SVGs and CSS pseudo-elements.
   - Positioned elements create seamless transitions between content sections.

2. **Responsive Layout**:
   - Fully responsive, adapting to various screen sizes for an optimal user experience.

3. **Scroll Animations**:
   - Elements animate as they scroll into view using the [AOS (Animate on Scroll)](https://michalsnik.github.io/aos/) library.

4. **Interactive Elements**:
   - Includes call-to-action buttons, a newsletter subscription form, and accessible navigation links.

## Technologies Used

- **HTML5**: Page structure and content.
- **CSS3**: Styling and layout, including pseudo-elements for curved effects.
- **JavaScript**: Initializing animations with the AOS library.
- **AOS Library**: Smooth animations on scroll.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/huddle-landing-page.git
   cd huddle-landing-page
Open the Project: Open index.html in a browser to view the landing page.

Edit Styles: Customize colors, fonts, and other styling in css/style.css as desired.

JavaScript Animations: Modify animation settings in the <script> section within index.html.

File Structure
index.html: Main HTML file with page structure and content.
/css/style.css: Stylesheet for layout, animations, and curved sections.
/images/: Folder containing all images and icons used on the page.
How It Works
Curved Sections:

Each section transition is styled with SVGs and pseudo-elements (::before, ::after).
CSS position properties are used to align backgrounds precisely with each section.
AOS Animations:

Scroll animations are added with AOS for a dynamic, engaging experience.
Customization Options
Colors & Fonts:

Adjust colors and fonts in css/style.css for a personalized look.
Animation Speed:

Modify AOS settings in the <script> section for custom animation duration and offset values.
Content:

Update text, images, and links directly in index.html.
Resources
AOS Library Documentation: AOS Library for advanced animations.
Google Fonts: Uses Open Sans and Raleway fonts.
Frontend Mentor Challenge: Huddle Landing Page for design reference.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Enjoy customizing and deploying your own version of the Huddle Landing Page!
