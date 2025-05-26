# SokoLink - Farmers Market Platform

SokoLink is a modern web platform connecting farmers with markets, making agriculture more accessible and profitable. Built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 🌍 Interactive map showing market locations
- 🎤 Voice input for easy search
- 🌙 Dark/Light mode support
- 🌐 Multi-language support (English & Swahili)
- 📱 Responsive design for all devices
- 🔒 Secure authentication system
- 📊 Real-time market prices
- 👥 Farmer profiles and verification

## Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Maps:** Leaflet
- **Authentication:** Supabase
- **State Management:** React Context
- **Icons:** React Icons
- **Animations:** CSS Animations

## Prerequisites

- Node.js 18.x or later
- npm 9.x or later
- Supabase account (for authentication)

## Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/sokolink.git
cd sokolink
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3002`

## Project Structure

```
sokolink/
├── app/                    # Next.js app directory
│   ├── about/             # About page
│   ├── contact/           # Contact page
│   ├── services/          # Services page
│   └── page.tsx           # Home page
├── components/            # React components
│   ├── auth/             # Authentication components
│   ├── layout/           # Layout components
│   └── ui/               # UI components
├── lib/                  # Utility functions and contexts
│   └── contexts/         # React contexts
├── public/              # Static assets
└── styles/             # Global styles
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
created by Denzel Odhiambo

## Support

For support, email support@sokolink.com or join our Slack channel.

## Acknowledgments

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Supabase](https://supabase.io/)
- [Leaflet](https://leafletjs.com/) 
