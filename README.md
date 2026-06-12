# Lithos

An interactive geological exploration platform featuring smooth cursor reveal animations and beautiful hero section design.

## Features

- 🎨 Beautiful hero section with parallax background
- 🖱️ Smooth cursor-following spotlight reveal effect
- 📱 Fully responsive design (mobile, tablet, desktop)
- ⚡ Built with React, TypeScript, and Tailwind CSS
- 🎬 Smooth animations and transitions
- ♿ Accessible and semantic HTML

## Tech Stack

- **Frontend Framework**: React 18
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Icons**: Lucide React
- **Animation**: CSS Animations & Canvas

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/riansyah4886-lang/lithos.git
cd lithos
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The app will open at `http://localhost:3000`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
lithos/
├── src/
│   ├── App.tsx          # Main App component
│   ├── main.tsx         # React entry point
│   └── index.css        # Global styles and animations
├── index.html           # HTML template
├── vite.config.ts       # Vite configuration
├── tailwind.config.js   # Tailwind CSS config
├── tsconfig.json        # TypeScript config
└── package.json         # Project dependencies
```

## Key Components

### App Component
- Main landing page with navigation
- Hero section with animated text
- Cursor tracking for reveal effect

### RevealLayer Component
- Canvas-based spotlight effect
- Follows cursor movement
- Reveals second background image

## Animation Details

### Hero Animations
- **hero-anim**: Fade in from bottom with cubic bezier easing
- **hero-reveal**: Same as hero-anim with staggered delays
- **hero-fade**: Simple fade-in effect
- **hero-zoom**: Subtle zoom-out on page load

### Cursor Reveal
- Smooth tracking with 0.1 interpolation factor
- Radial gradient spotlight (260px radius)
- Masks second background image

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT

## Author

riansyah4886-lang
