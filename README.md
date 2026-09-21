# Adaptive UI Using ListView and ImageView

## 📱 Project Overview

This project demonstrates how to create an **Adaptive User Interface in Android** using **ListView and ImageView**.

The application displays a list of learning topics. Each list item contains an image, title, and description. The layout is designed to adjust to different screen sizes by using responsive Android XML attributes such as `match_parent`, `layout_weight`, `dp`, and `sp`.

The project is developed using **Android Studio, Kotlin, and XML**.

---

## 🎯 Aim

To create an adaptive Android user interface using **ListView and ImageView**, where multiple items can be displayed in a scrollable list with images and descriptions.

---

## 🛠️ Technologies Used

- Android Studio
- Kotlin
- XML
- Android SDK
- ListView
- ImageView
- Custom BaseAdapter
- AndroidX AppCompat

---

## 📌 Features

- Adaptive and responsive user interface
- Scrollable ListView
- ImageView for displaying topic icons
- Custom ListView adapter
- Title and description for each item
- Item click functionality
- Toast message when an item is selected
- XML-based UI design
- Kotlin-based application logic
- Compatible with different Android screen sizes

---

## 📂 Project Structure

```text
AdaptiveListView/
│
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── com/
│           │       └── example/
│           │           └── adaptivelistview/
│           │               ├── MainActivity.kt
│           │               ├── Item.kt
│           │               └── ItemAdapter.kt
│           │
│           ├── res/
│           │   ├── drawable/
│           │   │   ├── ic_android.xml
│           │   │   ├── ic_java.xml
│           │   │   ├── ic_python.xml
│           │   │   ├── ic_data.xml
│           │   │   └── ic_database.xml
│           │   │
│           │   ├── layout/
│           │   │   ├── activity_main.xml
│           │   │   └── list_item.xml
│           │   │
│           │   └── values/
│           │       ├── colors.xml
│           │       ├── strings.xml
│           │       └── themes.xml
│           │
│           └── AndroidManifest.xml
│
├── build.gradle.kts
├── settings.gradle.kts
├── gradle.properties
└── README.md
