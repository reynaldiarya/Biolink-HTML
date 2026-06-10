# Biolink HTML

A lightweight, high-performance link-in-bio landing page built with pure HTML and CSS for creators and professionals.

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" />
  <img src="https://img.shields.io/badge/HTML5-E34F26.svg" />
  <img src="https://img.shields.io/badge/CSS3-1572B6.svg" />
  <a href="LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-yellow.svg" target="_blank" />
  </a>
</p>

## Description

Biolink HTML provides a streamlined, professional foundation for building personalized landing pages that house all your essential links in one place. Designed for optimal performance and mobile-first accessibility, it solves the problem of platform-specific link limitations while maintaining complete ownership of your digital presence. The project is built using standard web technologies, ensuring it is highly portable and can be deployed to any static hosting service with zero configuration.

## Features

- **Mobile-Responsive Design** - Fluid layout that adapts seamlessly to smartphones, tablets, and desktops
- **Optimized Performance** - Zero-dependency architecture ensuring near-instantaneous page load times
- **Social Integration** - Pre-configured Font Awesome support for consistent and modern social iconography
- **SEO & Social Sharing** - Built-in Open Graph metadata for enhanced visibility when shared on social platforms
- **Effortless Customization** - Intuitive structure allowing for rapid updates to branding, links, and styling
- **Static Deployment** - Fully compatible with GitHub Pages, Netlify, Vercel, and traditional web servers

## Tech Stack

- **Structure**: HTML5
- **Styling**: CSS3 (Vanilla)
- **Typography**: Google Fonts (Open Sans)
- **Icons**: Font Awesome 6.3.0

## Installation Guide

### Prerequisites

- A modern web browser
- A basic text editor (VS Code, Sublime Text, etc.)
- (Optional) A static site hosting account for deployment

### Steps

1. Clone the repository to your local machine:

```bash
git clone https://github.com/reynaldiarya/Biolink-HTML.git
```

2. Navigate to the project directory:

```bash
cd Biolink-HTML
```

3. Open `index.html` in your preferred browser to view the page locally.

## Configuration

The project is designed to be easily modified without a complex build process.

### Content Customization

Update the following elements in `index.html`:

- **Title & Metadata**: Update the `<title>` and `<meta>` tags for SEO purposes.
- **Branding**: Update the logo source and social media handle in the `.header` section.
- **Links**: Modify the `<ul>` list items to point to your respective URLs.

### Visual Assets

Replace the default assets in the `assets/images/` directory:

- `logo.png`: Your profile picture or brand logo.
- `icon.png`: The favicon for the browser tab.

### Styling

Modify `assets/css/main.css` to adjust colors, fonts, and spacing to match your personal brand.

## Usage

### Local Development

Since this is a static project, you can simply open the `index.html` file. For a better development experience, you can use a local server like Live Server (VS Code extension):

1. Open the project in VS Code.
2. Right-click `index.html`.
3. Select **Open with Live Server**.

### Deployment

To make your biolink public, upload the files to a hosting provider.

**Example for GitHub Pages:**

1. Push the code to a GitHub repository.
2. Go to **Settings > Pages**.
3. Select the `main` branch as the source and save.

## Project Structure

```text
/
├── assets/
│   ├── css/
│   │   └── main.css        # Core styling and layout definitions
│   └── images/
│       ├── icon.png        # Favicon asset
│       └── logo.png        # Profile or brand image
├── index.html              # Main entry point and content structure
├── LICENSE                 # MIT License details
└── README.md               # Project documentation
```

## Scripts / Commands

As a static HTML project, there are no build scripts required.

| Action     | Command                             |
| ---------- | ----------------------------------- |
| Preview    | Open `index.html` in any browser    |
| Deployment | Push to any static hosting provider |

## Contributing

Contributions are welcome to improve the template or add new styles.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Improve styling'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for detailed terms and conditions.

## Author

Reynaldi Arya
