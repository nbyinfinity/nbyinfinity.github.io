# nbyinfinity Blog

A technical blog built with Hugo and the LoveIt theme, focusing on data engineering, cloud computing, and technology.

## 🚀 Features

- **Modern Design**: Built with the Hugo LoveIt theme
- **Responsive**: Mobile-friendly layout
- **SEO Optimized**: Proper meta tags and structured data
- **Fast**: Static site generation with Hugo
- **GitHub Pages**: Automated deployment via GitHub Actions

## 📝 Content

The blog covers topics including:
- AWS and cloud computing
- Data engineering with Snowflake
- Streamlit development
- Technical tutorials and best practices

## 🛠️ Technology Stack

- **Hugo**: Static site generator
- **LoveIt Theme**: Modern Hugo theme
- **GitHub Pages**: Hosting
- **GitHub Actions**: CI/CD for automated deployment

## 🚀 Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nbyinfinity/nbyinfinity.github.io.git
   cd nbyinfinity.github.io
   ```

2. **Initialize submodules**:
   ```bash
   git submodule update --init --recursive
   ```

3. **Install Hugo** (if not already installed):
   ```bash
   # macOS
   brew install hugo
   
   # Or download from https://github.com/gohugoio/hugo/releases
   ```

4. **Run the development server**:
   ```bash
   hugo serve
   ```

5. **View the site**: Open http://localhost:1313 in your browser

## 📁 Project Structure

```
.
├── .github/workflows/    # GitHub Actions for deployment
├── archetypes/          # Content templates
├── content/             # Blog posts and pages
├── layouts/             # Custom layouts
├── static/              # Static assets (images, etc.)
├── themes/LoveIt/       # Hugo theme (git submodule)
├── hugo.toml           # Hugo configuration
└── README.md           # This file
```

## 🎨 Customizations

- Custom CSS styling for logo and page width
- Enhanced table of contents
- Custom title sections with logos
- Responsive design improvements

## 📄 License

This blog and its content are licensed under the MIT License. See individual posts for specific licensing information.

## 📧 Contact

- **GitHub**: [@nbyinfinity](https://github.com/nbyinfinity)
- **Blog**: [nbyinfinity.github.io](https://nbyinfinity.github.io)

---

**Built with ❤️ using Hugo and the LoveIt theme**