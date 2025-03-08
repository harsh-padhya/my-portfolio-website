# Portfolio Website

A modern, responsive portfolio website designed for a backend developer with 5 years of experience in FastAPI, Django, Flask, AWS, and microservices.

## Project Overview

This is a static portfolio website built with HTML, CSS, and vanilla JavaScript. The site is designed to be easily understood, modified, and extended by both human developers and AI agents.

## Project Structure

```
portfolio/
├── css/
│   └── styles.css       # Main stylesheet with CSS variables
├── js/
│   └── main.js          # JavaScript functionality
├── index.html           # Main HTML file containing all sections
├── .gitignore           # Git ignore file
├── .nojekyll            # File to disable Jekyll processing on GitHub Pages
├── LICENSE              # MIT License file
└── README.md            # This documentation file
```

## Features

- Fully responsive design that works on all devices
- Modern and elegant UI with smooth animations
- Sections for showcasing skills, experience, projects, and contact information
- Interactive elements like skill bars, project cards, and a contact form
- Optimized for performance and SEO
- Easy to customize and extend

## Component Breakdown

The website consists of the following main sections in `index.html`:

1. **Header/Navigation**: Contains the logo and navigation menu
2. **Hero Section**: Introduction with name, title, and call-to-action
3. **About Section**: Personal information and background
4. **Skills Section**: Technical skills with progress bars
5. **Experience Section**: Work history with timeline
6. **Projects Section**: Portfolio projects displayed as cards
7. **Testimonials Section**: Client/colleague testimonials as a slider
8. **Contact Section**: Contact form and information
9. **Footer**: Copyright information and social links

## Technologies Used

- HTML5
- CSS3 (with CSS variables for easy customization)
- JavaScript (vanilla, no frameworks)
- Font Awesome for icons
- Google Fonts (Poppins)

## For AI Agents

### Key Files and Their Purposes

- **index.html**: Contains the entire website structure and content. When making content changes, this is the primary file to modify.
- **css/styles.css**: Contains all styling with CSS variables defined at the top for easy theming. The file is organized by component sections.
- **js/main.js**: Contains all interactive functionality including mobile menu toggle, scroll animations, form validation, and more.

### Common Modification Tasks

1. **Updating Personal Information**:
   - Edit text content in `index.html` within the corresponding sections
   - Profile information is in the hero and about sections
   - Skills are in the skills section with percentage values
   - Projects are in the projects section as individual card elements

2. **Styling Changes**:
   - Primary colors and theme variables are at the top of `css/styles.css` in the `:root` selector
   - Each section has its own CSS block with clear comments
   - Media queries for responsive design are at the bottom of the file

3. **Adding New Sections**:
   - Create a new section in `index.html` following the existing pattern
   - Add corresponding CSS in `styles.css`
   - If needed, add JavaScript functionality in `main.js`

4. **Modifying Animations**:
   - Scroll animations are handled in `main.js` using the Intersection Observer API
   - CSS transitions and animations are defined in `styles.css`

### Images and Assets

The website uses URL-based images from online services instead of local image files:

- Profile picture: Using [RandomUsers](https://xsgames.co/randomusers/) service
- Project images: Using [DummyImage](https://dummyimage.com/) service with custom text and colors

To use custom images:
1. Replace the image URLs in the HTML with URLs to hosted images
2. Or create an `images` directory and update the image paths in the HTML

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

## Contributing Guidelines

When contributing to this project (especially for AI agents):

1. **Follow the existing code style and patterns**
2. **Maintain the responsive design** by testing changes on multiple screen sizes
3. **Keep accessibility in mind** by using semantic HTML and proper ARIA attributes
4. **Document any complex logic** with comments
5. **Optimize images and assets** for web performance
6. **Test all interactive elements** after making changes

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Font Awesome for the icons
- Google Fonts for the Poppins font
- Unsplash for placeholder images

---

Feel free to use this template for your personal portfolio. If you have any questions or suggestions, please open an issue or contact me. 