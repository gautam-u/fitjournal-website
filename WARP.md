# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

This is the official website for FitJournal, an iOS fitness tracking app. The site is built with Jekyll and deployed via GitHub Pages, serving as the app's marketing site, privacy policy, and support portal.

**Tech Stack**: Jekyll 4.3.2, Sass, GitHub Pages
**Purpose**: iOS app marketing website with privacy policy and support pages
**Theme**: Custom design with modern CSS and Apple-inspired aesthetics

## Common Development Commands

### Local Development
```bash
# Install dependencies
bundle install

# Start local development server
bundle exec jekyll serve

# Build for production
bundle exec jekyll build

# Serve with live reload (if configured)
bundle exec jekyll serve --livereload

# Build and serve with drafts
bundle exec jekyll serve --drafts
```

### Development Workflow
```bash
# Check site structure
bundle exec jekyll build --verbose

# Clean build artifacts
bundle exec jekyll clean

# Build with specific environment
JEKYLL_ENV=production bundle exec jekyll build
```

## Architecture & Structure

### Core Layout System
The site uses a custom Jekyll layout structure:

- **`_layouts/default.html`**: Main template with comprehensive CSS-in-HTML design system
- **`_config.yml`**: Central configuration with app metadata, features list, and build settings
- **`index.md`**: Homepage with hero section, screenshots, and features grid

### CSS Architecture
- **Embedded CSS**: All styles are in `_layouts/default.html` using CSS custom properties
- **Design System**: Uses CSS variables for colors, spacing, typography, and layout
- **Responsive Design**: Mobile-first approach with breakpoints at 768px and 480px  
- **Dark Mode**: Automatic support via `prefers-color-scheme` media queries

### Content Structure
```
├── index.md                 # Homepage (hero, screenshots, features)
├── privacy-policy.md        # Comprehensive privacy policy
├── support.md              # Support page with FAQs
├── terms.md                # Terms of service
├── ios-app.md              # App-specific information
└── _config.yml             # Site configuration & features
```

### Key Configuration Pattern
Features are managed centrally in `_config.yml` with this structure:
```yaml
features:
  - title: "Feature Name"
    description: "Feature description"  
    fontawesome_icon_name: "icon-name"
```

### Asset Management
- **App Icons**: `/assets/app_icon.png` and `/assets/app-icon-large.png`
- **Screenshots**: Referenced in `index.md` but stored in `/assets/screenshots/`
- **GitHub Pages**: Configured for `url: "https://gautam-u.github.io"` with clean URLs

## Development Guidelines

### Adding New Features
1. Add feature to `_config.yml` features array
2. Feature automatically appears in homepage grid
3. Use FontAwesome icon names for consistency

### Styling Approach
- Modify CSS variables in `_layouts/default.html` for design changes
- Use existing utility classes (`.text-center`, `.mb-xl`, etc.)
- Follow the established color palette using CSS custom properties

### Content Updates
- App Store link: Update `appstore_link` in `_config.yml`
- Contact email: Update `email_address` in `_config.yml`
- App description: Update `app_description` in `_config.yml`

### Page Creation
New pages should:
1. Include proper frontmatter with `layout: default`
2. Use `include_in_header: true` to appear in navigation
3. Follow established content structure with cards and grid layouts
4. Set appropriate `permalink` for clean URLs

### Responsive Considerations
- Screenshots grid: 4 columns → 2 columns (tablet) → 1 column (mobile)
- Features grid: 3 columns → responsive auto-fit with 250px minimum
- Navigation: Hidden on mobile (simplified approach)
- All spacing uses CSS custom properties for consistency

This Jekyll site prioritizes clean, modern design with strong privacy messaging and seamless mobile experience.
