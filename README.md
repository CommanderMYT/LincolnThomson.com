# LincolnThomson.com

A personal project hub website serving as a central homepage for all projects and initiatives.

## Overview

This website serves as a central hub for all my projects and can be extended to integrate with Odoo ERP system for enterprise-grade business management.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Project Cards**: Easy-to-extend grid layout for showcasing projects
- **Odoo Integration Ready**: Designed with Odoo ERP integration in mind
- **Modern UI**: Clean, professional design with smooth animations
- **GitHub Pages Compatible**: Ready for deployment on GitHub Pages

## Deployment

### GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/make-homepage-for-projects`)
4. Click "Save"
5. Your site will be published at `https://commandermyt.github.io/LincolnThomson.com/`

### Local Development

Simply open `index.html` in your web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Customization

### Adding New Projects

Edit `index.html` and add new project cards in the `projects-grid` section:

```html
<div class="project-card">
    <h3>Your Project Name</h3>
    <p>Project description goes here.</p>
    <div class="project-links">
        <a href="your-link" target="_blank" class="btn">View Project</a>
    </div>
</div>
```

### Odoo Integration

The Odoo integration section is ready for configuration. To connect to your Odoo instance:

1. Set up your Odoo server endpoint
2. Configure authentication credentials
3. Add Odoo API calls as needed in a JavaScript file

### Styling

Customize colors and styles in `styles.css`. The CSS uses CSS variables for easy theming:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    /* ... */
}
```

## License

See [LICENSE](LICENSE) file for details.