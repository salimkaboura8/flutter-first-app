<div align="center">

# 🚀 Flutter First App

**My first Flutter project: a profile card, a quiz page and a BLoC counter**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![BLoC](https://img.shields.io/badge/BLoC-Pattern-13B9FD?style=for-the-badge)

[📂 Source](lib) · [🎨 UI](lib/ui) · [🧠 BLoC](lib/bloc)

</div>

---

## 📖 Overview

An introduction to **Flutter** fundamentals. The app opens on a styled profile page and links to a quiz screen. Along the way it covers layouts, assets, named routes and a first look at state management with a `CountBloc`.

## 🔄 How It Works

| Step | What happens |
|:---:|---|
| 1️⃣ | `MaterialApp` opens on the **Profile Home Page**, wrapped in a `BlocProvider` |
| 2️⃣ | The profile card is built with `Stack`, `CircleAvatar` and decorated boxes |
| 3️⃣ | A named route (`/second`) goes to the **Quiz** page |
| 4️⃣ | `CountBloc` adds each incoming event to its current count |

## ✨ Highlights

| 🎨 Layout | 🧭 Navigation | 🧠 State |
|---|---|---|
| `Stack`, `Column`, `Padding`<br>Rounded cards<br>Image assets | `MaterialApp` routes<br>`Navigator.pushNamed` | `flutter_bloc` counter<br>`BlocProvider` at the root |

## 🚀 Quick Start

```bash
git clone https://github.com/salimkaboura8/flutter-first-app.git
cd flutter-first-app

flutter pub get
flutter run
```

---

<div align="center">
Made with ❤️ by <a href="https://github.com/salimkaboura8">Salim Kaboura</a>
</div>
