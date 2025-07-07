# BufferPics 📸

*A Flutter + Firebase app that efficiently loads and stores online images using smart caching.*

BufferPics allows users to view images loaded from the internet with blazing-fast performance using Flutter's **cached image** capabilities. It stores images locally after first load to enhance speed, reduce data usage, and provide a smooth user experience—even offline.

---

## 🚀 Features

* 🔁 **Cached Network Images**
  Loads images from URLs and caches them locally using `cached_network_image`.

* 🕗 **Faster Load Time**
  Once loaded, images are displayed instantly from local memory on next visit.

* 📶 **Offline Support**
  Cached images remain viewable without an internet connection.

* 📷 **Dynamic Image Grid**
  Clean UI to show multiple image cards in a responsive layout.

* 🔥 **Firebase-Ready**
  Firebase integration prepared for future storage, auth, or Firestore features.

* 📱 **Cross-Platform**
  Supports Android, iOS, Web, and Desktop (Flutter 3.x+).

---

## 🧠 What is Flutter Cached Image?

In Flutter, **cached image** refers to storing internet-downloaded images locally after the first view. This saves bandwidth and improves performance when navigating through the app again.

### 📦 Most commonly done using:

> **cached\_network\_image** package

### ✅ Key Benefits:

| Benefit           | Description                                     |
| ----------------- | ----------------------------------------------- |
| 🚀 Fast Reload    | Shows image instantly on second load            |
| 💾 Data Efficient | Reduces repeated downloads from the network     |
| 📡 Offline Access | Cached images are shown even without connection |
| 🎯 Smooth UX      | Avoids flickering or blank placeholders         |

### 🧱 Basic Usage:

```dart
CachedNetworkImage(
  imageUrl: "https://example.com/image.jpg",
  placeholder: (context, url) => CircularProgressIndicator(),
  errorWidget: (context, url, error) => Icon(Icons.error),
)
```

---

## 📸 Screenshots

<!-- TODO: Add actual screenshots to assets/README/ and link here -->

* Home Grid Page
* Single Image View

---

## 🛠️ Getting Started

### Prerequisites

* Flutter SDK 3.22+
* Dart 3.4+
* Firebase CLI (if using Firebase features)

### 🔧 Setup

```bash
# 1. Clone the repository
git clone https://github.com/onkarshirke/BufferPics-Flutter-Firebase-app.git
cd BufferPics-Flutter-Firebase-app

# 2. Install dependencies
flutter pub get

# 3. (Optional) Configure Firebase
flutterfire configure

# 4. Run the app
flutter run

---

## 📁 Project Structure

```
lib/
 ├── main.dart              # App entry point
 ├── pages/                 # UI pages/screens
 ├── widgets/               # Reusable UI components
 └── utils/                 # Helper functions or constants
assets/
 └── images/                # Image placeholders or logos
firebase/                   # (Optional) Firebase config files
```

## 🧪 Run Tests

```bash
flutter test
---

## 🤝 Contributing

Want to improve BufferPics? Great!

1. Fork the repo
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a pull request

---

## 👨‍💻 Author

**Onkar Shirke**
[GitHub](https://github.com/onkarshirke)

Project Link: [BufferPics Repository](https://github.com/onkarshirke/BufferPics-Flutter-Firebase-app)
