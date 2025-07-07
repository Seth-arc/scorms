# SCORM Learning Modules - William & Mary

Interactive e-learning modules for data journalism and development studies.

## 🌐 Live Demo

Visit the live site: [https://seth-arc.github.io/scorms/](https://seth-arc.github.io/scorms/)

## 📋 Available Modules

### Module 1: Data Fundamentals
- **Correlation vs Causation** - Statistical relationships and common pitfalls
- **Identifying and Mitigating Bias in Data** - Data quality and bias detection
- **Course Glossary** - Essential terminology and definitions
- **Development Finance Data Points** - Financial development indicators

### Module 2: Data Journalism
- **Media Integration in Data Journalism** - Multimedia storytelling techniques
- **Case Study Analysis** - Systematic scenario examination

### Module 4: Development Studies
- **Bilateral vs Multilateral Models** - International cooperation approaches
- **Decolonization and Development** - Post-colonial development perspectives
- **China Development Finance Strategy** - Belt and Road Initiative analysis

## 🚀 Features

- **Responsive Design** - Works on desktop, tablet, and mobile
- **Fast Loading** - Optimized performance with preloading
- **Transparent Background** - Seamless integration into any website
- **William & Mary Branding** - Consistent institutional identity
- **External Link Support** - Properly handles New York Times and other external content
- **Fullscreen Mode** - Immersive learning experience
- **Cross-Platform Compatibility** - Works across all modern browsers

## 📁 File Structure

```
/
├── index.html                           # Main entry point (redirects to embed-all-modules.html)
├── embed-all-modules.html              # Master interface with all modules
├── embed-correlation-causation.html    # Individual module embeds
├── embed-media-integration.html
├── embed-bilateral-multilateral.html
├── embed-bias-mitigation.html
├── embed-decolonization-development.html
├── embed-course-glossary.html
├── embed-development-finance-data.html
├── embed-china-development-finance.html
├── embed-case-study-analysis.html
├── Module 1/                           # SCORM content directories
│   ├── Correlation vs Causation/
│   ├── Course Glossary/
│   ├── Development Finance data points/
│   └── Identifying and Mitigating Bias in Data/
├── Module 2/
│   ├── Media Integration in Data Journalism/
│   └── Module 2 - Case Study Analysis/
└── Module 4/
    ├── Bilateral vs Multilateral Models/
    ├── China Development Finance Strategy_Menu/
    └── Decolonization and Development/
```

## 🔧 Deployment

### GitHub Pages Setup
1. Push all files to your repository's main branch
2. Go to repository Settings → Pages
3. Set Source to "Deploy from a branch"
4. Select "main" branch and "/ (root)" folder
5. Save and wait for deployment (usually 5-10 minutes)

### Custom Domain (Optional)
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Enable "Enforce HTTPS" in GitHub Pages settings

## 💻 Local Development

To test locally:

```bash
# Simple HTTP server (Python 3)
python -m http.server 8000

# Or with Node.js
npx http-server

# Then visit http://localhost:8000
```

## 🔗 Integration

### Embed Individual Modules
```html
<iframe src="https://seth-arc.github.io/scorms/embed-correlation-causation.html" 
        width="100%" height="600px" frameborder="0">
</iframe>
```

### Embed All Modules Interface
```html
<iframe src="https://seth-arc.github.io/scorms/" 
        width="100%" height="800px" frameborder="0">
</iframe>
```

## 🛠️ Technical Details

- **Framework**: Pure HTML/CSS/JavaScript (no dependencies)
- **SCORM Compatibility**: Supports SCORM 2004 modules
- **Performance**: Optimized with resource preloading and fast fallbacks
- **Security**: Sandboxed iframes with appropriate permissions
- **Accessibility**: Keyboard navigation and screen reader support

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🐛 Troubleshooting

### Common Issues

1. **404 Error**: Ensure `index.html` is in the repository root
2. **Modules Not Loading**: Check that Module directories are properly uploaded
3. **External Links Not Working**: Verify iframe sandbox permissions
4. **Slow Loading**: Enable browser caching and check network connection

### GitHub Pages Specific

- Allow 5-10 minutes for initial deployment
- Check GitHub Pages status in repository Settings
- Ensure all files are in the main branch root directory

## 📄 License

Educational use for William & Mary. See individual SCORM modules for specific licensing.

## 🤝 Support

For technical issues or questions, please contact the development team. 