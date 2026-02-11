# Fitness Basic UI

A Flutter fitness and nutrition app UI template. **Note: This is just a basic UI implementation** - it demonstrates the visual design and layout but does not include backend functionality, API integrations, or data persistence.

https://github.com/user-attachments/assets/aff47c85-5dd6-47e4-a812-cfe5f83c667f

## Getting Started

```bash
flutter pub get
flutter run
```

## Build

```bash
flutter build apk        # Android
flutter build ios        # iOS
flutter build web        # Web
```

## Project Structure

```
lib/
├── main.dart              # App entry point
├── pages/
│   └── home.dart          # Main home screen
└── models/
    ├── category_model.dart    # Category data model
    ├── diet_model.dart        # Diet recommendation model
    └── popular_model.dart     # Popular diets model
```

## Assets

- Icons: `assets/icons/` (SVG format)
- Fonts: `fonts/` (Poppins family)

## Dependencies

- `flutter_svg: ^2.2.3` - SVG image support
- `cupertino_icons: ^1.0.8` - iOS style icons
