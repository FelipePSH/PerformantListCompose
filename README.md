# PerformantListCompose

This app demonstrates efficient list handling and smooth animations in Jetpack Compose.

<img src="https://github.com/FelipePSH/PerformantListCompose/assets/40181262/79b16014-742e-43f4-8d77-b6225a8deb42" alt="Seu GIF" width="290" height="600" />

## Features
- Smoothly expanding cards with animated content and color changes.
- LazyColumn for efficient rendering of large lists.
- State management using remember and rememberSaveable.
- Animations using animateContentSize and animateColorAsState.
- Custom Material3 theme for a visually appealing UI.
- Onboarding screen with a "Continue" button.

## Getting Started
1. Clone or download the repository.
2. Open the project in Android Studio.
3. Run the app on an emulator or connected device.

## Previews
Preview the app's appearance in both light and dark themes using the Android Studio preview tool.

## Code Structure
- `MainActivity`: Entry point of the app.
- `MyApp`: Root composable, managing app state and screens.
- `OnboardingScreen`: Welcome screen with a "Continue" button.
- `Greetings`: Displays a list of greeting cards using LazyColumn.
- `Greeting`: Composable for a single greeting card with expandable content.
- `CardContent`: Handles card expansion, content, and animations.

## Contribute
Feel free to open issues or pull requests for any enhancements or bug fixes.
