# Task Manager App

Task Manager App is a Flutter application that allows users to manage their tasks efficiently. The app supports creating, updating, deleting tasks, and setting task priorities. It also features state management with BLoC and persistent storage with SQLite.

## Features

- Create, update, and delete tasks
- Set task priorities (Low, Medium, High)
- View task details
- State management using BLoC
- Custom theming and responsive UI
- Set up deadlines
## Tech Stack

- **Framework**: Flutter
- **Language**: Dart
- **State Management**: `flutter_bloc`, `bloc_concurrency`
- **Storage**: `shared_preferences`
- **UI Design**:
  - Material Design components
  - Cupertino Icons
  - Custom SVG rendering with `flutter_svg`
  - Calendar integration with `table_calendar`
  - Custom fonts from the `Sora` family
- **Utilities**: `nb_utils` for common functions and widgets
- **Internationalization**: `intl` for localization and handling dates/numbers
- **Testing**: 
  - `flutter_test` for unit and widget testing
  - `mocktail` for mocking in tests