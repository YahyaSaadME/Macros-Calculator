# AI-Powered Macro Calculator PWA 🍎📱

A Progressive Web App for calculating and tracking macronutrients using AI-powered food recognition.

## Features 🌟

- **PWA Ready**: Installable as a native app on mobile and desktop
- **AI-Powered**: Uses Groq Llama 3.1 for accurate nutrition data
- **Food Logo**: Beautiful food-themed icon and design
- **Offline Support**: Works offline after first load
- **Responsive Design**: Optimized for all screen sizes
- **Local Storage**: Saves your food records and meals

## Installation 📲

### For Users:

1. Visit your deployed Netlify URL
2. Look for the "📱 Install App" button
3. Click to install on your device
4. The app will appear on your home screen/desktop

### For Developers:

1. **Deploy to Netlify**:

   - Connect your GitHub repository to Netlify
   - Deploy from the main branch
   - Your app will be available at `https://your-app-name.netlify.app`

2. **Generate Icons** (if needed):
   - Open `create-icons.html` in your browser
   - Icons will download automatically
   - Place `icon-192.png` and `icon-512.png` in your root directory

## PWA Features ⚡

- **Manifest File**: `manifest.json` configures app metadata
- **Service Worker**: `sw.js` enables offline functionality
- **Install Prompt**: Automatic installation prompt for eligible devices
- **Theme Colors**: Beautiful blue theme matching your brand

## Food Logo Design 🎨

The app features a custom food-themed logo with:

- 🍎 Apple representing healthy eating
- 🍽️ Plate and utensils for food tracking
- 🧮 Calculator elements for macro calculations
- 🤖 AI indicator showing smart features
- Color-coded macro indicators (P=Protein, C=Carbs, F=Fat)

## Development Setup 🛠️

1. Clone the repository
2. Add your Groq API key in the app settings
3. Test locally by opening `index.html`
4. Deploy to Netlify for full PWA functionality

## Browser Support 📱

- Chrome/Edge: Full PWA support
- Safari: Limited PWA support (iOS 11.3+)
- Firefox: Full PWA support
- Mobile browsers: Excellent support

## Files Structure 📁

```
macros/
├── index.html          # Main application
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── icon-192.png       # App icon (192x192)
├── icon-512.png       # App icon (512x512)
├── icon-192.svg       # Source icon
├── icon-512.svg       # Source icon
├── create-icons.html  # Icon generator
└── README.md          # This file
```

## Deployment Checklist ✅

- [ ] Icons generated and placed correctly
- [ ] Manifest.json configured
- [ ] Service worker registered
- [ ] HTTPS enabled (required for PWA)
- [ ] Install prompt working
- [ ] Offline functionality tested

## Support 💡

For issues or questions, check:

1. Browser console for errors
2. Ensure HTTPS is enabled
3. Clear cache and reload
4. Test in incognito mode

---

Made with ❤️ for healthy eating and macro tracking!
