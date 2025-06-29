# Amazon Clone

A responsive Amazon e-commerce website clone built with HTML, CSS, and JavaScript. This project replicates the core design and layout of Amazon's homepage with interactive features and modern styling.

##Live Demo: 
🌐 https://gilded-baklava-4e4a69.netlify.app/
## 🚀 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Product Categories**: Multiple product category boxes with hover effects
- **Interactive Elements**:
  - Hover effects on navigation items
  - Search bar with category dropdown
  - Shopping cart icon
  - Double-click heart animation
- **Preloader**: Loading animation with properly sized GIF for better user experience
- **Footer**: Complete footer with multiple panels and links
- **Organized Assets**: All images and media files properly organized in an assets folder
- **Mobile-First Approach**: Optimized for all screen sizes with progressive enhancement

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**:
  - Flexbox for responsive layouts
  - CSS Grid for complex layouts
  - Custom animations and transitions
  - Hover effects and interactive styling
- **JavaScript**:
  - DOM manipulation
  - Event handling
  - Interactive animations
- **Font Awesome**: Icons for navigation and UI elements

## 📁 Project Structure

```
AmazonClone/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet
├── script.js           # JavaScript functionality
├── Heart.css           # Heart animation styles
├── README.md           # Project documentation
├── assets/             # All images and media files
│   ├── amazon_logo.png     # Amazon logo image
│   ├── hero_image.jpg      # Hero section background
│   ├── box1_image.jpg      # Product category images
│   ├── box2_image.jpg
│   ├── box3_image.jpg
│   ├── box4_image.jpg
│   ├── box5_image.jpg
│   ├── box6_image.jpg
│   ├── box7_image.jpg
│   ├── box8_image.jpg
│   ├── box9_image.jpg
│   ├── box10_image.jpg
│   ├── box11_image.jpg
│   ├── box1.jpg
│   ├── box2.jpg
│   ├── box3.jpg
│   ├── box4.jpg
│   ├── box5.jpg
│   ├── 681dd2c6e0f1b52a9a5dc7c995b14ef2.gif  # Animation GIFs
│   ├── icegif-1264.gif
│   ├── shop.gif
│   └── suchi-action.gif
└── Amazon_clone/       # Git repository folder
```

## 🎯 Key Components

### Navigation Bar

- Amazon logo
- Delivery address selector
- Search bar with category dropdown
- Sign-in/Account section
- Returns & Orders
- Shopping cart

### Hero Section

- Background image with overlay message
- Link to Amazon India

### Product Categories

- 8 different product category boxes
- Each box includes:
  - Category title
  - Product image
  - "See more" link
- Responsive grid layout

### Footer

- Multiple panels with links
- Back to top functionality
- Copyright information

### Preloader

- Loading animation with shopping cart GIF
- Properly sized at 50% for optimal visibility
- Full-screen overlay during page load

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required


## 🎨 Customization

### Adding New Product Categories

1. Add a new `<div class="box">` in the shop section
2. Include the category title, image, and "See more" link
3. Add corresponding CSS styles if needed
4. Place new images in the `assets/` folder

### Modifying Colors

- Main colors are defined in CSS variables
- Primary: `#0f1111` (dark)
- Secondary: `#febd68` (orange)
- Background: `#e2e7e6` (light gray)

### Adding New Features

- JavaScript functionality is in `script.js`
- CSS animations are in `Heart.css`
- Main styles are in `style.css`

### Managing Assets

- All images and media files are stored in the `assets/` folder
- When adding new images, place them in the assets folder
- Update image paths in HTML/CSS to include `assets/` prefix
- Supported formats: JPG, PNG, GIF

## 📱 Responsive Design

The website is fully responsive and includes:

- **Mobile-First Approach**: Designed for mobile devices first, then enhanced for larger screens
- **Flexible Layouts**: Using CSS Flexbox for responsive layouts
- **Responsive Images**: Images that scale properly across all devices
- **Touch-Friendly Navigation**: Optimized for touch interactions on mobile devices
- **Progressive Enhancement**: Features that work on all devices with enhanced functionality on larger screens


## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+



## 👨‍💻 Author

**Your Name**

- GitHub: [@11PRIA](https://github.com/11PRIA)

## 🙏 Acknowledgments

- Amazon for the original design inspiration
- Font Awesome for the icons
- The web development community for resources and tutorials

---

**Note**: This is a frontend-only clone for educational purposes. It does not include backend functionality, real e-commerce features, or actual product data.
