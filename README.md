# Nitish Patil - Professional Portfolio

A modern, interactive portfolio website showcasing cybersecurity expertise, professional experience, and technical projects. Built with cutting-edge web technologies and featuring a cyberpunk-inspired aesthetic.

🌐 **Live Site**: [nitishpatil.co.in](https://nitishpatil.co.in)

## Overview

This portfolio demonstrates proficiency in modern web development practices, combining React's component architecture with Three.js for immersive 3D experiences. The project emphasizes performance, accessibility, and SEO.

## Key Features

### Interactive 3D Elements
- Custom 3D avatar with real-time mouse tracking using Three.js and React Three Fiber
- Smooth camera animations and lighting effects
- Optimized rendering for performance across devices

### Advanced Visual Effects
- **Matrix Code Background**: Procedurally generated animated background inspired by The Matrix
- **Custom Cursor**: Magnetic hover effects on interactive elements with smooth transitions
- **Parallax Scrolling**: Depth-based animations that respond to scroll position
- **Glitch Animations**: Cyberpunk-style text effects and transitions

### Technical Excellence
- **Fully Responsive**: Mobile-first design approach optimized for all screen sizes
- **SEO Optimized**: Semantic HTML5, meta tags, structured data (JSON-LD), and sitemap
- **Type-Safe**: Built entirely in TypeScript for enhanced code quality and maintainability
- **Performance Focused**: Code splitting, lazy loading, and optimized assets
- **Accessibility**: ARIA labels, semantic markup, and keyboard navigation support

## Technology Stack

### Core Framework
- **React 18** - Component-based UI architecture
- **TypeScript** - Type-safe development with enhanced IDE support
- **Vite** - Lightning-fast build tool and development server

### Styling & UI
- **Tailwind CSS** - Utility-first CSS framework with custom design tokens
- **shadcn/ui** - High-quality, accessible component library built on Radix UI
- **Custom CSS Animations** - Keyframe animations and transitions

### 3D Graphics
- **Three.js** - WebGL-powered 3D rendering
- **React Three Fiber** - React renderer for Three.js
- **@react-three/drei** - Useful helpers for R3F

### Additional Libraries
- **Lucide React** - Comprehensive icon library
- **React Router DOM** - Client-side routing
- **Custom React Hooks** - Reusable logic for animations and interactions

## Project Architecture

```
├── public/
│   ├── Nitish_Patil_Resume.pdf    # Professional resume
│   ├── robots.txt                  # Search engine crawler instructions
│   ├── sitemap.xml                 # SEO site structure
│   └── np.glb                      # 3D avatar model
├── src/
│   ├── components/                 # React components
│   │   ├── Hero.tsx               # Landing section with 3D avatar
│   │   ├── Experience.tsx         # Professional timeline
│   │   ├── Projects.tsx           # Project showcase
│   │   ├── Skills.tsx             # Technical skills display
│   │   ├── Education.tsx          # Academic background
│   │   ├── Certifications.tsx     # Professional certifications
│   │   ├── Contact.tsx            # Contact information
│   │   ├── Navigation.tsx         # Sticky navigation bar
│   │   ├── Avatar3D.tsx           # Three.js 3D avatar component
│   │   ├── MatrixCodeBackground.tsx  # Animated Matrix effect
│   │   ├── CustomCursor.tsx       # Interactive cursor component
│   │   └── ui/                    # Reusable UI components (shadcn/ui)
│   ├── hooks/                      # Custom React hooks
│   │   ├── useTypingEffect.tsx    # Typewriter animation
│   │   ├── useScrollReveal.tsx    # Scroll-triggered animations
│   │   ├── useParallaxScroll.tsx  # Parallax effect
│   │   ├── useMouseTracking3D.tsx # 3D object mouse tracking
│   │   └── useMatrixRain.tsx      # Matrix background logic
│   ├── pages/
│   │   ├── Index.tsx              # Main portfolio page
│   │   └── NotFound.tsx           # 404 error page
│   ├── lib/
│   │   └── utils.ts               # Utility functions
│   ├── index.css                   # Global styles & design tokens
│   └── main.tsx                    # Application entry point
├── .github/workflows/
│   └── deploy.yml                  # CI/CD pipeline configuration
└── vite.config.ts                  # Build configuration
```

## Design System

### Color Scheme
The portfolio uses a cyberpunk-inspired dark theme with custom HSL color variables defined in `src/index.css`. All colors are managed through CSS custom properties for consistency and easy theming.

### Typography
- **Headings**: Bold, attention-grabbing fonts with glitch effects
- **Body Text**: Highly readable sans-serif with optimized line height
- **Code**: Monospace font for technical content

### Component Variants
All UI components are built with shadcn/ui and customized with variants for different use cases, ensuring consistency across the portfolio.

## Development Setup

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager
- Git

### Local Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/patil-nitish/my-radiant-profile.git
   cd my-radiant-profile
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:8080
   ```

### Build for Production

```bash
npm run build
```

The optimized production build will be generated in the `dist/` directory.

## SEO Implementation

- ✅ Semantic HTML5 structure with proper heading hierarchy
- ✅ Open Graph meta tags for social media sharing
- ✅ Twitter Card meta tags
- ✅ JSON-LD structured data for rich snippets
- ✅ XML sitemap for search engine crawling
- ✅ Robots.txt for crawler directives
- ✅ Descriptive alt attributes on all images
- ✅ Mobile-responsive with proper viewport meta tags
- ✅ Fast loading times and optimized Core Web Vitals

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimizations

- Code splitting with React lazy loading
- Asset optimization (images, 3D models)
- CSS and JavaScript minification
- Tree shaking for minimal bundle size
- Efficient re-rendering with React best practices

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

**Nitish Patil**  
Cybersecurity Professional

- 🌐 Website: [nitishpatil.co.in](https://nitishpatil.co.in)
- 📧 Email: Available on website
- 💼 LinkedIn: Available on website
- 🐙 GitHub: [patil-nitish](https://github.com/patil-nitish)

---

**Built with cutting-edge web technologies - React, TypeScript, Three.js, and Tailwind CSS**