# NutriBite Nutrition Assistant

NutriBite Nutrition Assistant is a .NET MAUI-based "Food & Drinks" course project application. The app can record food and drinks, display nutrition summaries, validate user inputs, and demonstrate mobile device hardware features.

## Key Features

- Food and drink list with search and detail pages.
- Add record form with validation for required fields and nutrition values.
- Use camera to take food photos and preview them.
- Use location to record meal or purchase locations.
- Use text-to-speech to read nutrition summaries and help content.
- Use vibration and haptic feedback for operation reminders.
- Support theme switching and large text mode.
- Includes semantic labels, screen reader announcements, and clear validation prompts.

## Grading Criteria Coverage

- UI/UX & Accessibility: XAML pages, bottom navigation, consistent visual style, dark mode, semantic descriptions, and screen reader announcements.
- Mobile Hardware: Camera, location, text-to-speech, vibration, and haptic feedback.
- Functionality Completeness: List, search, add, detail, settings, and hardware demo flow.
- Validation & Error Handling: Required field checks, number checks, permission errors, and hardware unavailable prompts.
- Code Quality: Separation of models and services, clear naming, reusable catalog service, and well-scoped page code.
- Deployment: .NET MAUI cross-platform app targeting Android and Windows.
- GitHub Usage: Recommend continuous commits, e.g., "Add food list", "Implement hardware page", "Add input validation".

## How to Run

Open `FoodDrinkApp.csproj` or `FoodDrinkApp.sln` with Visual Studio 2022 that has the .NET MAUI workload installed.

Recommended demo targets:

- Android Emulator
- Windows Machine

Windows build command:

```powershell
dotnet build .\FoodDrinkApp.csproj -f net9.0-windows10.0.19041.0
```

Android build command:

```powershell
dotnet build .\FoodDrinkApp.csproj -f net9.0-android
```

This project uses `Directory.Build.props` to place build outputs in `C:\MauiBuild\NutriTrack\` to avoid Android packaging tool issues with `assets` paths in Chinese directories.

## Screen Recording Demo Checklist

- Explain the "Food & Drinks" theme and "NutriBite" app concept.
- Show search, detail page, and adding a new record.
- Demonstrate validation prompts when required fields are missing or invalid numbers are entered.
- Demonstrate camera, location, text-to-speech, vibration, and haptic feedback.
- Show dark mode and large text mode.
- Show key code files: models, services, pages, and Android permission configuration.
- Show Android and Windows deployment results.
- Show GitHub commit history and README.
