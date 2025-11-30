# HelloWorld Android App

A minimal Android "Hello World" application built with Kotlin and the Android Gradle Plugin.

## Project Structure
- `app/`: Application module containing the Kotlin activity, manifest, resources, and tests.
- `gradlew` / `gradlew.bat`: Gradle wrapper scripts configured for Gradle 8.2.2.
- `settings.gradle` & `build.gradle`: Project-level Gradle configuration.

## Building
Ensure the Android SDK is installed and available. The Gradle wrapper JAR is not tracked to avoid committing binaries, so regenerate it with your locally installed Gradle before using the wrapper scripts:

```bash
gradle wrapper
./gradlew assembleDebug
```
