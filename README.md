# MediaPro Studios - Advanced Media Production Website

## Overview
MediaPro Studios is a professional media production company specializing in high-end video, audio, and post-production services. This website showcases our capabilities through a modern, responsive interface built with advanced HTML5 and CSS3 techniques—demonstrating superior semantic structure, sophisticated layouts, and immersive visual effects without any JavaScript.

## Issues Found & Resolved
The starter codebase contained several critical omissions and errors:
- **Semantic HTML**: Generic `div` tags were replaced with appropriate HTML5 elements (`header`, `nav`, `main`, `section`, `article`, `footer`) to improve accessibility and SEO.
- **Metadata**: Missing viewport, charset, and description meta tags were added for responsiveness and optimization.
- **Media Elements**: Fixed missing controls and fallbacks for video/audio, added a second video, and implemented a functional Google Maps iframe.
- **Form Validation**: The contact form was missing labels, fieldsets, and proper input types. I implemented 7+ input types (email, tel, date, number, etc.) and robust HTML5 validation.
- **Visuals**: Added 6+ images using `<figure>` and `<figcaption>` markup for better semantic representation.

## Advanced Implementations

### Flexbox Layouts
- **Navigation Bar**: A responsive, sticky navigation bar using `flex` with `justify-content: space-between` and `align-items: center`.
- **Services Section**: A fluid grid of service cards using `flex-wrap: wrap` and `flex: 1 1 300px` to ensure perfect responsiveness on all screen sizes.

### CSS Grid Layout
- **Media Gallery**: A sophisticated 10-item gallery using CSS Grid with `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))` and `grid-gap`.
- **Advanced Positioning**: Utilized **Grid Template Areas** on the Home page to create an explicitly mapped, perfectly balanced 3x2 grid for featured content on larger screens.

### Selectors & Pseudo-classes
I utilized over 8 selector types, including:
- **Attribute Selectors**: `img[alt^="Digital"]`
- **Child & Descendant Selectors**: `.form-group > input`
- **Combination Selectors**: `.service-item h3 + p`
- **Pseudo-classes**: `:hover`, `:focus`, `:not()`, `:last-child`, `:active`, and `:first-of-type`.

### Visual Effects & Animations
- **CSS Transforms**: Implemented `translate`, `scale`, and `rotate` for interactive hover states.
- **Transitions**: Smooth transitions on all interactive elements.
- **Keyframe Animation**: A smooth `fadeIn` animation on the hero section and a creative **Bonus** spinning loading animation that fades out after 3 seconds.
- **Text Effects**: Implemented `text-shadow` for depth and `linear-gradient` text for a premium brand feel.

## Accessibility & Compatibility
- **Semantic Landmarks**: Used proper HTML5 landmarks for screen readers.
- **Form Labels**: Every input is explicitly linked to a label via `for` and `id`.
- **Cross-Browser**: Tested for compatibility, including vendor-prefixed properties like `-webkit-background-clip`.
- **Responsive**: Fully optimized for Desktop, Tablet, and Mobile views.

## How to View
To view this website locally:
1. Clone the repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, or Edge).

## Project Structure
- `index.html`, `about.html`, `media.html`, `contact.html`: Page templates.
- `css/styles.css`: Centralized advanced stylesheet.
- `images/`: High-quality media assets.
- `media/`: Video and audio sample placeholders.
- `design/`: Original wireframes and planning documents.
