# Flutter Shopping List App

This project is a simple Shopping List application built with Flutter and Dart. It is based on a section from the Udemy course: **Flutter & Dart - The Complete Guide [2025 Edition]**.

## Features

- Add new grocery items with name, quantity, and category
- View a list of added items
- Persist data using Firebase Realtime Database (requires configuration)
- Responsive UI using Flutter's Material Design

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- Dart SDK (comes with Flutter)
- An editor like [VS Code](https://code.visualstudio.com/) or Android Studio

### Installation

1. **Clone the repository:**

   ```sh
   git clone <your-repo-url>
   cd flutter_shopping_list_app
   ```

2. **Install dependencies:**

   ```sh
   flutter pub get
   ```

3. **Set up environment variables:**

   - Copy `.env.template` to `.env`
   - Add your Firebase Realtime Database URL to the `.env` file:

     ```env
     FIREBASE_URL=your-firebase-url
     ```

4. **Run the app:**

   ```sh
   flutter run
   ```

## Project Structure

- `lib/` - Main Dart source code
  - `main.dart` - App entry point
  - `widgets/` - UI components
  - `models/` - Data models
  - `data/` - Static data (e.g., categories)
- `test/` - Unit and widget tests
- `android/`, `ios/`, `linux/`, `macos/`, `windows/`, `web/` - Platform-specific code

## Dependencies

- [flutter_dotenv](https://pub.dev/packages/flutter_dotenv) - For environment variables
- [http](https://pub.dev/packages/http) - For HTTP requests
- [cupertino_icons](https://pub.dev/packages/cupertino_icons) - iOS style icons

See [`pubspec.yaml`](pubspec.yaml) for the full list.

## Notes

- This project is for educational purposes and follows the structure and concepts taught in the Udemy course.
- You need to set up your own Firebase project and database for full functionality.

## License

This project is licensed under the MIT License.

---

_Based on a section from [Flutter & Dart - The Complete Guide [2025 Edition]](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/)._
