# CSS Advanced

## Project Overview

This is the CSS Advanced implementation of the SmileSchool webpage, created as part of the ALCHE Front-End Web Development Project. This version adds complete styling to the HTML structure based on Figma design specifications.

## Description

SmileSchool is an educational platform where users can learn various smiling techniques from professional instructors. This fully styled webpage features a modern, responsive design with gradient effects, smooth transitions, and pixel-perfect implementation of the design specifications.

## Project Structure

```
css_advanced/
├── index.html       # HTML file with linked stylesheet
└── styles.css       # Complete CSS styling
```

## Features

### Complete Styling Implementation:

1. **Header Section**
   - Absolute positioning with transparent background over banner
   - Logo on the left, navigation links on the right
   - White navigation links with hover effects
   - Clean, minimal design

2. **Banner Section**
   - Full-width background image with gradient overlay
   - Centered hero content with large, bold typography
   - Gradient purple call-to-action button with hover effects
   - "Learn from the pros" section with 4-column grid
   - Circular avatar images with professional styling

3. **Quote Section**
   - Purple gradient background (#C271FF)
   - Flexbox layout with avatar on left, quote on right
   - Large, readable typography
   - Author name in bold, title in italic

4. **Videos Section**
   - White background for contrast
   - 4-column responsive grid
   - Video cards with:
     - Rounded thumbnail images
     - Play button overlay
     - Purple titles and accent colors
     - Author avatars with names
     - 5-star rating system
     - Duration display

5. **Membership Section**
   - Dark background (#071629)
   - 4-column grid of membership benefits
   - Purple-tinted icons
   - Centered content with gradient button
   - Clean, modern card design

6. **FAQ Section**
   - White background
   - 2x2 grid layout (2 rows, 2 columns)
   - Bold questions with descriptive answers
   - Optimal spacing and readability

7. **Footer**
   - Dark background (#071629)
   - Logo on left, social media icons on right
   - Centered copyright text
   - Hover effects on social links

### Design Specifications

**Colors:**
- Primary Purple: #C271FF (gradient)
- Secondary Purple: #9356DC
- Dark Background: #071629
- White: #FFFFFF
- Text Dark: #071629
- Text Light: rgba(255, 255, 255, 0.7)

**Typography:**
- Font Family: 'Source Sans Pro' (from Google Fonts)
- Weights: 200, 300, 400, 600, 700, 900
- Responsive font sizes
- Proper line heights and letter spacing

**Layout:**
- Max width: 1100px
- Centered content
- Responsive grid systems
- Mobile-first approach

**Effects:**
- Smooth transitions (0.3s ease)
- Hover effects on buttons and links
- Gradient backgrounds
- Transform effects

## Technical Implementation

- **CSS Version:** CSS3
- **Methodology:** BEM-inspired naming convention
- **Layout:** Flexbox and CSS Grid
- **Responsive:** Mobile-first with breakpoints at 480px, 768px, 1024px
- **No Frameworks:** Pure CSS, no Bootstrap or libraries
- **Browser Support:** Modern browsers (Chrome, Firefox, Safari, Edge)

## Setup Instructions

1. Clone or download this repository
2. Ensure all image assets are in the `images/` folder
3. Open `index.html` in a modern web browser
4. Or deploy to GitHub Pages for live hosting

### Required Image Assets

The following images should be placed in an `images/` folder:
- `logo.png` - SmileSchool logo
- `background.png` - Hero background image
- `profile_1.png` - `profile_4.png` - Instructor avatars
- `avatar_testimonial.png` - Quote section avatar
- `video_thumbnail_1.png` - `video_thumbnail_4.png` - Video thumbnails
- `play_button.png` - Video play button overlay
- `star_on.png` - Filled star icon
- `star_off.png` - Empty star icon
- `smile_icon.png` - Membership benefit icon
- `facebook_icon.png` - Facebook social icon
- `twitter_icon.png` - Twitter social icon
- `instagram_icon.png` - Instagram social icon

## Design Reference

This implementation is based on the Figma design file:
[SmileSchool Figma Design](https://www.figma.com/design/NBnpjBTcwaUP2pQ3oj3SpD/Homepage?node-id=0-1&t=hYQM8l7vcPLsWiXv-1)

## Responsive Breakpoints

- **Desktop:** 1024px and above (4-column grids)
- **Tablet:** 768px - 1023px (2-column grids)
- **Mobile:** 480px - 767px (1-column grids)
- **Small Mobile:** Below 480px (optimized spacing)

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Brave (latest)

## Code Quality

- Clean, readable CSS with comments
- Organized sections for easy maintenance
- Consistent naming conventions
- Modular and reusable styles
- Proper indentation and formatting

## Performance

- Optimized CSS (no unused styles)
- Efficient selectors
- Minimal use of complex calculations
- Smooth animations with GPU acceleration
- Fast loading times

## Accessibility

- Proper color contrast ratios
- Hover states for interactive elements
- Semantic HTML structure
- Alt text for all images
- Keyboard navigation support

## Author

[Winebald Banituze](https://github.com/banituze)

## License

This project is part of an educational curriculum.

## Live Demo

https://banituze.github.io/alche-web-development/css_advanced
