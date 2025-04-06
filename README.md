# Animanani - Anime & Manga Connection App

Animanani is a mobile application that connects anime episodes with their corresponding manga chapters, allowing fans to seamlessly track and explore both formats of their favorite series.

## Features

- Browse a curated list of anime series
- View detailed information about each anime
- See which manga chapters correspond to specific anime episodes
- Beautiful, user-friendly interface
- Offline capabilities (coming soon)
- User accounts for tracking watched episodes and read chapters (coming soon)

## Tech Stack

- React Native
- TypeScript
- React Navigation
- AsyncStorage (for future offline support)

## Getting Started

### Prerequisites

- Node.js (v14 or newer)
- npm or yarn
- React Native CLI
- Android Studio (for Android development)
- Xcode (for iOS development, macOS only)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/animanani.git
cd animanani
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm start
# or
yarn start
```

4. Run on Android:
```bash
npm run android
# or
yarn android
```

5. Run on iOS (macOS only):
```bash
npm run ios
# or
yarn ios
```

## Project Structure

```
animanani/
├── src/              # Source code
│   ├── assets/       # Images, fonts, and other static assets
│   ├── components/   # Reusable UI components
│   ├── hooks/        # Custom React hooks
│   ├── navigation/   # Navigation configuration
│   ├── screens/      # App screens
│   └── services/     # API services and data handling
├── android/          # Android-specific files
├── ios/              # iOS-specific files
├── App.tsx           # Main app component
└── index.js          # Entry point
```

## Roadmap

- [ ] Implement user authentication
- [ ] Add search and filtering functionality
- [ ] Create a favorites system
- [ ] Add tracking for watched episodes and read chapters
- [ ] Implement offline mode
- [ ] Add notifications for new episodes and chapters

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all anime and manga creators for their amazing work
- Inspiration from similar apps in the space
