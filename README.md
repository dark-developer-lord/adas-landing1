# 🚁 ADAS - AI Drone Landing Page

A complete, production-ready landing page for ADAS (AI Drones & SaaS platform) built with Next.js 14, TypeScript, and Tailwind CSS.

![ADAS Landing Page](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-38B2AC?style=for-the-badge&logo=tailwind-css)
![Stripe](https://img.shields.io/badge/Stripe-Integrated-008CDD?style=for-the-badge&logo=stripe)

---

## ✨ Features

### 🎯 Complete Business Solution
- ✅ **9 Marketing Pages** - Homepage, Features, Pricing, Product, SaaS, About, Contact, Blog, Integrations
- ✅ **Admin Dashboard** - Real-time order tracking, analytics, revenue monitoring
- ✅ **Payment Processing** - Fully integrated Stripe checkout with webhook handling
- ✅ **Analytics** - Google Analytics 4, HubSpot CRM, custom analytics tracking
- ✅ **Customer Support** - Intercom live chat integration
- ✅ **SEO Optimized** - Sitemap, robots.txt, meta tags, schema markup

### 🎨 Design & UX
- ✅ **Modern Dark Theme** - Purple/pink gradient design
- ✅ **Fully Responsive** - Mobile, tablet, desktop optimized
- ✅ **Smooth Animations** - Framer Motion for engaging interactions
- ✅ **Optimized Performance** - Image optimization, lazy loading, PWA support

### 💻 Developer Experience
- ✅ **TypeScript** - Full type safety
- ✅ **App Router** - Next.js 14 App Router architecture
- ✅ **API Routes** - RESTful endpoints for orders, stats, webhooks
- ✅ **Environment Config** - Secure key management
- ✅ **Production Ready** - Build scripts, error handling, logging

---

## 🚀 Quick Start

### Installation

```bash
# Install dependencies
npm install

# Create environment file
# Add your API keys to .env.local

# Run development server
npm run dev
```

Visit [http://localhost:3003](http://localhost:3003) to see your site!

**👉 For detailed setup, see [QUICK_START.md](./QUICK_START.md)**

---

## 📚 Documentation

| Guide | Description |
|-------|-------------|
| [🚀 Quick Start](./QUICK_START.md) | Get running in 5 minutes |
| [🔑 API Keys Guide](./API_KEYS_GUIDE.md) | How to get all API keys |
| [🌐 Production Deployment](./PRODUCTION_DEPLOYMENT.md) | Database setup & deployment |

---

## 🔑 Environment Variables

Create a `.env.local` file:

```bash
# STRIPE (Required)
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=pk_test_...
STRIPE_SECRET_KEY=sk_test_...
STRIPE_WEBHOOK_SECRET=whsec_...

# ANALYTICS (Optional)
NEXT_PUBLIC_GA_MEASUREMENT_ID=G-XXXXXXXXXX
NEXT_PUBLIC_INTERCOM_APP_ID=abc12345
NEXT_PUBLIC_HUBSPOT_PORTAL_ID=12345678
```

**📖 Get your keys**: See [API_KEYS_GUIDE.md](./API_KEYS_GUIDE.md)

---

## 📊 Admin Dashboard

Access at `/admin` (password: `admin123`)

- 📈 Real-time stats
- 📦 Order management  
- 📊 Analytics tracking
- 🔄 Auto-refresh every 30 seconds

---

## 🚀 Deployment

```bash
# Deploy to Vercel
npm install -g vercel
vercel
```

**📖 Full guide**: See [PRODUCTION_DEPLOYMENT.md](./PRODUCTION_DEPLOYMENT.md)

---

## 📞 Need Help?

- [QUICK_START.md](./QUICK_START.md) - Get running fast
- [API_KEYS_GUIDE.md](./API_KEYS_GUIDE.md) - Get all your keys
- [PRODUCTION_DEPLOYMENT.md](./PRODUCTION_DEPLOYMENT.md) - Deploy to production

---

**🚀 Ready to launch?**

```bash
npm install && npm run dev
```

# adas-landing1
