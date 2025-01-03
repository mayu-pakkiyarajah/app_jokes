# Jokes World

A Flutter application that fetches and displays jokes. This app demonstrates the use of state management, animations, and custom widgets in Flutter.

## Features

- **Fetch Jokes**: Fetches jokes from a remote API.
- **Cache Jokes**: Caches jokes for offline access.
- **Pull-to-Refresh**: Refresh jokes by pulling down the list.
- **Custom AppBar**: A custom AppBar with gradient background and refresh animation.
- **Loading Indicator**: Displays a loading indicator while fetching jokes.
- **Empty State**: Shows an empty state message when no jokes are available.
- **Error Handling**: Handles errors gracefully and displays appropriate messages.
- **Responsive UI**: Adapts to different screen sizes and orientations.

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Dart SDK: Included with Flutter

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mayu-pakkiyarajah/app_jokes.git
   cd app_jokes

### Project structure
jokes_app/
├── lib/
│   ├── main.dart         # Entry point of the application
│   ├── screens/          # UI screens for displaying jokes
│   ├── widgets/          # Custom reusable widgets
│   ├── services/         # API service and local caching logic
│   └── models/           # Data models for jokes
├── pubspec.yaml          # Project dependencies and metadata
└── README.md             # Project documentation

