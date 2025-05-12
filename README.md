![Kotlin Instagram App](https://tse4.mm.bing.net/th?id=OIP.UwbdM7xzqwonhmOFjn9cQQHaPK&pid=Api)

# KotlinInstagramApp

**KotlinInstagramApp** is an Android application developed using Kotlin, designed to replicate core functionalities of Instagram. This project serves as a practical example for developers interested in building social media applications with modern Android development practices.

## 📱 Features

- **User Authentication**: Secure login and registration system.
- **Photo Upload**: Users can upload images to their profiles.
- **Feed Display**: View a feed of uploaded photos.
- **Profile Management**: Users can view and edit their profiles.
- **Like and Comment**: Interact with posts through likes and comments.

## 🛠️ Technologies Used

- **Kotlin**: Primary programming language.
- **Android Jetpack Components**: Including LiveData, ViewModel, and Navigation.
- **Firebase**: For authentication, real-time database, and storage.
- **Glide**: Image loading and caching library.
- **Material Design**: UI components and design principles.

## 🚀 Getting Started

### Prerequisites

- Android Studio Bumblebee or later.
- Android SDK 31 or higher.
- A Firebase project with Authentication and Realtime Database enabled.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AidenLM/KotlinInstagramApp.git
   cd KotlinInstagramApp
   ```

2. **Open in Android Studio**:
   - Launch Android Studio.
   - Click on "Open an existing project".
   - Navigate to the cloned repository folder.

3. **Configure Firebase**:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Enable Email/Password Authentication.
   - Enable Realtime Database and set the rules as needed.
   - Download the `google-services.json` file and place it in the `app/` directory.

4. **Build the project**:
   - Click on "Build" > "Make Project" or press `Ctrl+F9`.

5. **Run the application**:
   - Connect an Android device or start an emulator.
   - Click on "Run" > "Run 'app'" or press `Shift+F10`.

## 📂 Project Structure

```
KotlinInstagramApp/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/kotlininstagramapp/
│   │   │   │   ├── activities/
│   │   │   │   ├── adapters/
│   │   │   │   ├── fragments/
│   │   │   │   ├── models/
│   │   │   │   └── utils/
│   │   │   └── res/
│   │   │       ├── layout/
│   │   │       ├── drawable/
│   │   │       └── values/
│   └── build.gradle
├── build.gradle
└── settings.gradle
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Commit your changes**:
   ```bash
   git commit -m 'Add YourFeature'
   ```
4. **Push to the branch**:
   ```bash
   git push origin feature/YourFeature
   ```
5. **Open a Pull Request**.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
