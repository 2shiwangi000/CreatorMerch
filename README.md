# Creator Shop - React Application

A modern React application for a creator merchandise shop, converted from the original HTML/CSS/JavaScript implementation.

## Features

- **Hero Section** - Eye-catching landing section with call-to-action buttons
- **Featured Creators** - Dynamic display of creator profiles and merchandise
- **Shop by Category** - Browse products by category (Apparel, Tech Accessories, Home Decor, Gaming Gear)
- **Trending Products** - Showcase of popular products with ratings and wishlist functionality
- **Community Showcase** - Gallery of community photos
- **Contact Form** - Fully validated contact form with real-time error handling
- **Responsive Design** - Mobile-first design using Tailwind CSS

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

The application will open at [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## Project Structure

```
creator-shop/
├── public/
│   ├── index.html
│   ├── featuredCreators.json
│   ├── shopByCategory.json
│   └── trendingProducts.json
├── src/
│   ├── components/
│   │   ├── Navbar.js
│   │   ├── Hero.js
│   │   ├── FeaturedCreators.js
│   │   ├── Categories.js
│   │   ├── TrendingProducts.js
│   │   ├── CommunityShowcase.js
│   │   ├── ContactForm.js
│   │   └── Footer.js
│   ├── App.js
│   ├── index.js
│   └── index.css
├── package.json
├── tailwind.config.js
└── postcss.config.js
```

## Technologies Used

- **React 18** - UI library
- **Tailwind CSS 3** - Utility-first CSS framework
- **Remix Icon** - Icon library
- **Google Fonts** - Pacifico font

## Features Implementation

- All interactive features from the original HTML version
- React hooks for state management
- Form validation with real-time error messages
- Wishlist toggle functionality
- Responsive navigation with scroll effects
- Dynamic data loading from JSON files

## License

This project is for educational purposes.

