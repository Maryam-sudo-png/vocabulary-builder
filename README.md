# Vocabulary Builder App

A production-quality Flutter application for learning vocabulary, featuring local-first persistence, interactive quizzes, and intelligent progress tracking.

## Features

- **Vocabulary Management**: Add, edit, and delete words with meanings and examples.
- **Interactive Quizzes**: Test your knowledge with multiple-choice questions (Word to Meaning & Meaning to Word).
- **Progress Tracking**: Tracks attempts, accuracy, and streaks for every word.
- **Smart Difficulty**: Automatically adjusts word difficulty based on performance.
- **Offline First**: All data is stored locally using Hive. The app is fully functional and requires no account.

## Technical Architecture

- **Clean & Modular**: Separated into `data`, `logic`, and `ui` layers.
- **State Management**: `Provider` for reactive UI updates and decoupled business logic.
- **Persistence**: `Hive` for fast, efficient local storage.
- **Responsive Design**: Custom navy and gold theme with modern animations.

## Getting Started

1. Clone the repository.
2. Run `flutter pub get`.
3. Run `flutter run`.
