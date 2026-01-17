# Nur Travels - Manpower Agency Website

A modern, responsive static website for Nur Travels, a leading Bangladeshi manpower agency connecting talented workers with global opportunities.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on mobile, tablet, and desktop devices
- **Modern UI**: Clean, professional design with blue (#2B5AA0) and green (#2D7A4F) color scheme
- **Interactive Elements**: Smooth scrolling, form validation, mobile menu, and hover effects
- **Aviation Theme**: Professional imagery and design elements reflecting the travel and recruitment industry
- **Contact Form**: Client-side form validation for inquiries
- **Job Categories**: Easy access to different job vacancies
- **Service Showcase**: Comprehensive display of recruitment, visa, training, and travel services

## 📁 Project Structure

```
nur_travels/
├── index.html          # Main HTML file with all sections
├── css/
│   └── style.css       # Complete stylesheet with responsive design
├── js/
│   └── script.js       # JavaScript for interactivity and validation
├── images/             # Folder for local images (currently using Unsplash URLs)
└── README.md           # This file
```

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/raju-mechatronics/nur_travels.git
   cd nur_travels
   ```

2. **Open in browser**
   
   Simply open `index.html` in your web browser:
   - Double-click `index.html`, or
   - Right-click and select "Open with" your preferred browser

3. **Using a local server (recommended)**
   
   For better development experience, use a local server:

   **Using Python:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

   **Using Node.js (http-server):**
   ```bash
   npx http-server -p 8000
   ```

   **Using PHP:**
   ```bash
   php -S localhost:8000
   ```

   Then open `http://localhost:8000` in your browser.

## 🎨 Customization

### Updating Images

The website currently uses placeholder images from Unsplash. To use your own images:

1. Add your images to the `images/` folder
2. Update the image paths in `index.html`:
   - Hero background: `.hero` section background-image
   - Service cards: `.service-image img` src attributes
   - About section: `.about-image img` src attribute
   - Team section: `.team-image img` src attribute

### Updating Colors

Colors are defined as CSS variables in `css/style.css`:

```css
:root {
    --primary-blue: #2B5AA0;    /* Main brand color */
    --success-green: #2D7A4F;   /* Call-to-action buttons */
    --dark-blue: #1e3a5f;       /* Dark accents */
    /* ... other colors ... */
}
```

### Updating Content

- **Contact Information**: Update footer section in `index.html`
- **Job Categories**: Modify `.job-categories` section
- **Services**: Update `.service-cards` section
- **About Text**: Edit `.about-section` content

## 📱 Website Sections

1. **Header/Navigation** - Logo and main menu
2. **Hero Section** - Main banner with call-to-action buttons
3. **Who We Are & What We Do** - Company overview with three pillars
4. **Our Services** - Four service cards (Recruitment, Visa, Training, Travel)
5. **About Us** - Detailed company information with imagery
6. **Job Vacancies** - Quick access to job categories
7. **Documents Required** - Checklist of required documents
8. **Contact Form** - Get in touch form with validation
9. **Team Section** - Professional team showcase
10. **Footer** - Company info and social links

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **Vanilla JavaScript** - No frameworks required
- **Font Awesome** - Icons (loaded via CDN)

## 🌐 Deployment

### Deploy to GitHub Pages

1. Go to your repository settings on GitHub
2. Navigate to "Pages" section
3. Select source branch (main/master)
4. Click Save
5. Your site will be available at `https://raju-mechatronics.github.io/nur_travels/`

### Deploy to Netlify

1. Create account at [Netlify](https://www.netlify.com/)
2. Click "New site from Git"
3. Connect your GitHub repository
4. Click "Deploy site"

### Deploy to Vercel

1. Create account at [Vercel](https://vercel.com/)
2. Import your GitHub repository
3. Click "Deploy"

### Deploy to any hosting provider

Simply upload all files to your web hosting:
- `index.html`
- `css/` folder
- `js/` folder
- `images/` folder (if you've added local images)

## 🔧 Form Functionality

The contact form includes client-side validation for:
- Name (minimum 2 characters)
- Email (valid email format)
- Phone (minimum 10 digits)
- Message (minimum 10 characters)

To add server-side processing:
1. Add a backend endpoint (PHP, Node.js, etc.)
2. Update form submission in `js/script.js`
3. Replace the `alert()` with actual form submission

## 📝 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

Copyright © 2024 Nur Travels. All rights reserved.

## 👥 Support

For questions or support, please contact:
- Email: info@nurtravels.com
- Phone: +880-XXX-XXXXXX

## 🙏 Acknowledgments

- Images from [Unsplash](https://unsplash.com/)
- Icons from [Font Awesome](https://fontawesome.com/)

---

**Built with ❤️ for Nur Travels**