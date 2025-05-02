# JTASK Android Application

A simple yet functional to-do application built with Kotlin and Jetpack Compose that demonstrates modern Android development practices.

## Features

- Add new tasks
- Mark tasks as complete/incomplete
- Delete tasks
- Persistent storage using Room Database
- Clean Material Design 3 UI
- State management with ViewModel

## Technologies Used

- **Kotlin** - Primary programming language
- **Jetpack Compose** - Modern declarative UI toolkit
- **Room Database** - For local data persistence
- **ViewModel** - For UI-related data management
- **Flow** - For reactive data streams
- **Material Design 3** - For modern UI components

## Screenshots

![App Screenshot](/screenshots/screenshot1.png)
![App Screenshot](/screenshots/screenshot2.png)

## Installation

1. Clone this repository
2. Open the project in Android Studio (Flamingo or newer recommended)
3. Build and run the app on an emulator or physical device

## Architecture

The app follows a clean architecture approach with:

- **Data Layer**: Room database and repository
- **Domain Layer**: ViewModel for business logic
- **UI Layer**: Composable functions for presentation

## Key Concepts Demonstrated

1. **Declarative UI** with Jetpack Compose
2. **State management** with remember and mutableState
3. **Database operations** with Room
4. **Asynchronous operations** with Coroutines
5. **Reactive programming** with Flow
6. **Dependency injection** (manual) with ViewModelFactory

## Getting Started with Jetpack Compose

If you're new to Jetpack Compose, here are the key concepts used in this project:

- `@Composable` functions - Building blocks of UI
- `Modifiers` - For styling and layout
- `State management` - Using remember and mutableStateOf
- `Material Components` - Buttons, TextFields, etc.
- `LazyColumn` - Efficient list rendering

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

MIT License