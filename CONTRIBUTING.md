# Contributing to Elyan Labs Pitch Deck

Thank you for your interest in contributing to the Elyan Labs — Hartford AI Day Pitch Deck!

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Setup](#development-setup)
- [Project Structure](#project-structure)
- [How to Contribute](#how-to-contribute)
- [Content Guidelines](#content-guidelines)
- [Style Standards](#style-standards)
- [Testing](#testing)
- [Submitting Changes](#submitting-changes)
- [RTC Bounties](#rtc-bounties)

## Code of Conduct

This project follows the RustChain Code of Conduct. Be respectful, constructive, and inclusive in all interactions.

## Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally
3. **Set up the development environment** (see below)
4. **Create a branch** for your changes
5. **Make your changes** and preview them
6. **Submit a pull request**

## Development Setup

### Prerequisites

- **Web Browser**: Chrome, Firefox, Safari, or Edge
- **Text Editor**: VS Code, Sublime Text, or any HTML editor
- **Optional**: Live server extension for real-time preview

### Local Development

```bash
# Clone this repository
git clone https://github.com/Scottcjn/pitch.git
cd pitch

# Open in browser (or use live server)
open index.html

# Or on Linux
xdg-open index.html
```

## Project Structure

```
pitch/
├── index.html              # Main pitch deck
├── css/
│   ├── style.css           # Main stylesheet
│   └── responsive.css      # Mobile/tablet styles
├── js/
│   ├── slides.js           # Slide navigation logic
│   └── animations.js       # Animation effects
├── assets/
│   ├── images/             # Slide images
│   ├── logos/              # Company logos
│   └── fonts/              # Custom fonts
├── slides/                 # Individual slide HTML (if modular)
└── README.md
```

## How to Contribute

### Reporting Issues

1. Check if the issue already exists in [Issues](../../issues)
2. If not, create a new issue with:
   - Clear description
   - Screenshot if visual issue
   - Browser and version
   - Steps to reproduce

### Suggesting Content Changes

1. Open a [Content Request](../../issues/new)
2. Describe the proposed change
3. Explain the rationale
4. Provide example text if applicable

### Contributing Code

1. **Find an issue** to work on
2. **Comment on the issue** to claim it
3. **Fork and branch**: `git checkout -b content/slide-update`
4. **Make changes** following our guidelines
5. **Test across browsers**
6. **Submit PR** with clear description

## Content Guidelines

### Slide Content

- **Keep it concise**: 3-5 bullet points per slide maximum
- **Use active voice**: "We build AI" not "AI is built by us"
- **Focus on value**: What problem does it solve?
- **Include metrics**: Numbers make claims credible
- **Tell a story**: Logical flow from problem → solution → traction

### Text Guidelines

- **Headlines**: Max 8 words
- **Body text**: Max 20 words per bullet
- **Font size**: Minimum 24px for body, 48px for headlines
- **Contrast**: Ensure text is readable on background

### Visual Guidelines

- **Images**: Use high-resolution (min 1920x1080)
- **Colors**: Follow brand guidelines
- **Whitespace**: Don't overcrowd slides
- **Consistency**: Same style across all slides

## Style Standards

### HTML Structure

```html
<section class="slide" id="slide-1">
    <div class="slide-content">
        <h1>Slide Title</h1>
        <ul>
            <li>Point one</li>
            <li>Point two</li>
        </ul>
    </div>
</section>
```

### CSS Guidelines

- **Indentation**: 2 spaces
- **Naming**: BEM methodology (`.block__element--modifier`)
- **Organization**: Group by component
- **Comments**: Section headers for major components

```css
/* Slide Container */
.slide {
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

.slide__title {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.slide__content--highlight {
    background: var(--accent-color);
}
```

### JavaScript Guidelines

- **ES6+**: Use modern JavaScript features
- **Comments**: JSDoc for functions
- **Modules**: Organize code by feature

```javascript
/**
 * Navigate to the next slide
 * @param {boolean} animate - Whether to animate transition
 */
function nextSlide(animate = true) {
    // Implementation
}
```

## Testing

### Browser Testing

Test on latest versions of:
- Chrome
- Firefox
- Safari
- Edge

### Device Testing

- Desktop (1920x1080 and up)
- Tablet (768x1024)
- Mobile (375x667)

### Presentation Mode

- Test in fullscreen (F11)
- Verify slide transitions
- Check animation timing
- Ensure keyboard navigation works

## Submitting Changes

### Commit Messages

Follow conventional commits:
```
content: update problem slide with new metrics
style: fix mobile layout on slide 3
feat: add keyboard navigation
fix: resolve safari flexbox issue
docs: update README with setup instructions
```

### Pull Request Process

1. Preview changes locally
2. Test on multiple browsers
3. Update documentation if needed
4. Request review
5. Address feedback

### PR Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Content update
- [ ] Style/CSS fix
- [ ] New feature
- [ ] Bug fix
- [ ] Documentation

## Testing
- [ ] Tested on Chrome
- [ ] Tested on Firefox
- [ ] Tested on Safari
- [ ] Mobile responsive

## Screenshots
[If visual changes, include before/after screenshots]

## Checklist
- [ ] Content reviewed for accuracy
- [ ] Spelling/grammar checked
- [ ] Responsive design tested
- [ ] Cross-browser compatibility verified
```

## RTC Bounties

Earn RTC tokens for contributions! Check the [RustChain Bounties](https://github.com/Scottcjn/rustchain-bounties) repository for available tasks.

Common bounties for this project:
- Content improvements: 1-5 RTC
- Design enhancements: 5-15 RTC
- Bug fixes: 3-10 RTC
- New features: 10-30 RTC
- Accessibility improvements: 5-15 RTC

## Resources

- [Google Slides Design Guidelines](https://support.google.com/docs/answer/179480)
- [Presentation Best Practices](https://www.garrreynolds.com/preso-tips/design/)
- [Web Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)

## Questions?

- Open a [Discussion](../../discussions)
- Join the RustChain community
- Tag @Scottcjn for maintainer attention

---

**Thank you for helping make the Elyan Labs pitch deck shine!** 🎯✨
