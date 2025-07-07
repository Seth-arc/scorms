# SCORM Embeddable HTML Files

This directory contains embeddable HTML files for each SCORM module, making it easy to integrate your interactive learning content into websites, LMS systems, or other platforms.

## Available Embeddable Files

### Individual Module Embeds
- **`embed-correlation-causation.html`** - Correlation vs Causation module
- **`embed-bias-mitigation.html`** - Identifying and Mitigating Bias in Data module
- **`embed-course-glossary.html`** - Course Glossary module
- **`embed-development-finance-data.html`** - Development Finance Data Points module
- **`embed-media-integration.html`** - Media Integration in Data Journalism module
- **`embed-case-study-analysis.html`** - Case Study Analysis module
- **`embed-bilateral-multilateral.html`** - Bilateral vs Multilateral Models module
- **`embed-decolonization-development.html`** - Decolonization and Development module
- **`embed-china-development-finance.html`** - China Development Finance Strategy module

### Master Interface
- **`embed-all-modules.html`** - Complete interface with all modules accessible from one page

## Features

### 🎯 **Standalone Operation**
Each embeddable file is completely self-contained and can be used independently.

### 📱 **Responsive Design**
- Optimized for desktop, tablet, and mobile devices
- Adaptive layouts that work on any screen size
- Touch-friendly interface for mobile users

### 🔧 **Interactive Features**
- **Loading indicators** with animated spinners
- **Fullscreen mode** for immersive learning
- **Keyboard navigation** (ESC to close modals)
- **Cross-frame communication** for progress tracking

### 🎨 **Professional Styling**
- Modern, clean interface design
- Unique color schemes for each module
- Smooth animations and transitions
- Professional gradients and shadows

## Usage Instructions

### 1. **Direct Integration**
Simply upload any of the embeddable HTML files to your web server and link to them:

```html
<a href="embed-correlation-causation.html" target="_blank">
    Launch Correlation vs Causation Module
</a>
```

### 2. **Iframe Embedding**
Embed modules directly in your existing pages:

```html
<iframe 
    src="embed-correlation-causation.html" 
    width="100%" 
    height="700px" 
    frameborder="0"
    allow="fullscreen">
</iframe>
```

### 3. **LMS Integration**
These files work with most LMS platforms:
- **Moodle**: Upload as HTML resource or embed via iframe
- **Canvas**: Add as external tool or HTML page
- **Blackboard**: Insert as web link or content item
- **Google Classroom**: Share as web link

### 4. **Website Integration**
Add to any website by including the HTML file:
- WordPress: Upload to media library and embed
- Wix/Squarespace: Add as HTML embed
- Custom websites: Include directly in your pages

## Technical Specifications

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- **Lightweight**: Each embed file is under 15KB
- **Fast loading**: Optimized CSS and minimal JavaScript
- **Efficient**: Lazy loading with progress indicators

### SCORM Compliance
- **SCORM 2004** compatible
- **Progress tracking** via postMessage communication
- **Completion events** for learning analytics

## Customization Options

### Styling
You can customize the appearance by modifying the CSS in each file:
- Change colors by updating the gradient values
- Modify dimensions in the `.scorm-content` class
- Adjust responsive breakpoints in media queries

### Functionality
Extend functionality by adding JavaScript:
- Custom completion handlers
- Integration with analytics platforms
- Additional user interaction tracking

## File Structure Requirements

Ensure your SCORM modules maintain this structure:
```
/
├── Module 1/
│   ├── Correlation vs Causation/
│   │   └── story.html
│   ├── Identifying and Mitigating Bias in Data/
│   │   └── story.html
│   ├── Course Glossary/
│   │   └── story.html
│   └── Development Finance data points/
│       └── story.html
├── Module 2/
│   ├── Media Integration in Data Journalism/
│   │   └── story.html
│   └── Module 2 - Case Study Analysis/
│       └── story.html
├── Module 4/
│   ├── Bilateral vs Multilateral Models/
│   │   └── story.html
│   ├── Decolonization and Development/
│   │   └── story.html
│   └── China Development Finance Strategy_Menu/
│       └── story.html
└── [embeddable files]
```

## Security Considerations

- **Same-origin policy**: Modules must be hosted on the same domain
- **Content Security Policy**: Ensure iframe permissions are set correctly
- **HTTPS recommended**: For production environments

## Troubleshooting

### Common Issues
1. **Module not loading**: Check file paths in the iframe src attribute
2. **Responsive issues**: Verify viewport meta tag is present
3. **Fullscreen not working**: Ensure proper permissions in iframe allow attribute

### Support
For technical issues or customization help, check:
- Browser console for error messages
- Network tab for failed resource requests
- Ensure all module files are properly uploaded

## License
These embeddable files are designed to work with your existing SCORM content and maintain all original licensing terms of your educational materials. 