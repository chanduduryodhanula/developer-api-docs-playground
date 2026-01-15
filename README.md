# Developer API Documentation & Playground

A clean, professional static website for API documentation built with pure HTML and CSS. This project demonstrates best practices in developer relations (DevRel) by providing an accessible, well-structured documentation experience.

## Project Purpose

This project serves as a **Developer Relations (DevRel) focused** API documentation website. The primary goal is to improve developer experience (DX) by providing:

- **Clear, accessible documentation** that helps developers understand and integrate with APIs quickly
- **Copy-friendly code examples** that developers can easily use in their projects
- **Responsive design** that works seamlessly across all devices
- **Professional presentation** that builds trust and confidence in the API

## How This Improves Developer Experience

### 1. **Accessibility & Usability**
- High contrast color schemes ensure readability for all developers
- Semantic HTML structure improves screen reader compatibility
- Mobile-responsive design allows developers to access documentation on any device

### 2. **Developer-Friendly Code Blocks**
- Styled code blocks with proper syntax highlighting colors
- Easy-to-copy code examples with proper formatting
- Real-world request/response examples that developers can use immediately

### 3. **Clear Information Architecture**
- Logical flow from getting started to advanced topics
- Visual hierarchy with method badges (POST, GET, PUT, DELETE)
- Error code documentation with examples for troubleshooting

### 4. **Performance & Simplicity**
- Zero JavaScript means fast page loads
- No external dependencies reduces complexity
- Static HTML/CSS ensures compatibility across all browsers

### 5. **Professional Presentation**
- Clean, modern design that reflects quality
- Consistent spacing and typography
- Visual indicators (method badges, error codes) for quick scanning

## Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Semantic HTML5 structure
- ✅ CSS3 with Flexbox for layout
- ✅ Accessible color contrast ratios
- ✅ Copy-friendly code blocks
- ✅ No JavaScript dependencies
- ✅ No external libraries or frameworks
- ✅ Print-friendly styles

## File Structure

```
.
├── index.html      # Main HTML document
├── styles.css      # All styling and responsive design
└── README.md       # Project documentation
```

## How to Deploy Using GitHub Pages

### Option 1: Deploy from Repository Root

1. **Push your code to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: API documentation website"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on **Settings** tab
   - Scroll down to **Pages** section
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

3. **Access your site:**
   - Your site will be available at: `https://yourusername.github.io/your-repo-name/`
   - GitHub Pages typically takes 1-2 minutes to deploy

### Option 2: Deploy from `docs` Folder

If you prefer to keep documentation in a `docs` folder:

1. Create a `docs` folder in your repository
2. Move `index.html` and `styles.css` into the `docs` folder
3. In GitHub Pages settings, select **/docs** folder instead of root
4. Your site will be available at the same URL

### Option 3: Deploy Using GitHub Actions (Optional)

For automated deployments, you can set up a GitHub Actions workflow, though this is optional since the site is static.

## Local Development

To view the website locally:

1. **Simple HTTP Server (Python):**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

2. **Node.js HTTP Server:**
   ```bash
   npx http-server
   ```

3. **Open in Browser:**
   - Navigate to `http://localhost:8000` (or the port shown)
   - Or simply open `index.html` directly in your browser

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --text-primary: #1e293b;
    /* ... other variables */
}
```

### Content
Modify the HTML in `index.html` to match your API:
- Update endpoint paths and methods
- Replace example requests/responses
- Customize error codes and messages
- Update footer links

### Styling
All styles are in `styles.css`:
- Responsive breakpoints at 768px and 480px
- Reusable CSS classes
- No inline styles

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source and available for use in your own projects.

## Contributing

Feel free to fork this project and customize it for your own API documentation needs. If you make improvements that could benefit others, consider submitting a pull request.

---

**Built for developers, by developers** 🚀
