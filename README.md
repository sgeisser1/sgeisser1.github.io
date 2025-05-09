# Stephan Geisser - Personal CV Website

A clean, modern, and responsive personal CV website designed with Swiss Design principles. This project is ready to be deployed on GitHub Pages.

## Features

- **Responsive Design**: Works on all devices (mobile, tablet, desktop)
- **Dark/Light Mode**: Toggle between light and dark themes
- **Modern UI**: Inspired by Swiss Design principles (clean typography, strong grid layouts)
- **Interactive Elements**: Smooth scrolling, animations, and transitions
- **SEO Friendly**: Proper heading structure and semantic HTML

## Setup Instructions

### Option 1: Quick Setup (GitHub Pages)

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Set Source to "main" branch
5. Your site will be published at `https://[your-username].github.io/[repo-name]/`

### Option 2: Local Development

1. Clone this repository
2. Open `index.html` in your browser
3. Edit files as needed

## Customization

### Personal Information

Update your personal information in the `index.html` file:

- Name, contact details, and social links
- Education history
- Work experience
- Skills and interests

### Profile Picture

Replace the placeholder image by:
1. Adding your own image to the repository
2. Updating the image path in `index.html`:
```html
<img src="path/to/your-image.jpg" alt="Your Name">
```

### Colors and Styling

Customize the color scheme by modifying the CSS variables in `style.css`:

```css
:root {
  --accent-color: #f39c12; /* Main accent color */
  --accent-secondary: #e67e22; /* Secondary accent color */
  /* Other variables... */
}
```

## Project Structure

```
.
├── index.html         # Main HTML file
├── style.css          # CSS styles
├── README.md          # This readme file
└── images/            # (Optional) Add your images here
```

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (vanilla)
- Font Awesome for icons

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your personal website.

## Acknowledgments

- [Font Awesome](https://fontawesome.com/) for the icons
- [Google Fonts](https://fonts.google.com/) for the Inter font
