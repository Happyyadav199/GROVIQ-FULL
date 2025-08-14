# Groviq - Blinkit-style Flutter Boilerplate (Full)

Features included:
- Product grid similar to grocery apps
- Search bar
- Simple cart (in-memory using Provider)
- Placeholder WordPress API service (replace baseUrl)
- Green theme and Groviq branding
- codemagic.yaml ready for building release APK and publishing artifact

How to use:
1. Extract and open in VS Code / Android Studio.
2. Run `flutter pub get`.
3. Replace `assets/images/logo.png` with your logo.
4. Update `lib/services/api_service.dart` baseUrl to your WordPress site (optional).
5. Commit & push to GitHub.
6. Connect repo to Codemagic. The included `codemagic.yaml` will build a release APK and publish it as artifact:
   `build/app/outputs/flutter-apk/app-release.apk`

Notes:
- This is a starter boilerplate. Integrate authentication, payments, and production WordPress endpoints as needed.
