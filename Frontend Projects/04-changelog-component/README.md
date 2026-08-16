# Changelog Component

A clean and responsive changelog component built with HTML and CSS. This component helps display updates, fixes, and new features in a visually appealing way. Created as part of the [Changelog Component Project](https://roadmap.sh/projects/changelog-component) from roadmap.sh.

## 🔴 Live Demo

[View Live Demo](https://your-username.github.io/changelog-component)

![Changelog Component Preview](screenshot.png)

## ✨ Features

- Modern, clean design with subtle animations
- Fully responsive layout using Flexbox
- Three distinct badge types (New, Fix, Update)
- Hover effects and smooth transitions
- Easy customization through CSS variables
- Mobile-first approach
- Accessible markup structure

## 🚀 Quick Start

1. Clone the repository:

```bash
git clone https://github.com/your-username/changelog-component.git
cd changelog-component
```

2. Open in VS Code:

```bash
code .
```

3. Use Live Server extension to view the component:
   - Install "Live Server" extension in VS Code
   - Right-click `index.html` and select "Open with Live Server"

## 🎨 Customization

### Colors

Modify the CSS variables in `styles.css`:

```css
:root {
  --primary-color: #2563eb; /* New badge color */
  --success-color: #16a34a; /* Update badge color */
  --warning-color: #ea580c; /* Fix badge color */
  --text-color: #1f2937; /* Main text color */
  --border-color: #e5e7eb; /* Divider color */
  --background-color: #ffffff; /* Background color */
  --hover-bg: #f8fafc; /* Hover state color */
}
```

### Adding New Entries

Add new changelog entries by following this HTML structure:

```html
<div class="changelog__item">
  <div class="changelog__date">Date Here</div>
  <div class="changelog__content">
    <span class="changelog__badge">Type</span>
    <h3>Title</h3>
    <p>Description</p>
  </div>
</div>
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- Inspired by modern changelog designs
- Built as part of the [roadmap.sh](https://roadmap.sh) learning projects
- Icons from [Emoji CSS](https://emoji-css.afeld.me/)

## 📞 Support

If you have any questions or feedback, please open an issue on GitHub.
