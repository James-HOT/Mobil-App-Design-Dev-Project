# Mobile App Design & Development Project

Android application project built with Gradle. The current repository structure indicates a school-finder style app module (`app`) with Java source files and Android resources.

## Project Overview

This project appears to be an Android app focused on school discovery/navigation workflows (based on package paths like `com.example.hkschoolfinder` and assets such as `SCH_LOC_EDB.csv`).

Typical user flows likely include:
- Browsing school records in a list
- Viewing school details
- Exploring locations on a map
- Searching/filtering schools

## Tech Stack

- Android (App module)
- Java (application source)
- Gradle (Kotlin DSL)
- Android XML layouts/resources

## Prerequisites

Before running the app, make sure your environment includes:
- Android Studio (latest stable recommended)
- Android SDK and platform tools
- JDK 17 (commonly required by recent Android Gradle Plugin versions)

## Getting Started

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd Mobil-App-Design-Dev-Project
   ```
2. Open the project in Android Studio.
3. Let Gradle sync complete.
4. Run the `app` configuration on an emulator or physical Android device.

## Build and Run (CLI)

Use the Gradle wrapper:

```bash
./gradlew assembleDebug
./gradlew installDebug
```

If you have connected tests configured:

```bash
./gradlew test
./gradlew connectedAndroidTest
```

## Project Structure

```text
.
├── app/                        # Main Android application module
│   ├── src/main/java/          # Java source code
│   ├── src/main/res/           # Android resources (layouts, drawables, values)
│   ├── src/main/assets/        # Static asset files
│   └── build.gradle.kts        # Module-level Gradle config
├── gradle/                     # Gradle wrapper and version catalog
├── build.gradle.kts            # Root Gradle config
├── settings.gradle.kts         # Module include/settings
└── gradlew                     # Gradle wrapper script
```

## Notes

- The repository currently appears to contain Git LFS pointer files in place of normal source contents. If you see lines like `version https://git-lfs.github.com/spec/v1` inside source/config files, ensure Git LFS is properly installed and pulled:

  ```bash
  git lfs install
  git lfs pull
  ```

- After LFS content is pulled successfully, update this README with the exact app features, architecture, and setup details.

## Contributing

1. Create a feature branch.
2. Keep changes focused and reviewable.
3. Run build/tests before opening a pull request.

## License

Add your project license here (for example: MIT, Apache-2.0, or proprietary internal use).
