# VELORA

VELORA is a fashion e-commerce product showcase designed with a premium, timeless style.

## Project Features

### CSS Grid
CSS Grid is used to arrange the six product cards into three columns on larger screens.

### Flexbox
Flexbox is used in the navigation and hero section to arrange elements neatly.

### Responsive Design
A media query is used to change the layout on smaller screens. The product grid becomes one column, the hero section stacks vertically, and the filters adjust for mobile screens.

### Product Cards
Each product card contains:
- Product image
- Product name
- Price
- Rating
- Add to Cart button

Hover effects are used to make the cards move slightly and show a stronger shadow.

### Product Modal
The Siena Blazer has a product detail modal.

The modal uses the CSS `:target` pseudo-class, so it can open and close without JavaScript.

### Shopping Cart Sidebar
A static shopping cart sidebar is included.

It also uses `:target` to open and close without JavaScript.

### Filter and Sort UI
Category and sorting dropdowns are included to create a shopping interface.

The controls are UI only and do not require JavaScript.

### CSS Custom Properties
CSS variables are stored in `:root` for the main colors and shadow.

This makes it easier to keep the design consistent and change the theme.

### Dark Mode
The website uses `prefers-color-scheme: dark` to automatically change some colors when the user's device uses dark mode.

### Transitions
Transitions are used on links, buttons, and product cards to make hover effects smoother.

### Animation
`@keyframes` is used to create an entrance animation for the product cards.

The cards begin slightly lower and transparent before moving into their normal position.

### Print Styles
A `@media print` rule creates a cleaner version of the website for printing.

Navigation, buttons, filters, the cart, and modal are hidden when printing.

## Design System

### Colors
- Background: Antiquewhite
- Product cards: Beige
- Text: Brown
- Accent: Burgundy
- Borders: Light brown

### Typography
Georgia and Times New Roman are used as the main fonts to create a classic fashion-editorial appearance.

### Layout
The website uses Flexbox, CSS Grid, spacing, shadows, and responsive design to create the layout.

## Accessibility

Product images include alternative text to describe the images.

Labels are also provided for the category and sorting controls.

The color scheme was chosen to keep the text readable against the backgrounds.

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Media Queries
- CSS Variables
- CSS Animations
- CSS Pseudo-classes

## JavaScript

No JavaScript functionality was used for the main interactive components. The modal and cart sidebar use CSS `:target` instead.

## Conclusion

VELORA demonstrates how HTML and CSS can be used to create a responsive e-commerce product showcase with interactive visual features without relying on JavaScript.
## Browser Compatibility

VELORA was designed using standard HTML5 and CSS3 features including Flexbox, CSS Grid, media queries, transitions, animations, and CSS variables.

The website is intended to work with modern versions of Chrome, Edge, Firefox, and Safari.

The layout was checked at different screen sizes to ensure the responsive design works correctly.
## Performance

I organized the CSS into sections for different parts of the website, such as the navigation, hero section, product cards, modal, cart, responsive design, and themes.

CSS variables were used for repeated colors and shadows so the same values can be reused throughout the website.

The product images use fixed sizing and `object-fit` to keep the product cards consistent.

Animations and transitions were kept simple so they do not add unnecessary complexity to the page.

A Lighthouse audit was not completed during development, so no Lighthouse scores are included.# VELORA-FASHIONS
# VELORA-FASHIONS
# VELORA-FASHIONS
