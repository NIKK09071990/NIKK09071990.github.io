# Vibraspex Website

A modern, responsive website for Vibraspex, showcasing early detection and care technology solutions.

## Features

- Clean, modern design with a soothing color scheme
- Fully responsive layout
- Optimized for performance
- Semantic HTML5 structure
- Modern CSS with custom properties
- Smooth animations and transitions

## Project Structure

```
vibraspex/
├── index.html
├── styles/
│   └── main.css
├── images/
│   ├── vibraspex-logo.png
│   ├── hero-image.jpg
│   └── tech-image.jpg
└── README.md
```

## Setup Instructions

1. Clone this repository to your local machine
2. Replace the placeholder images in the `images/` directory with your own:
   - `vibraspex-logo.png`: Your company logo
   - `hero-image.jpg`: A high-quality hero image related to medical technology
   - `tech-image.jpg`: An image showcasing your technology
3. Customize the color scheme in `styles/main.css` by modifying the CSS custom properties in the `:root` selector
4. Update the content in `index.html` to match your specific needs

## Customization

### Colors

The website uses a soothing blue color scheme that can be easily customized by modifying the following CSS custom properties in `styles/main.css`:

```css
:root {
    --primary-color: #4A90E2;
    --secondary-color: #6BB9F0;
    --accent-color: #3498DB;
    --text-color: #2C3E50;
    --light-text: #7F8C8D;
    --background-color: #F5F7FA;
}
```

### Typography

The website uses the Poppins font family from Google Fonts. To change the font:

1. Update the Google Fonts link in the `<head>` section of `index.html`
2. Modify the `font-family` property in the `body` selector in `styles/main.css`

### Images

Replace the placeholder images with your own:

- Logo: 200x50px (recommended)
- Hero image: 1920x1080px (recommended)
- Technology image: 800x600px (recommended)

## Browser Support

The website is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is licensed under the MIT License - see the LICENSE file for details. 