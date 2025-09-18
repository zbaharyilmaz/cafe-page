# ☕ Cafebahz

## Modern Coffee Shop Website

Welcome to **Cafebahz**, a beautifully designed, responsive coffee shop website that brings the warmth and charm of a local café to the digital world!

### Website Demo

![Cafebahz Demo](/assets/demo/cafebahz.png)

_Interactive demo showcasing the responsive design, smooth animations, and modern UI of Cafebahz website._

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** (comes with Node.js)
- A modern web browser

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/zbaharyilmaz/cafebahz.git
   cd cafebahz
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Start development server**:

   ```bash
   # Development with live reload
   npm run dev

   # Or production server
   npm start
   ```

4. **Open your browser** and visit:
   ```
   http://localhost:5000
   ```

### Available Scripts

- `npm run dev` - Start development server with live reload
- `npm start` - Start production server
- `npm run build` - Build optimized assets for production
- `npm run lint` - Lint HTML files
- `npm run format` - Format code with Prettier

## ✨ Features

### 🎨 **Modern Design**

- **Responsive Layout**: Perfect on desktop, tablet, and mobile devices
- **Beautiful Typography**: Poppins for clean readability, Dancing Script for elegant headings
- **Smooth Animations**: Hover effects and transitions that delight users
- **Gradient Cards**: Eye-catching design elements with coffee-themed colors

### 📱 **Fully Responsive**

- Mobile-first approach
- Adaptive hero section with rotating cards
- Responsive image galleries
- Touch-friendly navigation

### 🖼️ **Interactive Elements**

- **Image Carousel**: Stunning coffee shop photos with smooth transitions
- **Menu Gallery**: Interactive tabs for Coffee, Food, and Desserts
- **Lightbox Gallery**: Click to view menu items in full size
- **Contact Form**: Clean, user-friendly contact section
- **Google Maps Integration**: Find us easily with embedded map

### 🎯 **Sections**

- **Hero Section**: Eye-catching carousel with brand messaging
- **About Us**: Story and history of Cafebahz
- **Meet the Team**: Staff profiles with social links
- **Our Menu**: Categorized menu with beautiful food photography
- **Contact**: Contact form and location information

## 📁 Project Structure

```
cafe-page/
├── assets/                # Source assets
│   ├── images/           # Image assets organized by category
│   │   ├── hero/         # Hero section images (sliders, about)
│   │   ├── icons/        # Icons and logos
│   │   ├── menu/         # Menu item images
│   │   │   ├── coffee/   # Coffee photos
│   │   │   ├── food/     # Food photos
│   │   │   └── dessert/  # Dessert photos
│   │   └── team/         # Team member photos
│   ├── scripts/          # Source JavaScript files
│   │   └── fslightbox.js # Lightbox functionality
│   └── styles/           # Source CSS files
│       └── style.css     # Main stylesheet
├── dist/                 # Built/optimized assets
│   ├── styles/           # Minified CSS
│   └── scripts/          # Minified JavaScript
├── demo/                 # Demo materials
│   └── Cafebahz-demo.gif  # Demo GIF (add your GIF here)
├── node_modules/         # Dependencies (auto-generated)
├── .gitignore           # Git ignore rules
├── .htmlhintrc          # HTML linting config
├── .prettierrc          # Code formatting config
├── favicon.ico          # Website favicon (ICO format)
├── favicon.svg          # Website favicon (SVG format)
├── package.json         # Node.js project config
├── postcss.config.js    # PostCSS config
├── README.md            # Project documentation
└── index.html           # Main HTML file
```
