# Korí Website

A modern, responsive website for Korí - the beauty service platform that bridges the distance between customers and beauty specialists.

## 🌟 Features

- **Modern Design**: Clean, professional design inspired by Korí's brand identity
- **Responsive**: Mobile-first approach, works perfectly on all devices
- **Dark/Light Mode**: Toggle between themes with smooth transitions
- **SEO Optimized**: Comprehensive SEO setup with structured data
- **Performance**: Optimized images, code splitting, and fast loading
- **TypeScript**: Fully typed for better development experience
- **Accessibility**: WCAG compliant components

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Styling**: Tailwind CSS with CSS variables
- **TypeScript**: Full type safety
- **Performance**: Image optimization, code splitting
- **SEO**: Structured data, sitemaps, meta tags
- **Deployment**: Vercel ready

## 📱 Apps Showcased

### Korí Pro

Professional app for beauty specialists including:

- Hairdressers
- Masseurs
- Barbers
- Other beauty service providers

### Korí

Korí is the customer app for booking beauty services with features like:

- Service discovery
- Professional profiles
- Booking system
- Reviews and ratings

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0 or later
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd kori-website
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run lint:fix` - Fix ESLint issues
- `npm run format` - Format code with Prettier
- `npm run type-check` - Run TypeScript type checking

## 🎨 Design System

### Colors

- **Primary**: #53745D (Green)
- **Text**: #261D12 (Dark Brown)
- **Background**: #F7F1E8 (Light Cream)
- **Accent**: Various shades for interactive elements

### Typography

- **Font**: Geist Sans (Primary), Geist Mono (Code)
- **Scales**: Responsive typography with fluid scaling

## 📂 Project Structure

```
src/
├── app/                 # App Router pages
│   ├── about/          # About page
│   ├── contact/        # Contact page
│   ├── layout.tsx      # Root layout
│   └── page.tsx        # Home page
├── components/         # React components
│   ├── layout/         # Layout components
│   ├── sections/       # Page sections
│   └── ui/            # UI components
├── lib/               # Utilities and configurations
├── types/             # TypeScript type definitions
└── globals.css        # Global styles
```

## 🌍 Environment Variables

Copy `.env.example` to `.env.local` and update the values:

```env
NEXT_PUBLIC_SITE_URL=https://your-domain.com
NEXT_PUBLIC_CONTACT_EMAIL=contact@kori.app
NEXT_PUBLIC_CONTACT_PHONE=+237 123 456 789
```

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to a Git repository
2. Import your project to Vercel
3. Configure environment variables
4. Deploy!

The site is optimized for Vercel deployment with automatic optimization.

### Other Platforms

The site can be deployed to any platform that supports Next.js:

- Netlify
- AWS Amplify
- Railway
- Digital Ocean App Platform

## 📈 SEO Features

- **Meta Tags**: Comprehensive meta tag setup
- **Open Graph**: Social media sharing optimization
- **Structured Data**: JSON-LD for search engines
- **Sitemap**: Auto-generated XML sitemap
- **Robots.txt**: Search engine indexing control

## 🎯 Performance Optimizations

- **Image Optimization**: Next.js Image component with WebP/AVIF
- **Code Splitting**: Automatic route-based splitting
- **Tree Shaking**: Remove unused code
- **Compression**: Gzip/Brotli compression
- **Caching**: Optimized caching headers

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 📞 Contact

For questions about this website:

- Email: contact@kori.app
- Phone: +237 123 456 789

---

Built with ❤️ for the Korí beauty platform.
