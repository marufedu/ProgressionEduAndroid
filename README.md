# Progression Edu Android App

Premium six-page Android app for Progression Edu, built with Jetpack Compose.

## Included pages
- Home
- English Course
- Chinese / HSK
- Our Teachers
- About Us
- Contact / Admission

## Build without Android Studio
This project includes a GitHub Actions workflow at `.github/workflows/build-apk.yml` that builds the debug APK in the cloud. GitHub-hosted runners provide the build machine and workflow artifacts can be downloaded after the run.

## Local build
Requires JDK 17 and Android SDK. Run `./gradlew assembleDebug`.
