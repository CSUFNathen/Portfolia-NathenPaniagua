# Portfolio Website Project

## Overview

This project involves creating a personal portfolio website to showcase information about me. The site will feature:

- About Me
- Professional Headshot
- School Location
- Major
- Resume
- Contact Information
- GitHub Profile Link
- Projects

## Development Phases

### Phase 0: Planning

- Designed the website layout and features on paper.
- Defined the content and structure of the website.

### Phase 1: Learning HTML & Basic Styling

- Watched tutorials and learned HTML basics.
- Explored HTML elements like `<h1>`, `<h2>`, `<p>`, `width`,` height`, and `<div>`.
- Experimented with changing colors, adding images, adjusting font sizes, styles and boxes, and creating background designs.
- Started building the initial structure of the website.

### Phase 2: Implementing Buttons and Links

- Learned how to make a separate file to hold the styling code, making it more orginized.
- Learned how to create and style buttons.
- Implemented button functionalities including:
  - Downloading files
  - Navigating to external links
  - Linking to other pages within the same website

### Phase 3: Creating and Designing Pages

- Created individual pages for each section of the website.
- Designed the layout and content of each page according to its intended purpose.

### Phase 4: Enhancing Content

- Added images and text to the pages.
- Refined the design to make the website more complete and visually appealing.

### Phase 5: Final Refinements

- Polished the overall website.
- Ensured all elements and links function correctly.
- Made final adjustments and improvements.

## Usage

To view or use the website, open the `index.html` file in your preferred web browser. Make sure all associated files (CSS, images, etc.) are in the correct directories.

## Final Thoughts

Creating this website was a rewarding experience that deepened my understanding of web development. I gained valuable insights into the complexity of web design and the challenges that come with it. One particular challenge I faced was setting the background image. I struggled for hours trying to position the image correctly behind the main content box on the homepage.

After numerous attempts and breaks, I discovered that the solution was surprisingly simple. By adding a `body` style in the CSS file and specifying the background image within that style, I was able to achieve the desired effect. Here’s the CSS code that resolved the issue:

```css
body {
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    background-image: url('images/background.jpeg'); /* <-- */
    margin-bottom: 18px;
}
