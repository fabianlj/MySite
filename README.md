# MySite

A modern single-page website built with Flutter Web featuring a contact form.

## Features

- Responsive design
- Modern Material Design 3
- Contact form with validation
- Clean and professional layout

## Prerequisites

- Flutter SDK (3.0.0 or higher)
- Dart SDK (3.0.0 or higher)
- A web browser

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/fabianlj/MySite.git
   ```

2. Navigate to the project directory:
   ```bash
   cd MySite
   ```

3. Get dependencies:
   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run -d chrome
   ```

## Building for Production

To create a production build:

```bash
flutter build web
```

The built files will be available in the `build/web` directory.

## Project Structure

- `lib/main.dart` - Main application file containing all the widgets
- `pubspec.yaml` - Project configuration and dependencies

## Technologies Used

- Flutter Web
- Google Fonts
- Material Design 3
- URL Launcher for handling external links