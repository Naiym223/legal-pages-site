# Legal Pages Site 📋

A visually stunning legal documentation website with beautiful animations, glassmorphism design, and comprehensive legal pages meeting New York state requirements.

## ✨ Features

### 🎨 Design & User Experience
- **Glassmorphism Design** - Modern glass card effects with backdrop blur
- **Smooth Animations** - Framer Motion powered transitions and interactions
- **Floating Elements** - Animated blob backgrounds and hover effects
- **Responsive Design** - Perfect experience across all devices
- **Dark/Light Mode** - Theme switching with smooth transitions
- **Interactive Navigation** - Animated dropdown menus and breadcrumbs

### 📄 Comprehensive Legal Documentation
- **Privacy Policy** - GDPR, CCPA, and NY state compliant
- **Terms of Service** - Complete terms meeting NY legal standards
- **Cookie Policy** - Detailed cookie usage and consent management
- **Data Security Policy** - Security measures and breach procedures
- **Accessibility Statement** - ADA compliance and accommodations
- **Refund Policy** - Clear refund terms and processes
- **Disclaimer** - Liability limitations and disclaimers
- **User Conduct Policy** - Acceptable use guidelines
- **Intellectual Property** - Copyright and DMCA procedures
- **Contact Information** - Legal contacts and business details

### 🔍 Advanced Functionality
- **Real-time Search** - Search across all legal documents
- **Table of Contents** - Interactive navigation for long documents
- **Print Support** - Print-optimized CSS for legal documents
- **PDF Download** - Ready for PDF generation implementation
- **Scroll to Top** - Animated scroll to top button
- **Last Updated Tracking** - Document version control
- **SEO Optimized** - Meta tags and structured data

### 🛠 Technical Features
- **Next.js 14** - Latest React framework with App Router
- **TypeScript** - Full type safety throughout the application
- **Tailwind CSS** - Utility-first CSS with custom animations
- **Framer Motion** - Advanced animations and transitions
- **Performance Optimized** - Lighthouse score optimizations
- **Accessibility** - WCAG compliant design patterns

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm, yarn, or bun package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Naiym223/legal-pages-site.git
   cd legal-pages-site
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   bun install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   bun dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🏗 Project Structure

```
legal-pages-site/
├── src/
│   ├── app/                    # App Router pages
│   │   ├── globals.css         # Global styles and animations
│   │   ├── layout.tsx          # Root layout with providers
│   │   ├── page.tsx            # Homepage with animated cards
│   │   ├── privacy-policy/     # Privacy policy page
│   │   ├── terms-of-service/   # Terms of service page
│   │   ├── contact/            # Contact information page
│   │   └── [other-pages]/      # Additional legal pages
│   └── components/             # Reusable UI components
│       ├── breadcrumb.tsx      # Breadcrumb navigation
│       ├── footer.tsx          # Site footer
│       ├── navigation.tsx      # Main navigation with dropdowns
│       ├── search-bar.tsx      # Real-time search functionality
│       ├── scroll-to-top.tsx   # Animated scroll button
│       ├── table-of-contents.tsx # Document navigation
│       ├── theme-provider.tsx  # Dark/light mode provider
│       ├── last-updated.tsx    # Document timestamp display
│       └── print-button.tsx    # Print and PDF controls
├── public/                     # Static assets
├── package.json               # Dependencies and scripts
├── tailwind.config.ts         # Tailwind configuration with custom animations
├── tsconfig.json             # TypeScript configuration
└── next.config.mjs           # Next.js configuration
```

## 🎯 Key Components

### Navigation System
- **Glassmorphism navbar** with blur effects
- **Dropdown menus** with smooth animations
- **Mobile-responsive** hamburger menu
- **Active state indicators** for current page

### Legal Document Pages
- **Consistent layout** across all documents
- **Table of contents** with smooth scrolling
- **Print-optimized styling** for professional documents
- **Breadcrumb navigation** for easy orientation
- **Last updated timestamps** for version tracking

### Animation System
- **Stagger animations** for content loading
- **Hover effects** on interactive elements
- **Scroll-triggered animations** using Intersection Observer
- **Page transitions** with Framer Motion
- **Loading states** with custom animations

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#4963e0` - Main brand color
- **Gradient Blues**: From blue-50 to purple-50 backgrounds
- **Glass Effects**: White/95 with backdrop blur
- **Text Colors**: Gray-900 for headings, Gray-600 for body

### Typography
- **Font Family**: Inter (Google Fonts)
- **Headings**: Bold weights with gradient text effects
- **Body**: Clean, readable typography with proper spacing
- **Legal Text**: Optimized for document readability

### Animations
- **Blob Animation**: 7s infinite floating effect
- **Float Animation**: 6s ease-in-out floating
- **Fade In**: 0.5s ease-in-out entrance
- **Hover Lift**: Transform and shadow on hover
- **Stagger**: Sequential element animations

## 📱 Responsive Design

- **Mobile First**: Optimized for mobile devices
- **Tablet Support**: Enhanced layouts for tablets
- **Desktop**: Full-featured desktop experience
- **Print Styles**: Clean printing for legal documents

## 🔧 Configuration

### Environment Variables
Create a `.env.local` file for environment-specific settings:

```env
# Add your environment variables here
NEXT_PUBLIC_SITE_URL=https://your-domain.com
```

### Customization
- **Colors**: Modify `tailwind.config.ts` for brand colors
- **Animations**: Add custom animations in the config
- **Content**: Update legal documents in respective page files
- **Styling**: Customize global styles in `globals.css`

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically with each push

### Netlify
1. Build the project: `npm run build`
2. Deploy the `out` folder to Netlify
3. Configure redirects for proper routing

### Manual Deployment
1. Build the project: `npm run build`
2. Export static files: `npm run export`
3. Deploy the `out` folder to your hosting provider

## 📋 Legal Compliance

This website includes comprehensive legal documentation that meets:

- **New York State Requirements** - All documents comply with NY legal standards
- **Federal Regulations** - GDPR, CCPA, and other federal compliance
- **Industry Standards** - Following best practices for legal documentation
- **Accessibility Standards** - WCAG 2.1 AA compliance

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support and questions:

- **Email**: legal@legalpages.com
- **GitHub Issues**: [Create an issue](https://github.com/Naiym223/legal-pages-site/issues)
- **Documentation**: This README and inline code comments

## 🔄 Updates

The legal documents and website are regularly updated to maintain compliance with changing legal requirements. Check the "Last Updated" timestamps on each document page.

---

Built with ❤️ using Next.js, TypeScript, Tailwind CSS, and Framer Motion.