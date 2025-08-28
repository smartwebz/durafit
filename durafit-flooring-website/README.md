# DURAFIT FLOORING Website

A modern, responsive website for DURAFIT FLOORING company featuring a professional design based on the company's logo colors and branding.

## 🎨 Design Theme

The website is designed around the DURAFIT FLOORING logo with:
- **Primary Orange**: #FF6B35 (from the logo mark)
- **Primary Blue**: #1E3A8A (from "DURAFIT" text)
- **Primary Grey**: #374151 (from "FLOORING" text and tagline)
- **Tagline**: "PRECISION FLOORING, LASTING QUALITY"

## 🚀 Features

### Core Sections
- **Hero Banner**: Eye-catching landing section with call-to-action buttons
- **Products Section**: 6 flooring products with pricing per square meter
- **Testimonials Carousel**: Customer reviews with auto-advancing slides
- **About Us**: Company information and key features
- **Gallery**: Project showcase with hover effects
- **Contact Form**: Interactive contact form with validation

### Interactive Features
- **Responsive Design**: Mobile-first approach with hamburger menu
- **Smooth Scrolling**: Navigation links with smooth scroll behavior
- **Price Calculator**: Interactive pricing calculator for each product
- **Form Validation**: Contact form with email validation
- **Animations**: Scroll-triggered animations and hover effects
- **Back to Top**: Floating back-to-top button
- **Auto Carousel**: Testimonials automatically advance every 5 seconds

### Product Pricing
- **Hardwood Flooring**: From $45/m²
- **Luxury Vinyl Planks**: From $28/m²
- **Engineered Wood**: From $35/m²
- **Laminate Flooring**: From $22/m²
- **Ceramic Tiles**: From $32/m²
- **Premium Carpet**: From $18/m²

## 📁 File Structure

```
durafit-flooring-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Setup Instructions

### Option 1: Simple Setup (Recommended)
1. Download or clone the project files
2. Open `index.html` in any modern web browser
3. The website is ready to use!

### Option 2: Local Server (For Development)
1. Navigate to the project directory in terminal:
   ```bash
   cd durafit-flooring-website
   ```

2. Start a local server using Python:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

3. Open your browser and go to: `http://localhost:8000`

### Option 3: Using Node.js
1. Install a simple HTTP server:
   ```bash
   npm install -g http-server
   ```

2. Navigate to the project directory and run:
   ```bash
   http-server
   ```

## 🎯 Key Features Explained

### Logo Design
The website logo recreates the original design with:
- Orange "D" mark with subtle detail line
- "DURAFIT" in dark blue
- "FLOORING" in dark grey
- Company tagline below

### Responsive Navigation
- Fixed navigation bar with scroll effects
- Mobile hamburger menu
- Smooth scrolling to sections
- Active link highlighting

### Product Showcase
- Grid layout with hover animations
- Feature tags for each product
- Interactive price calculator
- Call-to-action buttons

### Testimonials Carousel
- Auto-advancing slides (5-second intervals)
- Manual navigation with arrows and dots
- Smooth fade transitions
- Star ratings display

### Contact Form
- Form validation for required fields
- Email format validation
- Service selection dropdown
- Success message simulation

## 🎨 Customization

### Colors
To modify the color scheme, update the CSS variables in `styles.css`:
```css
:root {
    --primary-orange: #FF6B35;
    --primary-blue: #1E3A8A;
    --primary-grey: #374151;
    /* ... other variables */
}
```

### Content
- Update product information in `index.html`
- Modify pricing in both HTML and JavaScript
- Replace placeholder images with actual product photos
- Update contact information and business details

### Styling
- Modify fonts by changing the Google Fonts import
- Adjust spacing and layout in CSS
- Customize animations and transitions
- Update responsive breakpoints

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

### Performance Features
- Optimized CSS with CSS custom properties
- Efficient JavaScript with event delegation
- Smooth animations with CSS transitions
- Responsive images (placeholder for actual implementation)

### Accessibility
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images (when implemented)
- Keyboard navigation support
- Screen reader friendly

## 📞 Contact Information

The website includes placeholder contact information:
- **Phone**: (555) 123-4567
- **Email**: info@durafitflooring.com
- **Address**: 123 Flooring Street, City, State 12345
- **Hours**: Mon-Fri: 8AM-6PM, Sat: 9AM-4PM

## 🚀 Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload the project files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop the project folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on push

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts

## 📝 License

This project is created for DURAFIT FLOORING company. All rights reserved.

## 🤝 Support

For technical support or customization requests, please contact the development team.

---

**DURAFIT FLOORING** - Precision Flooring, Lasting Quality
