# 🏡 MOJO - Find Your Mojo in Portugal

A modern, AI-powered real estate website template for Portugal property investments. Built with responsive design, interactive features, and seamless user experience.

## ✨ Features

### 🎨 Modern Design
- **Warm Color Palette**: Coral/orange gradients with creamy backgrounds
- **Typography**: Poppins font family for professional, modern appearance
- **Responsive Layout**: Mobile-first design that works on all devices
- **Smooth Animations**: Hover effects, transitions, and loading states

### 🤖 AI-Powered Content
- **Interactive Quiz**: Personalized Portugal lifestyle recommendations
- **Property Story Generator**: Dynamic descriptions using Google Gemini API
- **Smart Itineraries**: Custom daily plans based on user preferences

### 🏠 Real Estate Features
- **Property Showcase**: Beautiful property cards with dynamic content
- **Service Overview**: 3-step process for property acquisition
- **Investment Focus**: Emphasizes Portugal's growing market opportunities
- **Professional Team**: Showcases local expertise and team photos

### 🔧 Technical Features
- **Static HTML**: Single-file deployment, no build process required
- **External APIs**: Google Gemini integration for AI content
- **Loading States**: Professional UX with spinners and transitions
- **SEO Optimized**: Proper meta tags and semantic HTML

## 🚀 Quick Start

### Local Development
```bash
# Clone the repository
git clone https://github.com/failoftenfailfast/mojo.git
cd mojo

# Start local server
python3 -m http.server 3004

# Open in browser
open http://localhost:3004
```

### Deployment Options

#### Vercel (Recommended)
1. Fork this repository
2. Go to [vercel.com](https://vercel.com)
3. Sign in with GitHub
4. Import your fork of `failoftenfailfast/mojo`
5. Deploy with default settings

#### Other Static Hosts
- **Netlify**: Drag and drop `index.html`
- **GitHub Pages**: Enable in repository settings
- **Any CDN**: Upload `index.html` to your hosting provider

## ⚙️ Configuration

### AI Features Setup
To enable AI-powered property descriptions and quiz results:

1. Get a Google Gemini API key from [Google AI Studio](https://aistudio.google.com)
2. Replace the empty string in `index.html` line 192:
   ```javascript
   const apiKey = "YOUR_GEMINI_API_KEY_HERE";
   ```
3. Deploy your changes

### Customization
- **Properties**: Update property data in the Properties Section (around line 140)
- **Contact Info**: Modify footer contact details
- **Images**: Replace Unsplash URLs with your own property photos
- **Branding**: Update logo, colors, and company information

## 📁 Project Structure
```
mojo/
├── index.html          # Complete website (HTML, CSS, JavaScript)
├── vercel.json        # Vercel deployment configuration
└── README.md          # This documentation
```

## 🎯 Key Sections

### Hero Section
- Full-screen background with compelling tagline
- Call-to-action for the interactive quiz
- Responsive typography with gradient effects

### Services Section
- 3-step process: Finding, Renovating, Investment Management
- Card-based layout with hover animations
- Clear value proposition for each service

### Properties Section
- Featured property cards with AI-generated descriptions
- Interactive "Generate Story" buttons
- Professional property photography

### Team Section
- Social proof and local expertise messaging
- Team photo grid with professional styling
- Investment growth statistics

## 🌐 Live Demo
- **Local**: http://localhost:3004 (when running locally)
- **Production**: Will be available after Vercel deployment

## 🔧 Technical Stack
- **HTML5**: Semantic markup and accessibility
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **Vanilla JavaScript**: No framework dependencies
- **Google Gemini API**: AI content generation
- **Poppins Font**: Modern, professional typography

## 📱 Browser Support
- Chrome/Edge 80+
- Firefox 75+
- Safari 13+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Performance
- **Lighthouse Score**: 95+ (when optimized)
- **Load Time**: < 2 seconds on fast connections
- **Bundle Size**: Single HTML file (~22KB)
- **CDN Optimized**: Uses external CDNs for fonts and CSS

## 🎨 Color Scheme
- **Primary Gradient**: `#FF6F61` → `#FF4500` (Coral to Orange)
- **Background**: `#FFF8F0` (Creamy White)
- **Text**: `#333333` (Charcoal Gray)
- **Accents**: Various grays for secondary content

## 📝 License
This project is provided as a template. Customize freely for your real estate business.

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

---

**Built with ❤️ for Portugal real estate professionals**
