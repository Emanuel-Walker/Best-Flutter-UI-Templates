# Start here

## Goal

Inspect or run the historical Flutter UI examples without mistaking this fork for a current original project.

## 1. Read the status

```text
FORK_STATUS.md
LICENSE
```

## 2. Enter the Flutter app

```bash
cd best_flutter_ui_templates
```

## 3. Check your Flutter/Dart version

```bash
flutter --version
dart --version
```

The project expects Dart 2.x:

```text
>=2.7.0 <3.0.0
```

**STOP:** if you are using a modern incompatible Dart release and do not intend to migrate the project.

## 4. Historical run path

With a compatible toolchain:

```bash
flutter pub get
flutter run
```

## Useful folders

Inside `best_flutter_ui_templates/`:

- `lib/` = Dart UI code
- `assets/` = images and fonts
- `test/` = Flutter tests, if present
- `pubspec.yaml` = dependencies and asset declarations

## Definition of done

For learning purposes, stop when you can:
- run or inspect one screen
- identify where its Dart widget code lives
- identify which assets it uses
- explain that the source is an upstream historical template
