
# Course App

A simple Flutter application demonstrating BLoC pattern, clean architecture, and REST API integration for managing a list of courses.

## Features

- View list of courses from an API
- Clean separation of concerns (DataProvider, Repository, BLoC, UI)
- State management using BLoC
- Custom route management

## Structure

```
lib/
├── bloc_observer.dart
├── course/
│   ├── bloc/
│   │   ├── course_bloc.dart
│   │   ├── course_event.dart
│   │   └── course_state.dart
│   ├── data_provider/
│   │   └── course_data.dart
│   ├── models/
│   │   └── course.dart
│   ├── repository/
│   │   └── course_repository.dart
│   └── screens/
│       ├── course_list_screen.dart
│       └── course_route.dart
└── main.dart
```

## Getting Started

1. Clone the repository
2. Run `flutter pub get`
3. Use `flutter run` to launch the app

## Dependencies

- flutter_bloc
- http

## Author

Your Name
