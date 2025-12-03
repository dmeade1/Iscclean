# ISC Clean - Industrial Steam Cleaning Website

Professional website for ISC (Industrial Steam Cleaning), specializing in kitchen exhaust and ventilation cleaning services.

## Features

- Modern, Professional Design: Clean aesthetic with smooth animations
- Fully Responsive: Optimized for all devices (desktop, tablet, mobile)
- SEO Optimized: Proper meta tags and semantic HTML structure
- Fast Loading: Minimal dependencies, optimized CSS
- Call-to-Action Focused: Multiple prominent phone CTAs for easy customer contact
- Navigation System: Consistent header across all pages with active states

## Pages

### Homepage (index.html)
- Hero section with animated steam effects
- Quick service overview cards
- Why professional cleaning matters section
- Comprehensive services grid
- Process timeline
- Call-to-action section

### About Page (about.html)
- Company history since 1979
- Employee standards and training
- Insurance coverage details
- Statistics and guarantees

### Services Page (services.html)
- Equipment Cleaning (24/7 availability)
- Kitchen Cleaning
- Hood & Duct Cleaning (NFPA 96 compliant)
- Concrete Cleaning
- Sticky service navigation for easy access

## Services Offered

- Hood Cleaning
- Duct Cleaning
- Fan & Rooftop Cleaning
- Equipment Cleaning (24/7)
- Kitchen Cleaning
- Concrete Cleaning
- Filter Exchange Services

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript**: Interactive navigation and smooth scrolling
- **Google Fonts**: Inter font family for clean typography
- **Vercel**: Hosting platform (optimized for deployment)

## Contact Information

**Phone**: 1-855-618-HOOD (4663)

## Deployment to Vercel

### Option 1: Vercel CLI (Recommended)

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Navigate to the project directory:
   ```bash
   cd ISCCleanSite
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts to complete deployment

### Option 2: Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign in or create account
3. Click "New Project"
4. Import Git Repository
5. Vercel will auto-deploy from the main branch

### Option 3: Git Integration (Current Setup)

This repository is already connected to GitHub at: https://github.com/dmeade1/Iscclean

1. Connect the GitHub repository to Vercel
2. Vercel will auto-deploy on every push to main branch
3. Access deployment settings through Vercel dashboard

## Project Structure

```
ISCCleanSite/
├── index.html              # Homepage
├── about.html              # About page
├── services.html           # Services page
├── styles.css              # Main stylesheet with navigation
├── about-styles.css        # About page specific styles
├── services-styles.css     # Services page specific styles
├── vercel.json             # Vercel configuration
└── README.md               # Documentation
```

## Design Features

- **Animated Steam Effect**: Custom CSS animations on hero section
- **Smooth Hover Effects**: Interactive cards and buttons
- **Color Scheme**: Professional blue (#0033A0) with orange accents
- **Typography**: Inter font family for modern, clean look
- **Grid Layouts**: Responsive service and feature cards
- **Fixed Navigation**: Sticky header with scroll effects
- **Active States**: Visual feedback for current page

## Customization

To customize the website:

1. **Colors**: Edit CSS variables in `styles.css` under `:root`
2. **Content**: Modify text directly in HTML files
3. **Phone Number**: Search and replace `1-855-618-4663` throughout all files
4. **Fonts**: Change Google Fonts link in HTML files
5. **Navigation**: Update links in header section across all pages

## Performance

- Minimal external dependencies
- Optimized CSS with no frameworks
- Fast page load times
- Mobile-first responsive design
- Smooth scrolling with proper offset handling

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Development

To run locally for testing:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

---

© 2024 ISC Clean - Industrial Steam Cleaning
