# 🎬 Mobile Movie App

A modern mobile application for movie discovery and management, built with **Expo** and **React Native**.

## 📱 About the Project

The **Mobile Movie App** is a cross-platform application that allows users to:
- 🔍 Search for movies
- 💾 Save favorite movies
- 👤 Manage user profile
- 📺 View movie details

## 🛠️ Technologies Used

- **Expo** - React Native development framework
- **React Native** - Mobile development framework
- **TypeScript** - Typed programming language
- **NativeWind** - CSS framework for React Native
- **Tailwind CSS** - Utility-first CSS framework
- **Expo Router** - File-based routing system
- **React Navigation** - Screen navigation

## 🚀 Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn
- Expo CLI
- Android Studio (for Android) or Xcode (for iOS)

### Installation

1. **Clone the repository**
   ```bash
   git clone [REPOSITORY_URL]
   cd mobile-movie-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the project**
   ```bash
   npm start
   # or
   npx expo start
   ```

### Running Options

After running `npm start`, you'll have the following options:

- **Expo Go**: Scan the QR code with the Expo Go app on your device
- **Android Emulator**: Press `a` to open in Android emulator
- **iOS Simulator**: Press `i` to open in iOS simulator (macOS only)
- **Web**: Press `w` to open in browser

## 📁 Project Structure

```
mobile-movie-app/
├── app/                    # Application pages (Expo Router)
│   ├── (tabs)/            # Tab navigation
│   │   ├── index.tsx      # Home screen
│   │   ├── search.tsx     # Search screen
│   │   ├── saved.tsx      # Saved movies screen
│   │   └── profile.tsx    # Profile screen
│   ├── movies/            # Movie pages
│   │   └── [id].tsx       # Movie details
│   └── _layout.tsx        # Main layout
├── assets/                # Static resources
│   ├── icons/            # Application icons
│   ├── images/           # Images and backgrounds
│   └── fonts/            # Custom fonts
├── constants/            # Constants and configurations
├── interfaces/           # TypeScript type definitions
└── types/               # Additional types
```

## 🎨 Design System

The project uses a custom color system:

- **Primary**: `#030014` - Main dark color
- **Secondary**: `#151312` - Secondary color
- **Accent**: `#AB8BFF` - Highlight color
- **Light**: Light tones for texts and elements
- **Dark**: Dark tones for backgrounds

## 📱 Features

### ✅ Implemented
- [x] Project base structure
- [x] Tab navigation
- [x] Routing system
- [x] NativeWind styling configuration
- [x] TypeScript interface definitions

### 🚧 In Development
- [ ] Movie API integration
- [ ] Search interface
- [ ] Favorites system
- [ ] User profile
- [ ] Movie details

## 🔧 Available Scripts

```bash
npm start          # Start development server
npm run android    # Run on Android emulator
npm run ios        # Run on iOS simulator
npm run web        # Run in browser
npm run lint       # Run linter
```

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

If you encounter any issues or have questions, please open an [issue](https://github.com/your-username/mobile-movie-app/issues) in the repository.

---

Built with ❤️ using Expo and React Native
