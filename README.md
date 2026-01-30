# Hydration-Tracker💧

A modern, multilingual web application to help you stay hydrated and track your daily water intake. Built with React, TypeScript, and Vite.

## Features

- 🌍 **Multi-language Support**: Available in 7 languages (English, Spanish, Mandarin, French, Japanese, Korean, German)
- 📊 **Daily Water Intake Tracking**: Calculate and track your recommended daily water intake based on age and weight
- 🌡️ **Weather Integration**: Automatically adjust water recommendations based on weather conditions
- 🔔 **Notifications**: Get reminders to drink water at customizable intervals
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
- 💾 **Local Storage**: All data is stored locally on your device for privacy
- 🎨 **Modern UI**: Beautiful, dark-themed interface with smooth animations

## Tech Stack

- **React 19** - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **Zustand** - State management
- **React Router** - Routing
- **Tailwind CSS** - Styling
- **Zod** - Schema validation

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- pnpm (recommended) or npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SergioSediq/hydration-tracker.git
cd hydration-tracker
```

2. Install dependencies:
```bash
pnpm install
```

3. Start the development server:
```bash
pnpm dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
pnpm build
```

The production build will be in the `dist` directory.

## Project Structure

```
hydration-tracker/
├── src/
│   ├── assets/          # Static assets
│   ├── components/      # React components
│   ├── core/            # Core business logic
│   ├── i18n/            # Internationalization
│   │   └── translations/ # Language files
│   ├── pages/           # Page components
│   ├── schemas/         # Zod schemas
│   ├── stores/          # Zustand stores
│   ├── styles/          # Global styles
│   └── util/            # Utility functions
├── public/              # Public assets
└── dist/                # Production build
```

## Available Languages

- 🇺🇸 English (en-US)
- 🇪🇸 Spanish (es-ES)
- 🇨🇳 Mandarin Chinese (zh-CN)
- 🇫🇷 French (fr-FR)
- 🇯🇵 Japanese (ja-JP)
- 🇰🇷 Korean (ko-KR)
- 🇩🇪 German (de-DE)

## Features in Detail

### Water Intake Calculation
The app calculates your recommended daily water intake based on:
- Your age
- Your weight
- Weather conditions (if enabled)
- Your preferred measurement units

### Custom Containers
Track water intake using custom containers with personalized names.

### History Tracking
View your water intake history with timestamps and container information.

### Settings
Customize your experience:
- Enable/disable weather detection
- Configure notification intervals
- Change language
- Adjust measurement units

## Development

### Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm preview` - Preview production build
- `pnpm lint` - Run ESLint

### Adding a New Language

1. Create a new JSON file in `src/i18n/translations/` following the naming convention `{language-code}.json`
2. Copy the structure from `en-US.json` and translate all values
3. Add the import and entry in `src/i18n/index.ts`

## Deployment

The app is configured for deployment on Vercel. Simply push to your repository and Vercel will automatically deploy.

## Author

**Sergio Sediq**

- GitHub: [@SergioSediq](https://github.com/SergioSediq)

## License

This project is private and proprietary.

## Contributing

This is a personal project. Contributions are not currently being accepted.

---

Made with 💧 and ❤️ by Sergio Sediq
