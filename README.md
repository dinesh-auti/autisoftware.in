# Auti Software - SRE Consulting Website

A professional website for Auti Software, specializing in Site Reliability Engineering (SRE) consulting services.

## Services

- **CI/CD Pipeline Development & Automation**
- **Cloud Cost Optimization & Resource Management** 
- **Infrastructure as Code & DevOps Transformation**
- **Site Reliability Engineering & Performance Optimization**

## Built With

- [Hugo](https://gohugo.io/) - Static Site Generator
- [Bigspring Light Theme](https://github.com/themefisher/bigspring-light) - Hugo Theme
- Custom styling and content for SRE consulting

## Local Development

### Prerequisites

- Hugo Extended v0.110.0 or later
- Git

### Setup

1. Clone the repository:
```bash
git clone https://github.com/dinesh-auti/autisoftware.in.git
cd autisoftware.in
```

2. Initialize theme submodule:
```bash
git submodule update --init --recursive
```

3. Start the development server:
```bash
hugo server -D
```

4. Open your browser and navigate to `http://localhost:1313`

### Building for Production

```bash
hugo --minify
```

The generated site will be in the `public/` directory.

## Project Structure

```
├── assets/          # Images, SCSS, JS files
├── config/          # Hugo configuration files
├── content/         # Website content (markdown files)
├── layouts/         # Custom layouts and partials
├── static/          # Static files (favicon, etc.)
├── themes/          # Hugo themes
└── hugo.toml        # Main Hugo configuration
```

## Contact Information

- **Email**: info@autisoftware.in
- **Phone**: +91 8591121670
- **Location**: Mumbai, India

## License

© 2025 Auti Software Consultancy Services · India 🇮🇳