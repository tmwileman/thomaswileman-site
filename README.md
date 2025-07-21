# Personal Website

A clean, minimalist personal website for technical writing, book reviews, and general musings on machine learning and data science. Inspired by academic and professional portfolios with a focus on content and readability.

## 🚀 Live Site

Visit the website at: `https://[your-username].github.io/[repository-name]`

## 📋 Project Overview

This is a static website built with vanilla HTML, CSS, and JavaScript, designed for:
- **Technical Writing**: Blog posts about machine learning, data science, and software engineering
- **Book Reviews**: Thoughtful reviews and recommendations
- **General Musings**: Personal reflections and insights
- **Professional Portfolio**: Showcase of work and expertise

## 🛠 Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Hosting**: GitHub Pages
- **Development**: Claude Code for AI-assisted development
- **Version Control**: Git/GitHub

## 📁 Project Structure

```
personal-website/
├── index.html              # Homepage
├── blog/                   # Blog section
│   ├── index.html          # Blog listing
│   └── posts/              # Individual blog posts
│       ├── post-1.html
│       └── post-2.html
├── books/                  # Book reviews
│   └── index.html
├── about/                  # About page
│   └── index.html
├── assets/                 # Static assets
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   └── main.js         # JavaScript functionality
│   └── images/             # Image assets
├── README.md               # This file
├── claude.md               # Development workflow
└── _config.yml             # GitHub Pages config
```

## 🚀 Getting Started

### Prerequisites
- Git installed on your machine
- A text editor or IDE
- Python 3 or Node.js (for local development server)

### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/[your-username]/[repository-name].git
   cd [repository-name]
   ```

2. **Serve locally**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # OR using Node.js
   npx serve .
   ```

3. **Open in browser**
   Navigate to `http://localhost:8000`

## 📝 Content Management

### Adding New Blog Posts
1. Create a new HTML file in `blog/posts/`
2. Follow the existing template structure
3. Update the blog index page to include the new post
4. Commit and push changes

### Adding Book Reviews
1. Create content in the `books/` section
2. Follow the established format for consistency
3. Update navigation if needed

### Updating Existing Content
1. Edit the relevant HTML files
2. Test changes locally
3. Deploy via git push

## 🎨 Design Philosophy

The website follows these design principles:
- **Minimalism**: Clean, uncluttered interface
- **Readability**: Typography and spacing optimized for long-form reading
- **Accessibility**: Semantic HTML and proper contrast ratios
- **Responsiveness**: Works well on desktop, tablet, and mobile
- **Performance**: Fast loading times with optimized assets

## 🔧 Development Workflow

### Using Claude Code
This project is optimized for development with Claude Code. See `claude.md` for detailed workflows and best practices.

### Local Development
```bash
# Make changes to files
# Test locally
python -m http.server 8000

# Commit changes
git add .
git commit -m "Descriptive commit message"

# Deploy to GitHub Pages
git push origin main
```

### Deployment
The site automatically deploys to GitHub Pages when you push to the main branch. No build process required.

## 📊 Features

- **Responsive Design**: Mobile-first approach
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Minimal dependencies and optimized assets
- **Accessible**: WCAG compliant design
- **Clean URLs**: Organized structure for easy navigation

## 🤝 Contributing

This is a personal website, but if you notice any issues:
1. Open an issue describing the problem
2. Or submit a pull request with fixes

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🛠 Maintenance

### Regular Tasks
- **Content Updates**: Add new posts and reviews regularly
- **Link Checking**: Verify external links are still active
- **Performance**: Monitor and optimize loading speeds
- **SEO**: Update meta descriptions and titles as needed

### Troubleshooting
- **Site not updating**: Check GitHub Pages settings and build status
- **Styling issues**: Verify CSS file paths and browser cache
- **Mobile problems**: Test responsive design on multiple devices

## 📞 Contact

For questions about this website or its content, reach out via:
- **Email**: [your-email@example.com]
- **GitHub**: [@your-username]
- **LinkedIn**: [your-linkedin-profile]

---

*Built using Claude Code and GitHub Pages*