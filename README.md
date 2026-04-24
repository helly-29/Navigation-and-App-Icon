# Flutter Navigation App – Helly Leuva

A simple Flutter application demonstrating navigation between two screens using the `Navigator` widget. This project helps beginners understand how screen transitions work in Flutter.

## 📱 Features

* Two-screen navigation
* Navigate from First Screen → Second Screen
* Navigate back using `Navigator.pop()`
* Clean and simple UI
* Beginner-friendly structure

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

* Flutter SDK
* Dart
* Android Studio or Visual Studio Code
* Emulator or physical device

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-navigation-app.git
   ```

2. Navigate to the project folder:

   ```bash
   cd flutter-navigation-app
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

## 📂 Project Structure

```id="nav321"
lib/
 └── main.dart   # Contains both FirstScreen and SecondScreen
```

## 🧭 How Navigation Works

* Uses `Navigator.push()` to move to the second screen
* Uses `MaterialPageRoute` for page routing
* Uses `Navigator.pop()` to return to the first screen

##  UI Components

* **First Screen**

  * AppBar with title
  * Button to navigate to second screen

* **Second Screen**

  * AppBar with different title
  * Text message
  * Button to go back

##  Code Overview

* `FirstScreen`: Entry screen with navigation button
* `SecondScreen`: Displays message and back button
* Stateless widgets used for simplicity
* 
##  Future Improvements

* Add animations between screen transitions
* Use named routes for better navigation structure
* Pass data between screens
* Improve UI/UX design

##  Author

**Helly Leuva**

##  License

This project is open-source and available under the MIT License.
