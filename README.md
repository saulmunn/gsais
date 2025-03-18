# Guaranteed Safe AI Summit Website

This repository contains a simple, static HTML website for the Guaranteed Safe AI Summit (GSAIS). The website is designed to be clean, professional, and easy to maintain.

## Website Structure

The website consists of:

- `index.html` - The main (and only) HTML file containing all the content and styling
- This README.md file

## Features

- Clean, professional design with responsive layout
- Navigation menu for easy access to different sections
- Sections for:
  - About the Summit
  - GSAI Research description
  - Organizers (with hyperlinks to personal websites)
  - Sponsors
- Mobile-friendly design
- Embedded CSS (no external dependencies)

## How to Use

### Viewing the Website Locally

1. Clone or download this repository
2. Open the `index.html` file in any modern web browser

### Making Changes

The website is designed to be easily maintained and updated:

1. **Content Changes**: Simply edit the text within the HTML tags in the `index.html` file
2. **Style Changes**: Modify the CSS in the `<style>` section at the top of the `index.html` file
3. **Adding Sections**: Copy an existing section structure and update the content as needed
4. **Updating Hyperlinks**: The organizers' names include hyperlinks to their personal websites. You can update these by modifying the `href` attribute in the corresponding `<a>` tags.

### Deploying the Website

This is a static website that can be deployed to any web hosting service:

1. Upload the `index.html` file to your web server
2. No database or server-side processing is required

## Customization Options

### Colors

The website uses CSS variables for colors. You can easily change the color scheme by modifying these variables in the CSS:

```css
:root {
  --primary-color: #2c3e50;
  --secondary-color: #3498db;
  --accent-color: #27ae60;
  --light-color: #ecf0f1;
  --dark-color: #2c3e50;
}
```

### Adding Images

If you want to add images to the website:

1. Create an `img` folder in the same directory as the `index.html` file
2. Add your images to this folder
3. Reference them in the HTML using relative paths, e.g., `<img src="img/logo.png" alt="GSAIS Logo">`

## License

This website template is available for use by the Guaranteed Safe AI Summit organization.

## Contact

For more information, please contact info@gsais.org (placeholder email).
