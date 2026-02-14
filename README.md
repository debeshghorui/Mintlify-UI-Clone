# Mintlify - Documentation Website UI Clone

A frontend UI clone of the Mintlify documentation website, built as a learning project for the Web Development Cohort.

## Overview

This project replicates the visual design and layout of the Mintlify documentation platform. It showcases modern web design practices with a responsive, professional interface.

<img src="screenshot\Screenshot.png" alt="Mintlify UI Clone Screenshot" width="800">

## Features

- Clean, modern UI design
- navigation header with logo and menu items
- Call-to-action buttons for user engagement
- Smooth styling using custom CSS
- Professional typography with Google Fonts (Poppins & Roboto)
- Static documentation website layout

## Tech Stack

- **Frontend:** HTML5, CSS3
- **Build Tool:** Vite
- **Package Manager:** pnpm
- **Fonts:** Google Fonts (Poppins, Roboto)

## Project Structure

```
.
├── index.html          # Main HTML file with page structure
├── style.css           # Stylesheet for all components
├── package.json        # Project configuration and scripts
├── pnpm-lock.yaml      # Dependency lock file
├── public/             # Static assets directory
├── MediaAssets/        # Images and SVG assets (logos, icons)
└── node_modules/       # Installed dependencies
```

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd Mintlify-UI-Clone
```

2. Install dependencies using pnpm:

```bash
pnpm install
```

## Running the Project

### Development Server

Start the development server with hot module reloading:

```bash
pnpm run dev
```

The application will be available at `http://localhost:5173`

### Build for Production

Create an optimized production build:

```bash
pnpm run build
```

### Preview Production Build

Preview the production build locally:

```bash
pnpm run preview
```

## Page Structure

The main page includes:

- **Header:** Logo, navigation menu, and call-to-action buttons
- **Main Content:** Hero section with new features announcement and call-to-action
- **Navigation Items:** Resources, Documentation, Customers, Blog, Pricing
- **Buttons:** "Contact sales" and "Start for free" CTAs

## License

This project is created for educational purposes.
