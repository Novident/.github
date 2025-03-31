# 🌱 Contributing

First, we would like to thank you for your time and efforts on this project, we appreciate it.

> [!NOTE]
> The package version in `pubspec.yaml` of every package in Novident **should not be modified**; this will be handled by a maintainer or CI.
> Add updates to `Unreleased` in `CHANGELOG.md` following [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) format.

## 📋 Development Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install), which can be installed by following the instructions the
  provided link, also make sure to add it to your path so `flutter --version` and `dart --version` work
- [IntelliJ IDEA Community Edition](https://www.jetbrains.com/idea/download/)
  or [Android Studio](https://developer.android.com/studio) (with Dart and Flutter plugins) or
  use [VS Code](https://code.visualstudio.com/) (with Dart and flutter extensions)

## 🧪 Test your changes

Make sure you have the [Requirement](#-development-prerequisites) installed and configured correctly

To test your changes:

1. Make sure to read the [Development Notes](#development-notes) if you made certain changes in important parts of the package

## Guidelines 📝

1. **Code Style and Formatting**:

   Adhere to the Dart Coding Conventions (https://dart.dev/effective-dart).
   Use consistent naming conventions for variables, functions, classes, etc.
   Follow a consistent code formatting style throughout the project.

   We use [Dart lints](https://dart.dev/tools/linter-rules) to make the process easier.

2. **Documentation**:

   Document public APIs using Dart comments (https://dart.dev/effective-dart/documentation).
   Provide comprehensive documentation for any complex algorithms, data structures, or significant functionality.
   Write clear and concise commit messages and pull request descriptions.

3. **Performance**:

   Write efficient code and avoid unnecessary overhead.
   Profile the application for performance bottlenecks and optimize critical sections if needed.

4. **Bundle size**:

   Try to make the application size as less as possible but as much as needed

5. **Code Review**:

   Encourage code reviews for all changes to maintain code quality and catch potential issues early.
   Use pull requests and code reviews to discuss proposed changes and improvements.

6. **Versioning and Releases**:

   Follow semantic versioning for releases (https://semver.org/).
   Clearly document release notes and changes for each version.

   For now, we might introduce breaking changes in a non-major version but will always provide a migration
   guide in each release info.

7. **Consistency**:

   Adhere to a consistent coding style throughout the project for improvement readability and maintainability

8. **Meaningful Names**:

   Use descriptive variable, class, and function names that clearly convey their purpose.

9. **Testing**:

   Try to write tests (Widget or Unit tests or other types or tests) when possible

## 📝 Development Notes

- Package versioning is automated, PRs need to update `CHANGELOG.md` to add the changes in the `Unreleased` per [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) format.
