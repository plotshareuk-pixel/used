# Used

A modern, responsive website for finding and sharing used items. This platform promotes sustainable living by connecting people who have items they no longer need with those who are looking for exactly those things.

## 🌟 Features

- **Modern Design**: Clean, responsive interface that works on all devices
- **Mobile-First**: Optimized for mobile browsers with touch-friendly navigation
- **Fast Loading**: Lightweight code with optimized performance
- **Accessible**: Built with accessibility standards in mind
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## 🚀 Getting Started

This is a static website that can be served by any web server or deployed to hosting platforms like GitHub Pages, Netlify, or Vercel.

### Local Development

1. Clone the repository
2. Open `index.html` in your web browser
3. Or serve the files using a local web server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

### Deployment

#### GitHub Pages
1. Go to your repository settings
2. Navigate to Pages section
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

#### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command to empty (static site)
3. Set publish directory to `/` (root)
4. Deploy

## 📁 Project Structure

```
├── index.html          # Homepage
├── about.html          # About page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── favicon.ico         # Website icon
└── README.md          # This file
```

## 🎨 Customization

### Colors
The main color scheme can be customized by modifying the CSS variables or replacing the gradient colors in `styles.css`:

- Primary: `#2c5aa0` (blue)
- Secondary: `#ff6b6b` (coral)
- Gradients: `#667eea` to `#764ba2`

### Content
- Update the text content in HTML files
- Replace placeholder contact information
- Add your own images and branding
- Modify the navigation structure as needed

### Functionality
- The contact form currently shows a success message
- Add backend integration for form submissions
- Implement user authentication
- Add database connectivity for listings

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive features and form handling
- **Responsive Design**: Mobile-first approach

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across different browsers
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🌍 Mission

We believe in creating a more sustainable world by extending the lifecycle of products and reducing waste. Every item that finds a new home through our platform is a small victory for the environment.

---

**Live Website**: [Add your deployment URL here]

For questions or support, please open an issue or contact us through the website.