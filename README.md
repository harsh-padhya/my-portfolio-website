# Portfolio Website

A modern, responsive portfolio website designed for a backend developer with 5 years of experience in FastAPI, Django, Flask, AWS, and microservices.

## Features

- Fully responsive design that works on all devices
- Modern and elegant UI with smooth animations
- Sections for showcasing skills, experience, projects, and contact information
- Interactive elements like skill bars, project cards, and a contact form
- Optimized for performance and SEO
- Easy to customize and extend

## Technologies Used

- HTML5
- CSS3 (with CSS variables for easy customization)
- JavaScript (vanilla, no frameworks)
- Font Awesome for icons
- Google Fonts (Poppins)

## Getting Started

### Prerequisites

- A web browser
- A code editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/portfolio.git
   ```

2. Navigate to the project directory:
   ```
   cd portfolio
   ```

3. Open `index.html` in your browser to view the website.

## Customization

### Personal Information

Edit the `index.html` file to update:
- Your name and title in the hero section
- About me information
- Skills and experience
- Project details
- Contact information

### Styling

The website uses CSS variables for easy customization. Open `css/styles.css` and modify the variables in the `:root` selector to change colors, fonts, etc.

```css
:root {
    --primary-color: #4a6cf7;
    --primary-dark: #3a56d4;
    /* other variables */
}
```

### Images

The website uses URL-based images from online services instead of local image files:

- Profile picture: Using [RandomUsers](https://xsgames.co/randomusers/) service
- Project images: Using [DummyImage](https://dummyimage.com/) service with custom text and colors

This approach eliminates the need to download and manage image files locally. If you want to use your own images, you can either:

1. Replace the image URLs in the HTML with URLs to your own hosted images
2. Download images and store them locally in the `images` directory, then update the image paths in the HTML

## Deployment

### GitHub Pages

This portfolio is designed to be easily deployed on GitHub Pages:

1. Push your code to a GitHub repository
2. Go to repository settings
3. Navigate to the "Pages" section
4. Select the main branch as the source
5. Your site will be published at `https://yourusername.github.io/portfolio/`

### Other Hosting Options

You can also deploy this website on any static site hosting service like:
- Netlify
- Vercel
- Firebase Hosting
- Amazon S3

## Browser Support

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Font Awesome for the icons
- Google Fonts for the Poppins font
- Unsplash for placeholder images

---

Feel free to use this template for your personal portfolio. If you have any questions or suggestions, please open an issue or contact me. 