# Flutter Testing

A sample Flutter project to demonstrate testing.

## Getting Started

### Installation

- **To install app** 
```
flutter run lib/main.dart
```

### Testing

- **To run all unit tests**  
```
flutter test
```

- **To run a selected unit test**  
```
flutter test test_file_directory/test_file_name.dart
```

- **To run widget test**  
```
flutter test test_file_directory/test_file_name.dart
```

- **To run widget test in device**  
```
flutter run test_file_directory/test_file_name.dart
```

- **To run integration tests**  
```
flutter drive --driver integration_test/driver.dart --target integration_test/app_test.dart --profile
```

## Reference
- [Codelab - Flutter App Testing](https://codelabs.developers.google.com/codelabs/flutter-app-testing)
- [Docs - Testing Flutter apps](https://flutter.dev/docs/testing)
