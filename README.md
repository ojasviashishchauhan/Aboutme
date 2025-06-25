# Ojasvi Ashish Chauhan - Portfolio Website

A modern, responsive portfolio website showcasing expertise in Data Science and Cybersecurity.

## 🌟 Features

- **Modern Design**: Clean, professional design with stunning visual effects
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth animations and transitions powered by AOS (Animate On Scroll)
- **Professional**: Showcases career journey, skills, and projects
- **Fast Loading**: Optimized for performance with lazy loading and efficient animations
- **SEO Friendly**: Semantic HTML structure for better search engine visibility

## 🚀 Live Demo

Visit the live website at: [ojasviashishchauhan.dharaik.in](https://ojasviashishchauhan.dharaik.in)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for accessibility and SEO
- **CSS3**: Modern styling with Flexbox, Grid, and CSS animations
- **JavaScript**: Interactive functionality and dynamic content
- **Font Awesome**: Icons for enhanced visual appeal
- **Google Fonts**: Inter font family for clean typography
- **AOS Library**: Animate On Scroll for smooth animations

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # Main CSS file with all styles
├── script.js           # JavaScript for interactivity
├── README.md           # Project documentation
└── assets/             # Images and other assets (if any)
```

## 🎨 Design Features

### Color Scheme
- Primary gradient: #667eea to #764ba2
- Background: Clean whites and light grays
- Text: Professional dark grays and whites

### Animations
- Floating icons in hero section
- Smooth scroll animations
- Skill bar progress animations
- Counter animations for statistics
- Hover effects on all interactive elements

### Sections
1. **Hero**: Eye-catching introduction with animated role rotation
2. **About**: Professional overview with key highlights
3. **Journey**: Career timeline with detailed experience
4. **Skills**: Technical skills categorized by domain
5. **Projects**: Featured projects with technology stacks
6. **Contact**: Contact form and social links

## 🚀 Getting Started

### Prerequisites
- A GitHub account
- Basic knowledge of Git
- Text editor (VS Code recommended)

### Installation

1. **Clone or download this repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Open index.html in your browser**
   - Simply double-click on `index.html`
   - Or use a local server for development

3. **For development with live reload** (optional):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## 🌐 Hosting on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to GitHub and create a new repository
2. Name it `portfolio` or any name you prefer
3. Make sure it's public
4. Don't initialize with README (since you already have one)

### Step 2: Upload Your Files

```bash
# Initialize git in your project folder
git init

# Add all files
git add .

# Commit your files
git commit -m "Initial portfolio website"

# Add your GitHub repository as origin
git remote add origin https://github.com/yourusername/portfolio.git

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

Your site will be available at: `https://yourusername.github.io/portfolio`

## 🔗 Custom Domain Setup (ojasviashishchauhan.dharaik.in)

### Step 1: Configure GitHub Pages for Custom Domain

1. In your repository settings, go to **Pages** section
2. Under **Custom domain**, enter: `ojasviashishchauhan.dharaik.in`
3. Click **Save**
4. GitHub will create a CNAME file in your repository

### Step 2: Configure DNS Settings

You need to configure DNS settings with your domain provider (dharaik.in):

#### For GitHub Pages:
Add these DNS records:

```
Type: CNAME
Name: ojasviashishchauhan
Value: yourusername.github.io
```

Or if using apex domain:

```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153
```

### Step 3: Enable HTTPS

1. In GitHub Pages settings, check **Enforce HTTPS**
2. It may take a few minutes to provision the SSL certificate

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

## 🎯 SEO Optimization

- Semantic HTML structure
- Meta tags for social sharing
- Descriptive alt texts for images
- Clean URL structure
- Fast loading times
- Mobile-friendly design

## 🔧 Customization

### Updating Content

1. **Personal Information**: Edit the hero section in `index.html`
2. **Skills**: Modify the skills section with your technologies
3. **Projects**: Update the projects section with your work
4. **Contact**: Change contact information and social links

### Styling Changes

1. **Colors**: Update CSS custom properties in `styles.css`
2. **Fonts**: Change font imports in HTML head
3. **Layout**: Modify CSS Grid and Flexbox properties

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Add any interactive functionality in `script.js`

## 📈 Performance

- **Optimized Images**: Use WebP format when possible
- **Minified CSS/JS**: Consider minifying for production
- **CDN Usage**: External libraries loaded from CDN
- **Lazy Loading**: Implemented for better performance

## 🐛 Browser Support

- **Chrome**: Latest 2 versions
- **Firefox**: Latest 2 versions
- **Safari**: Latest 2 versions
- **Edge**: Latest 2 versions

## 📧 Contact

- **Email**: ojaschauhan44@gmail.com
- **Website**: [ojasviashishchauhan.dharaik.in](https://ojasviashishchauhan.dharaik.in)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Font Awesome** for icons
- **Google Fonts** for typography
- **AOS Library** for animations
- **GitHub Pages** for hosting

---

Made with ❤️ by Ojasvi Ashish Chauhan 