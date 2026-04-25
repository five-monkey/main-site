# 🐵 5Monkey Bistro - Official Website

<div align="center">

![5Monkey Bistro](public/svg/Logo.svg)

**Premium Italian & European Restaurant in Sonipat, Haryana**

[![Next.js](https://img.shields.io/badge/Next.js-15.0-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?logo=typescript)](https://www.typescriptlang.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-38bdf8?logo=tailwind-css)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-11.0-ff69b4?logo=framer)](https://www.framer.com/motion/)

[Visit Website](https://5monkey.in) · [View Menu](https://5monkey.in/menu) · [Book Table](https://5monkey.in/contact)

</div>

---

## 📖 About

5Monkey Bistro's official website showcasing authentic Italian and European cuisine with premium coffee in a cozy atmosphere. Built with modern web technologies to provide an exceptional user experience for food lovers in Sonipat and beyond.

### 🌟 Features

- **🍽️ Digital Menu** - Comprehensive menu with 50+ dishes across multiple categories
- **📸 Interactive Gallery** - Beautiful photo gallery with lightbox functionality
- **📅 Online Reservations** - Easy table booking system
- **🎨 Smooth Animations** - Engaging UI with Framer Motion animations
- **📱 Fully Responsive** - Optimized for all devices (mobile, tablet, desktop)
- **⚡ Fast Performance** - Next.js App Router with optimized images and fonts
- **🔍 SEO Optimized** - Comprehensive SEO with structured data and meta tags
- **🤖 AI-Friendly** - Includes robots.txt, sitemap.xml, and llms.txt

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **[Next.js 15](https://nextjs.org/)** | React framework with App Router |
| **[TypeScript](https://www.typescriptlang.org/)** | Type-safe development |
| **[TailwindCSS](https://tailwindcss.com/)** | Utility-first CSS framework |
| **[Framer Motion](https://www.framer.com/motion/)** | Animation library |
| **[Lucide Icons](https://lucide.dev/)** | Beautiful icon set |
| **[ESLint](https://eslint.org/)** | Code linting and quality |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn/pnpm
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/five-monkey/five-monkey.git
   cd five-monkey
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
npm start
```

---

## 📁 Project Structure

```
five-monkey/
├── app/
│   ├── component/          # Reusable components
│   │   ├── Navbar.tsx      # Navigation bar
│   │   └── Footer.tsx      # Footer component
│   ├── HomeComponents/     # Home page sections
│   │   ├── Hero.tsx        # Hero section
│   │   ├── OurStory.tsx    # About section
│   │   ├── Menu.tsx        # Menu preview
│   │   └── Gallery.tsx     # Gallery preview
│   ├── menu/               # Menu pages
│   │   ├── page.tsx        # Menu overview
│   │   ├── food/           # Food menu
│   │   ├── drinks/         # Drinks menu
│   │   └── desserts/       # Desserts menu
│   ├── gallery/            # Gallery page
│   ├── contact/            # Contact & reservations
│   ├── layout.tsx          # Root layout with SEO
│   ├── page.tsx            # Home page
│   └── globals.css         # Global styles
├── data/
│   └── menuData.json       # Menu content data
├── public/
│   ├── Fonts/              # Custom fonts
│   ├── svg/                # Images and SVG assets
│   ├── robots.txt          # Search engine directives
│   ├── sitemap.xml         # Site structure for SEO
│   └── llms.txt            # AI crawler guidance
├── next.config.ts          # Next.js configuration
├── tailwind.config.ts      # Tailwind configuration
└── tsconfig.json           # TypeScript configuration
```

---

## 🔍 SEO Features

This website implements comprehensive SEO best practices:

### ✅ Metadata & Tags
- Rich title and description tags with keywords
- Open Graph tags for social media sharing
- Twitter Card metadata
- Canonical URLs
- Mobile-friendly meta tags

### ✅ Structured Data (JSON-LD)
- **Restaurant Schema** - Business details, location, hours
- **Menu Schema** - Food categories and offerings
- **Organization Schema** - Contact information
- **WebSite Schema** - Site structure and search

### ✅ Technical SEO
- **robots.txt** - Search engine crawl directives
- **sitemap.xml** - Complete site structure with images
- **llms.txt** - AI/LLM crawler guidance
- Semantic HTML5 structure
- Optimized images (WebP format)
- Fast loading times

### ✅ Local SEO
- Business address and geo-coordinates
- Phone number and email
- Opening hours
- Service area (Sonipat, Haryana)
- Rating and review schema

---

## 🎨 Key Pages

| Page | Route | Description |
|------|-------|-------------|
| **Home** | `/` | Hero, story, menu preview, gallery |
| **Menu** | `/menu` | Complete menu overview |
| **Food Menu** | `/menu/food` | Dining options (breakfast, burgers, pasta) |
| **Drinks Menu** | `/menu/drinks` | Coffee, tea, mocktails |
| **Desserts** | `/menu/desserts` | Sweet treats |
| **Gallery** | `/gallery` | Photo gallery with lightbox |
| **Contact** | `/contact` | Location, hours, reservation form |

---

## 🎯 Performance Optimizations

- ⚡ Next.js App Router for optimal performance
- 🖼️ Next.js Image component with lazy loading
- 📦 Code splitting and dynamic imports
- 🔤 Custom font optimization with `next/font`
- 🎨 CSS optimization with Tailwind
- 📱 Responsive images with WebP format
- 🚀 Static generation where possible

---

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📞 Business Information

**5Monkey Bistro**
- 📍 SCO-150, Sector-15, Sonipat, Haryana 131001
- 📱 +91 99960 21150
- 📧 5monkeybistro@gmail.com
- 🌐 [5monkey.in](https://5monkey.in)

**Operating Hours:**
- Monday - Friday: 10:00 AM - 11:00 PM
- Saturday - Sunday: 11:00 AM - 11:00 PM

---

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Import project to [Vercel](https://vercel.com)
3. Vercel will auto-detect Next.js and configure build settings
4. Deploy!

### Other Platforms
- **Netlify** - Connect GitHub repo and deploy
- **Railway** - One-click deployment
- **Self-hosted** - Use `npm run build` and serve the `.next` folder

---

## 📄 License

This project is proprietary and confidential. © 2025 5Monkey Bistro. All rights reserved.

---

## 📚 Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [TailwindCSS Documentation](https://tailwindcss.com/docs)
- [Framer Motion Documentation](https://www.framer.com/motion/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)

---

<div align="center">

**Created with ❤️ by [Kaizen](mailto:kaizen.official.hub@gmail.com)**

*Building digital experiences that elevate your business*

[![Email](https://img.shields.io/badge/Email-kaizen.official.hub%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kaizen.official.hub@gmail.com)

</div>
