# windows_app

```bash
#!/bin/bash
windows

flutter channel dev  
flutter upgrade  
flutter config --enable-windows-desktop  
flutter config --enable-macos-desktop  
flutter config --enable-linux-desktop  
flutter devices  
flutter run -d windows
flutter run -d macos
flutter run -d linux
flutter build windows
flutter build macos
flutter build linux

```

```bash
#!/bin/bash
web

flutter channel beta  
flutter upgrade  
flutter config --enable-web  
flutter devices  
flutter run -d chrome  
flutter build web  

```

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
