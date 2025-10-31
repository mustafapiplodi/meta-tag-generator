# Meta Tag Generator

A free, browser-based meta tag generator that creates SEO-optimized meta tags with live multi-platform preview. Generate professional meta tags for Google, Facebook, Twitter, and LinkedIn with real-time visual feedback.

![Meta Tag Generator](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🚀 Features

### Core Functionality
- **Live Multi-Platform Previews** - See exactly how your content appears on Google search results, Facebook, and Twitter in real-time
- **Smart Character Counting** - Unicode-aware character limits with visual warnings for title (60 chars) and description (160 chars)
- **Complete Meta Tag Generation** - Generates SEO tags, Open Graph tags, and Twitter Cards
- **One-Click Copy** - Copy all tags or individual sections (SEO, Open Graph, Twitter)
- **Download as HTML** - Export meta tags as an HTML file
- **URL Sharing** - Share pre-filled forms via URL parameters

### User Experience
- **Dark Mode** - Toggle between light and dark themes
- **Form Progress Tracking** - Visual progress bar showing completion status
- **Device Preview Toggle** - Switch between desktop and mobile views
- **Smart Placeholders** - Rotating example placeholders for inspiration
- **Empty State Design** - Helpful guidance when starting fresh
- **Confetti Celebrations** - Fun animations on successful copy/download

### Design & Polish
- **Glassmorphism Effects** - Modern frosted glass appearance
- **Smooth Animations** - Loading states and micro-interactions throughout
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Accessibility** - Keyboard shortcuts and ARIA labels

## 📋 SEO Best Practices Included

- **2025 Standards** - Up-to-date with current SEO requirements
- **Mobile-First** - Viewport meta tag included by default
- **Social Media Optimization** - Proper Open Graph and Twitter Card tags
- **Image Specifications** - Guidance for 1200x630px social sharing images
- **Validation Tools** - Direct links to Facebook Debugger, Twitter Validator, and Google Rich Results Test

## 🎯 Use Cases

Perfect for:
- Content creators publishing blog posts and articles
- Small business owners managing their own websites
- Digital marketers creating landing pages
- Developers who need quick meta tag generation
- Anyone publishing web content who wants better social sharing and search visibility

## 🛠️ Technical Details

### Technology Stack
- **Pure Vanilla JavaScript** - No frameworks or dependencies (except canvas-confetti)
- **Single Page Application** - Everything in one HTML file
- **Modern Browser APIs** - Intl.Segmenter, Clipboard API, Proxy for state management
- **CSS Variables** - HSL-based theming system for light/dark modes

### Browser Support
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Performance
- Fast load time (<100KB total)
- No external dependencies (except confetti library)
- Client-side only - no server required
- Works offline after initial load

## 🚦 Getting Started

### Quick Start
Simply open `index.html` in your browser - that's it! No installation or build process required.

### Deployment Options

**Option 1: Static Hosting**
Upload `index.html` to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Any web server

**Option 2: Local Development**
```bash
# Clone the repository
git clone https://github.com/yourusername/meta-tag-generator.git

# Navigate to directory
cd meta-tag-generator

# Open in browser
open index.html
```

## 📖 How to Use

1. **Enter Your Content Details**
   - Fill in your page title, description, URL, site name, and social image
   - Watch the live previews update in real-time

2. **Review Previews**
   - Check how your content appears on Google, Facebook, and Twitter
   - Toggle between desktop and mobile views

3. **Copy or Download**
   - Click "All" to copy all meta tags at once
   - Or copy individual sections (SEO, OG, Twitter)
   - Download as HTML file for easy reference

4. **Add to Your Website**
   - Paste the tags into your HTML `<head>` section
   - Test with the validation tools provided

5. **Validate**
   - Use the "Open Validation Tools" button to test your tags
   - Verify appearance on Facebook, Twitter, and Google

## ⌨️ Keyboard Shortcuts

- `Ctrl/Cmd + S` - Prevent browser save dialog
- `Ctrl/Cmd + C` - Copy generated code (when not in input field)
- `Ctrl/Cmd + K` - Focus title input

## 🎨 Customization

The tool uses CSS variables for easy theming. Key variables:
```css
--primary: 221.2 83.2% 53.3%;
--background: 0 0% 100%;
--foreground: 222.2 84% 4.9%;
```

Modify these in the `<style>` section to match your brand colors.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 Meta Tag Generator

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🐛 Bug Reports

Found a bug? Please open an issue with:
- Browser version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable

## 💡 Feature Requests

Have an idea? Open an issue with the `enhancement` label and describe:
- The problem you're trying to solve
- Your proposed solution
- Why this would be useful to others

## 📊 SEO Meta Tags Reference

### Essential Tags Generated
- `<title>` - Page title (50-60 characters)
- `<meta name="description">` - Meta description (140-160 characters)
- `<link rel="canonical">` - Canonical URL
- `<meta name="viewport">` - Mobile viewport
- `<meta name="robots">` - Search engine directives

### Open Graph Tags (Facebook, LinkedIn, WhatsApp)
- `og:title`, `og:type`, `og:url`, `og:image`
- `og:description`, `og:site_name`
- `og:image:width`, `og:image:height`, `og:image:alt`

### Twitter Card Tags
- `twitter:card` - Summary with large image
- `twitter:title`, `twitter:description`
- `twitter:image`, `twitter:image:alt`

## 🙏 Acknowledgments

- [canvas-confetti](https://github.com/catdad/canvas-confetti) - Celebration animations
- Icons from [Heroicons](https://heroicons.com/)
- Inspired by modern SEO best practices and meta tag standards

## 📞 Support

Need help?
- Open an issue on GitHub
- Check existing issues for solutions
- Review the SEO Best Practices section in the app

## 🔗 Related Resources

- [Open Graph Protocol](https://ogp.me/)
- [Twitter Cards Documentation](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/abouts-cards)
- [Google Search Central](https://developers.google.com/search/docs)

---

**Built with ❤️ for better SEO and social sharing**

[Live Demo](https://yourusername.github.io/meta-tag-generator) | [Report Bug](https://github.com/yourusername/meta-tag-generator/issues) | [Request Feature](https://github.com/yourusername/meta-tag-generator/issues)
