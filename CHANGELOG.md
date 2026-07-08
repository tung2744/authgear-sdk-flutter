# Changelog

## Unreleased

### Breaking changes

- Upgraded Flutter tooling to 3.44.5 (from 3.32.8). Consuming apps should be on a compatible Flutter version.
- Android: raised the Android Gradle Plugin to 9.0.1 (from 8.7.3), Kotlin to 2.3.20 (from 2.1.0), `compileSdk` to 36 (from 35), and the Java/Kotlin build target to 17 (from 11). Consuming apps must build with a JDK 17 toolchain and an AGP/Gradle version compatible with AGP 9.
