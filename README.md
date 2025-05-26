# # Soko Link

A modern web application connecting Kenyan farmers with local markets and buyers. Built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 🌾 **Kenyan Crop Database**: Pre-loaded data on common Kenyan crops with icons, prices, and farming tips
- 🌍 **Local Language Support**: Full support for English and Swahili (Kiswahili)
- 🗺️ **Market Map Integration**: Interactive map showing nearby markets and buyer hotspots
- 📱 **Offline Mode**: Work in the field without internet connection
- 👨‍🌾 **Farmer Profiles**: Verified farmer badges based on sales and ratings
- 💰 **M-Pesa Integration**: Ready for mobile payments
- 🎤 **Voice Input**: Support for voice commands in both English and Swahili

## Tech Stack

- **Framework**: Next.js 14
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Maps**: Leaflet.js
- **State Management**: Zustand
- **Internationalization**: i18next
- **PWA Support**: next-pwa
- **Database**: Supabase

## Getting Started

1. Clone the repository:
```bash
git clone [repository-url]
cd soko-link
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
soko-link/
├── app/              # Next.js app directory
├── components/       # React components
├── lib/             # Utility functions and contexts
├── public/          # Static assets
├── styles/          # Global styles
└── types/           # TypeScript type definitions
```

## Key Features Implementation

### Language Support
- Bilingual interface (English/Swahili)
- Context-based language switching
- Voice input support for both languages

### Market Map
- Interactive map using Leaflet.js
- Real-time location tracking
- Market and buyer location markers
- Distance calculation

### Offline Support
- Service Worker implementation
- IndexedDB for local data storage
- Background sync for data updates

### Farmer Profiles
- Verification system
- Rating mechanism
- Sales tracking
- M-Pesa integration

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
Created by Denzel Odhiambo

## Support

For support, email [support@sokolink.com](mailto:support@sokolink.com) or [denzelodhiambo10@gmail.com] (mailto:denzelodhiambo10@gmail.com).
