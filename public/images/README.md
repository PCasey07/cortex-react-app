# Images & Icons Directory

This directory contains all static images and icons used in the Dash DesAI application.

## Directory Structure

```
public/images/
├── logos/          # Brand logos and main application logos
├── icons/          # App icons, favicons, and UI icons
└── README.md       # This file
```

## Usage

### Logos
- Place the main "DASH THRU DATA AI" logo with snowboarding character here
- Recommended filename: `dash-logo.png` or `dash-logo.svg`
- Use in React components with: `/images/logos/dash-logo.png`

### Icons
- Place UI icons, favicons, and other small graphics here
- Use consistent naming convention (kebab-case)
- Common files: `favicon.ico`, `app-icon.png`, etc.

## File Naming Convention

- Use kebab-case for all file names
- Include descriptive names
- Add size suffixes when needed (e.g., `logo-32x32.png`)

## Integration with React

Since these files are in the `public` directory, reference them directly:

```jsx
// In React components
<img src="/images/logos/dash-logo.png" alt="Dash DesAI Logo" />

// In CSS/styling
background-image: url('/images/icons/background-pattern.png');
```

## TODO

- [ ] Add the "Dash DesAI" logo with snowboarding character
- [ ] Add favicon and app icons
- [ ] Optimize images for web (WebP format where supported)
- [ ] Consider SVG versions for scalability

