# ForEco - Plastic Recycling Website

A modern, responsive website for ForEco Pvt Ltd, a plastic recycling company focused on sustainable waste management solutions. Built with HTML5, CSS3, and JavaScript using modern design patterns including glassmorphism effects and smooth animations.

## Installation

1. Clone or download the project
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

**Development:**
```bash
npm run dev
```

**Build for production:**
```bash
npm run build
```

**Preview production build:**
```bash
npm run preview
```

## Project Structure

```
├── index.html          # Main website file with all sections
├── style.css           # Additional custom styles (if any)
├── main.js            # Main JavaScript functionality
├── counter.js         # Counter animation logic
├── public/            # Static assets
│   ├── nature.svg     # Hero section illustration
│   └── vite.svg      # Vite icon
├── package.json       # Dependencies and scripts
└── .bolt/            # Bolt configuration files
```

## Key Features

- **Responsive Design**: 75% width container with mobile-first approach
- **Modern Animations**: AOS (Animate On Scroll) library integration
- **Glassmorphism Navbar**: Fixed navigation with blur effects
- **Interactive Gallery**: Filterable image gallery with modal view
- **Contact Form**: Client-side validation and file attachment support
- **Design System**: CSS custom properties for consistent theming

## Technologies Used

- **HTML5/CSS3/JavaScript** - Core web technologies
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Font Awesome** - Icon library
- **AOS Library** - Scroll animations
- **Vite** - Build tool and development server

## Contributing

- Follow existing CSS custom properties for consistent styling
- Maintain 75% width containers across all sections
- Test responsiveness on mobile, tablet, and desktop
- Keep animations subtle and performance-focused
- Use semantic HTML and accessible markup

## Notes

- All external dependencies are loaded via CDN
- Custom design tokens are defined in CSS `:root` variables
- Images are optimized and use lazy loading where appropriate
- Contact form currently uses client-side validation only
