# Vedagna Parvathareddy - Portfolio Website

A modern, responsive portfolio website showcasing skills, projects, and achievements.

## Features

- 🎨 Modern, clean design with dark mode support
- 📱 Fully responsive across all devices
- ⚡ Smooth animations and micro-interactions
- 🔗 Interactive project gallery with live links
- 📧 Functional contact form
- 📄 Downloadable resume
- 🌙 Dark/Light mode toggle with user preference persistence

## How to Run in VS Code

### Method 1: Using Live Server Extension (Recommended)

1. **Install Live Server Extension:**
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X)
   - Search for "Live Server" by Ritwick Dey
   - Click Install

2. **Open the Project:**
   - Open VS Code
   - File → Open Folder
   - Select the portfolio folder

3. **Run the Website:**
   - Right-click on `index.html` in the file explorer
   - Select "Open with Live Server"
   - The website will automatically open in your default browser
   - Any changes you make will automatically refresh the page

### Method 2: Using VS Code's Built-in Browser Preview

1. **Install Browser Preview Extension:**
   - Go to Extensions (Ctrl+Shift+X)
   - Search for "Browser Preview"
   - Install the extension

2. **Open Preview:**
   - Open `index.html`
   - Press Ctrl+Shift+P
   - Type "Browser Preview: Open Preview"
   - Select the command

### Method 3: Manual Browser Opening

1. **Open File Explorer:**
   - Navigate to your project folder
   - Double-click on `index.html`
   - It will open in your default browser

2. **For Development:**
   - Make changes in VS Code
   - Save the file (Ctrl+S)
   - Refresh the browser (F5) to see changes

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── resume.pdf          # Downloadable resume
├── public/
│   └── ME-1.jpg       # Profile photo
└── README.md          # This file
```

## Customization

### Changing Colors
The website uses CSS custom properties for easy color customization. Main colors are defined in the `:root` selector:
- Primary: Blue (#3B82F6)
- Secondary: Purple (#8B5CF6)
- Background: White/Dark gray

### Adding New Sections
1. Add the section HTML in `index.html`
2. Add corresponding navigation link in the header
3. Update the smooth scroll JavaScript if needed

### Modifying Content
- **Personal Info:** Update the hero section
- **Projects:** Modify the projects section with your own projects
- **Skills:** Update the skills arrays in the JavaScript section
- **Contact:** Update contact information and social links

## Technologies Used

- HTML5
- CSS3 (with Tailwind CSS classes)
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts (Inter)

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Tips for Development in VS Code

1. **Use Emmet:** Type shortcuts like `div.container` and press Tab
2. **Auto-format:** Press Shift+Alt+F to format your code
3. **Multi-cursor:** Hold Alt and click to place multiple cursors
4. **Quick Open:** Press Ctrl+P to quickly open files
5. **Integrated Terminal:** Press Ctrl+` to open terminal

## Deployment Options

1. **GitHub Pages:** Push to GitHub and enable Pages in repository settings
2. **Netlify:** Drag and drop the folder to Netlify
3. **Vercel:** Connect your GitHub repository
4. **Firebase Hosting:** Use Firebase CLI to deploy

## Contact Form Setup

The contact form currently shows a success message. To make it functional:

1. **Using Formspree:**
   - Sign up at formspree.io
   - Replace the form action with your Formspree endpoint

2. **Using Netlify Forms:**
   - Add `netlify` attribute to the form
   - Deploy to Netlify

3. **Using EmailJS:**
   - Sign up at emailjs.com
   - Add EmailJS SDK and configure

## License

This project is open source and available under the MIT License.