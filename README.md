
# Course App

A simple Flutter application demonstrating BLoC pattern, clean architecture, and REST API integration for managing a list of courses.

![Capture d'écran 2025-04-10 233630](https://github.com/user-attachments/assets/cbf9a41c-0f14-46bf-86c4-47d6c13f93a5)
![image](https://github.com/user-attachments/assets/cb3939ce-5382-4a6e-b417-8394d849a7b5)



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

@lemrin0
