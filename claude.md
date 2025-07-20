# Personal Website Development Workflow

This document outlines the standard workflow for developing and maintaining this personal website using Claude Code and GitHub Pages.

## Project Structure

```
personal-website/
├── index.html              # Main homepage
├── blog/                   # Blog posts directory
│   ├── index.html          # Blog listing page
│   └── posts/              # Individual blog posts
├── books/                  # Book reviews section
│   └── index.html          # Book reviews listing
├── about/                  # About page
│   └── index.html
├── assets/                 # Static assets
│   ├── css/
│   ├── js/
│   └── images/
├── README.md               # Project documentation
├── claude.md               # This workflow file
└── _config.yml             # GitHub Pages configuration
```

## Development Workflow

### 1. Content Creation
- **Blog Posts**: Create new HTML files in `blog/posts/` directory
- **Book Reviews**: Add new reviews to `books/` section
- **General Updates**: Modify existing pages as needed

### 2. Using Claude Code for Development
When working with Claude Code, use these prompts and patterns:

#### Adding New Blog Posts
```
Create a new blog post about [topic] for my personal website. 
The post should:
- Follow the existing HTML structure and CSS styling
- Include proper meta tags and SEO
- Have a clean, readable layout similar to huyenchip.com
- Include navigation back to the blog index
```

#### Updating Existing Content
```
Update the [specific page/section] to [describe changes needed].
Maintain consistency with the existing design and navigation structure.
```

#### Design Improvements
```
Improve the CSS styling for [specific component/page] to:
- Enhance readability
- Maintain the clean, academic aesthetic
- Ensure responsive design
- Follow modern web standards
```

### 3. Local Development
```bash
# Clone the repository
git clone [your-repo-url]
cd personal-website

# Serve locally (Python 3)
python -m http.server 8000

# Or serve locally (Node.js)
npx serve .

# View at http://localhost:8000
```

### 4. Content Guidelines
- **Technical Writing**: Focus on clear explanations, code examples, and practical insights
- **Book Reviews**: Include key takeaways, ratings, and personal reflections
- **General Musings**: Keep authentic voice while maintaining professional tone
- **SEO**: Use descriptive titles, meta descriptions, and proper heading structure

### 5. Deployment Process
```bash
# 1. Make changes locally
# 2. Test thoroughly
# 3. Commit changes
git add .
git commit -m "Add new blog post: [title]"

# 4. Push to GitHub
git push origin main

# 5. GitHub Pages will automatically deploy
# Site will be live at: https://[username].github.io/[repository-name]
```

### 6. Regular Maintenance Tasks
- **Monthly**: Review and update outdated content
- **Quarterly**: Check for broken links and update dependencies
- **As needed**: Optimize images and improve page load speeds
- **Annually**: Review overall site structure and design

## Claude Code Best Practices

### File Organization
- Keep related files together
- Use descriptive file names
- Maintain consistent directory structure
- Document any non-obvious file purposes

### Code Quality
- Write semantic HTML
- Use clean, maintainable CSS
- Optimize for performance
- Ensure accessibility compliance

### Content Management
- Keep a content calendar for regular posting
- Maintain consistent formatting across posts
- Use proper heading hierarchy (h1, h2, h3, etc.)
- Include internal linking between related posts

## Troubleshooting

### Common Issues
1. **CSS not loading**: Check file paths and case sensitivity
2. **Images not displaying**: Verify image paths and file extensions
3. **GitHub Pages not updating**: Check repository settings and build status
4. **Mobile responsiveness**: Test on multiple device sizes

### When to Use Claude Code
- Creating new pages or blog posts
- Implementing design changes
- Adding new features or sections
- Debugging layout issues
- Optimizing existing code

## Future Enhancements
- Add RSS feed for blog posts
- Implement search functionality
- Add commenting system
- Include social media integration
- Set up analytics tracking
