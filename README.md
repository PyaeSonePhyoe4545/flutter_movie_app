# 🎬 Flutter Netflix Clone

A beautiful and feature-rich Netflix clone built with Flutter, featuring modern UI components, state management with BLoC pattern, and movie data from TMDB API.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## ✨ Features

- 📱 **Cross-platform**: Runs on Android, iOS, Web, and Desktop
- 🎭 **Authentic Netflix UI**: Pixel-perfect recreation of Netflix's interface
- 🎬 **Real Movie Data**: Integration with TMDB (The Movie Database) API
- 🔍 **Browse & Search**: Discover movies and TV shows across different categories
- 📺 **Multiple Sections**: Home, Movies, TV Shows, New & Hot content
- 🌟 **Movie Details**: Rich detail pages with trailers, cast, and episodes
- 🎨 **Modern Design**: Clean, responsive UI with smooth animations
- 🏗️ **Clean Architecture**: Well-structured code following Flutter best practices

## 🛠️ Tech Stack

### Core Technologies
- **Flutter 3.32.5+** - Cross-platform UI framework
- **Dart 3.8.1+** - Programming language

### State Management
- **BLoC Pattern** (`flutter_bloc ^9.1.1`) - Predictable state management
- **Cubit** - Lightweight state management for simple states

### Navigation
- **GoRouter** (`go_router ^16.0.0`) - Declarative routing solution

### Networking & Data
- **HTTP** (`http ^1.4.0`) - API communication
- **TMDB API** - Movie and TV show data source

### UI & Animation
- **Cached Network Image** (`cached_network_image ^3.2.3`) - Efficient image loading
- **Shimmer** (`shimmer ^3.0.0`) - Loading skeleton animations
- **Sliver Tools** (`sliver_tools ^0.2.9`) - Advanced scrollable widgets
- **Lucide Icons** (`lucide_icons ^0.257.0`) - Beautiful icon set
- **Ionicons** (`ionicons ^0.2.2`) - Additional icon collection

### Utilities
- **Intl** (`intl ^0.20.2`) - Internationalization support

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- Flutter SDK 3.10.0 or higher
- Dart SDK 3.0.0 or higher
- Android Studio / VS Code
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/flutter_netflix.git
   cd flutter_netflix
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Set up TMDB API** (Optional for full functionality)
   - Create an account at [TMDB](https://www.themoviedb.org/)
   - Get your API key
   - Add your API key to the project configuration

4. **Run the app**
   ```bash
   # For debug build
   flutter run

   # For specific platform
   flutter run -d chrome    # Web
   flutter run -d windows   # Windows
   flutter run -d android   # Android
   flutter run -d ios       # iOS
   ```

### Building for Production

```bash
# Android APK
flutter build apk --release

# Android App Bundle
flutter build appbundle --release

# iOS
flutter build ios --release

# Web
flutter build web --release

# Windows
flutter build windows --release
```

## 📱 Screenshots

<!-- Add your app screenshots here -->
*Screenshots coming soon...*

## 🏗️ Project Structure

```
lib/
├── api/                    # API service classes
├── bloc/                   # BLoC state management
├── cubit/                  # Cubit state management
├── model/                  # Data models
├── repository/             # Data repository layer
├── screens/                # UI screens
├── utils/                  # Utility functions
├── widgets/                # Reusable UI components
└── main.dart              # App entry point
```

## 🎯 Key Features Implementation

### State Management
- **BLoC Pattern**: Clean separation of business logic and UI
- **Cubit**: Simple state management for toggles and animations
- **Repository Pattern**: Centralized data access layer

### Navigation
- **Declarative Routing**: Type-safe navigation with GoRouter
- **Deep Linking**: Support for web URLs and app links
- **Nested Navigation**: Complex navigation flows

### Performance
- **Image Caching**: Efficient image loading and caching
- **Lazy Loading**: Content loaded on demand
- **Optimized Builds**: Tree shaking and code splitting

## 🧪 Testing

```bash
# Run all tests
flutter test

# Run tests with coverage
flutter test --coverage

```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📋 TODO

- [ ] Add user authentication
- [ ] Implement watchlist functionality
- [ ] Add offline viewing capabilities
- [ ] Include video player integration
- [ ] Add more language support
- [ ] Implement dark/light theme switching
- [ ] Add unit and integration tests
- [ ] Performance optimizations

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [TMDB](https://www.themoviedb.org/) for providing the movie database API
- [Netflix](https://www.netflix.com/) for design inspiration
- Flutter community for amazing packages and resources

## 📞 Contact

If you have any questions or suggestions, feel free to reach out:

- **Email**: your.email@example.com
- **GitHub**: [@yourusername](https://github.com/yourusername)
- **LinkedIn**: [Your Name](https://linkedin.com/in/yourname)

---

⭐ If you found this project helpful, please give it a star!

## 📱 Platform Support

| Platform | Status |
|----------|--------|
| Android  | ✅ Supported |
| iOS      | ✅ Supported |
| Web      | ✅ Supported |
| Windows  | ✅ Supported |
| macOS    | ✅ Supported |
| Linux    | ✅ Supported |

## 🎨 Design Philosophy

This project follows Netflix's design principles:
- **Content First**: The content is the hero of the experience
- **Cinematic Feel**: Rich visuals and smooth animations
- **Personalization**: Tailored recommendations and categories
- **Cross-platform Consistency**: Same experience across all devices

Built with ❤️ using Flutter
