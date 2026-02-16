# Phrase Gym — English Grammar Trainer

Interactive English grammar trainer built with Flutter. Practice sentence assembly, listening comprehension, and vocabulary drills.

## Live Demo

[**Open Phrase Gym**](https://dinislam-y.github.io/phrase-gym-web/)

Click **"Continue as Guest"** to try the app without registration.

## Features

- **Sentence Assembly** — build correct sentences from word chips with instant feedback
- **Listening Exercises** — listen and transcribe audio, improving comprehension skills
- **Binary Choice** — choose between commonly confused words (e.g., *make* vs *do*)
- **Vocabulary Builder** — learn new words with spaced repetition
- **Theory & Quizzes** — read grammar rules and test your understanding
- **Progress Tracking** — achievements, streaks, and detailed statistics

## Tech Stack

- **Flutter** (Dart) — cross-platform UI framework
- **flutter_bloc** (Cubit) — state management
- **GoRouter** — declarative routing
- **Firebase** — authentication and cloud sync
- **Clean Architecture** — Presentation / Domain / Data layers
- **GetIt + Injectable** — dependency injection
- **Freezed** — immutable data classes

## Architecture

```
lib/
  core/        # App-wide: router, theme, services, DI
  shared/      # Reusable widgets and cross-feature services
  features/
    auth/      # Authentication (email + guest mode)
    home/      # Home screen with lesson categories
    lesson/    # Sentence assembly exercises
    listening/ # Audio comprehension exercises
    binary_choice/ # A/B word choice training
    vocabulary/    # Vocabulary building
    theory/    # Grammar theory + quizzes
    profile/   # User profile and settings
    achievements/ # Gamification system
```

## Screenshots

| Home | Lesson | Listening |
|------|--------|-----------|
| Categorized grammar lessons | Drag-and-drop sentence building | Audio transcription exercises |

## Author

**Dinislam Yakupov** — Flutter Developer

## License

This is a demo deployment for portfolio purposes.
