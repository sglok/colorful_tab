# Flutter Colorful TabBar

A colorful TabBar for Flutter where each tab has a color (inspired by SmartNews app).

A customizable and animated tab bar for Flutter applications.

## 📌 About This Package

This package is a modified version of [original_package_name](https://pub.dev/packages/flutter_colorful_tab) by [datvu7](https://github.com/datvu7/flutter_colorful_tab). 

### What's Changed/Added:
- ✨ Fixed changes for latest flutter package

## 📦 Installation

Add to your `pubspec.yaml`:

```yaml
dependencies:
  colorful_tab: ^1.0.0

![demo](https://github.com/sglok/colorful_tab/main/demo.gif)

## Getting Started

Add this to your package's pubspec.yaml file:
```yaml
  dependencies:
    colorful_tab: {current_version}
```

Import the library in your file:
```dart
import 'package:colorful_tab/colorful_tab.dart';
```

Use the colorful_tab like this: 
```dart
ColorfulTabBar(
  tabs: [
    TabItem(color: Colors.red, title: Text('Home')),
    TabItem(color: Colors.green, title: Text('Favorite')),
    TabItem(color: Colors.orange, title: Text('Search')),
    TabItem(color: Colors.green, title: Text('Settings')),
  ],
  controller: _tabController,
)

// all available parameters of TabItem
  TabItem(
    color: Colors.orange,
    unselectedColor: Colors.orange.shade600,
    title: const Text('Search'),
    labelColor: Colors.black,
    unselectedLabelColor: Colors.yellow,
    labelStyle: const TextStyle(fontWeight: FontWeight.bold),
    unselectedLabelStyle: const TextStyle(fontWeight: FontWeight.normal),
  ),
```