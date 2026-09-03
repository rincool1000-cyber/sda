# 💰 Trents Spending

A modern, mobile-friendly spending tracker that auto-saves your data every second. Built with React and ready for Cloudflare Pages deployment.

## ✨ Features

- ✅ **Auto-saves every second** - Your data is never lost
- 📱 **Mobile-friendly** - Responsive design that works great on phones
- 💚 **Monthly total** - Green money counter showing this month's spending
- 🎨 **Modern UI** - Beautiful gradient design with smooth animations
- 💾 **Local storage** - Data persists in your browser
- ⚡ **Fast & lightweight** - Built with Vite and React

## 📝 Track Everything

- What was bought
- Where it was bought
- Amount spent
- Date of purchase
- Extra notes/information

## 🚀 Getting Started

### Install dependencies
```bash
npm install
```

### Run locally
```bash
npm run dev
```

Open http://localhost:5173 in your browser.

### Build for production
```bash
npm run build
```

## 🌐 Deploy to Cloudflare Pages

1. **Install Wrangler** (if not already installed)
```bash
npm install -g wrangler
```

2. **Login to Cloudflare**
```bash
wrangler login
```

3. **Deploy**
```bash
npm run deploy
```

Or connect your GitHub repo to Cloudflare Pages for automatic deployments:
1. Go to [Cloudflare Dashboard](https://dash.cloudflare.com)
2. Navigate to Pages
3. Click "Create a project"
4. Connect your GitHub repository
5. Build settings:
   - Build command: `npm run build`
   - Build output directory: `dist`

## 💾 Data Storage

Currently uses **localStorage** for instant, reliable client-side storage. Your data:
- ✅ Saves automatically every second
- ✅ Persists across browser sessions
- ✅ Never leaves your device (privacy-first)

## 🎯 How It Works

1. Enter your purchase details in the form
2. Data automatically saves every second
3. See your monthly total update in real-time
4. View all expenses in a beautiful card layout
5. Delete expenses you no longer need

## 📱 Mobile Optimized

The app is fully responsive and optimized for mobile devices with:
- Touch-friendly buttons
- Easy-to-use form inputs
- Readable text sizes
- Smooth scrolling
- Native date picker

## 🎨 Design

- Clean, modern gradient design
- Smooth animations and transitions
- Accessible color contrast
- Visual feedback for all actions
- Beautiful card-based layout

Enjoy tracking your spending! 💚
