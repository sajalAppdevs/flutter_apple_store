# Flutter Apple Store

A modern e-commerce application built with Flutter and BLoC state management pattern. This project demonstrates best practices in Flutter development, clean architecture, and state management using the BLoC pattern.

## Features

- Material Design 3 UI with custom Iranian Sans font
- Clean Architecture implementation
- BLoC pattern for state management
- HTTP integration for API calls
- Responsive design for multiple screen sizes

## Architecture

The project follows Clean Architecture principles with the following layers:

- **Presentation Layer**: Contains UI components and BLoC implementations
- **Domain Layer**: Contains business logic and use cases
- **Data Layer**: Handles data operations and external API communications

### State Management

The application uses the BLoC (Business Logic Component) pattern with the following packages:
- `flutter_bloc`: ^8.1.3 - For implementing the BLoC pattern
- `equatable`: ^2.0.5 - For value equality comparisons

## Getting Started

### Prerequisites

- Flutter SDK (>=3.1.0)
- Dart SDK (>=3.1.0)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/flutter_apple_store.git
```

2. Navigate to the project directory:
```bash
cd flutter_apple_store
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## Dependencies

Key dependencies used in this project:

- `flutter_bloc`: For state management
- `equatable`: For value comparisons
- `http`: For API communications
- `cupertino_icons`: For iOS-style icons

## Project Structure

```
lib/
├── Shop/
│   └── presentation/
│       └── pages/
│           └── main_page.dart
├── assets/
│   └── fonts/
│       └── A-Iranian-Sans/
└── main.dart
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
