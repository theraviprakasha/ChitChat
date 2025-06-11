# ChitChat – Real-Time Android Chat Application

ChitChat is a Firebase-powered Android app that enables real-time one-on-one messaging with a clean UI and robust backend integration. Built in Android Studio using Java, it offers features like user authentication, chat history, user listing, FCM-based push notifications, and local preference management.

---

## Screenshots
![SignUp](https://github.com/user-attachments/assets/6d56bbc6-5a3a-4b26-a199-12c7272735a3)
![SignIn](https://github.com/user-attachments/assets/44295b1b-01bc-4b92-922b-1d2791d39640)
![Main](https://github.com/user-attachments/assets/af355de6-e926-4c8e-afde-c403858d7313)
![ChatActivity](https://github.com/user-attachments/assets/2619f981-254f-42af-af01-20c701c8a51c)
![AllUsers](https://github.com/user-attachments/assets/22c08096-2901-41b3-8758-9425d69b4458)



## 📱 Overview

ChitChat facilitates:
- 🔐 User sign-up, login, and authentication
- 💬 Real-time chat functionality using Firebase Firestore
- 🔔 Push notifications via Firebase Cloud Messaging (FCM)
- 🗂️ Recent conversation and user list with profile info
- 🎨 Material Design UI with modular components
- 🧠 Shared Preferences for session management

---

## 🚀 Technologies Used

- **Android SDK** (Java, XML, Gradle)
- **Firebase** (Authentication, Firestore, FCM)
- **AndroidX Libraries**
- **Glide / Base64** (for image handling)
- **RecyclerView, ViewHolder** (for UI lists)
- **SharedPreferences** (user session handling)

---

## 🔧 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/theraviprakasha/ChitChat-App-main.git
   cd ChitChat-App-main
   ```

2. **Open in Android Studio**
   - File → Open → Select the project folder

3. **Firebase Configuration**
   - Add `google-services.json` to the `/app` directory
   - Set up Firebase project with Authentication and Firestore enabled

4. **Build & Run**
   - Connect your Android device or start an emulator
   - Click ▶ (Run) in Android Studio

---

## 🧱 App Architecture

```
├── activities/               # UI logic (MainActivity, SignInActivity, etc.)
├── adapter/                 # RecyclerView adapters for chat & users
├── models/                 # Data models: User, ChatMessage
├── listeners/              # Callback interfaces
├── utilities/              # SharedPreferences, Constants
├── services/               # FirebaseMessagingService for notifications
├── res/layout/             # All XML layout files
├── AndroidManifest.xml     # App permissions and component registration
```

---

## 🔐 Key Features

### 🧍 User Management
- Registration & login with Firebase Auth
- Profile image handling via Base64
- Persistent login using SharedPreferences

### 💬 Chat System
- One-on-one messaging using Firestore
- Real-time updates via snapshot listeners
- Message timestamping and sorting

### 📥 Push Notifications
- FCM token management
- Notification delivery on new message
- MessagingService class handles tokens and alerts

### 🧭 Navigation & UX
- Splash screen with session check
- Home screen with recent conversations
- User list for new chat initiation
- Modern UI with ConstraintLayout & Material Design

---

## 📸 Screenshots

- Splash Screen  
- Sign In / Sign Up  
- User List  
- Chat Window  
- Recent Conversations

---

## 📚 Documentation

Refer to the academic documentation and source code for detailed architecture, functions, and app design principles.

### Abstract
> ChitChat App facilitates real-time messaging using Firebase and modular Android components. It demonstrates best practices in authentication, messaging, UI design, and cloud integration.

---

## 🔒 Requirements

### Minimum Hardware:
- Android device with API level 26+ (Android 8.0 Oreo)
- 2GB RAM, 1.6GHz CPU, 50MB storage

### Development Tools:
- Android Studio Arctic Fox or later
- Firebase Project (Auth + Firestore + FCM)
- JDK 8 or later
- Gradle 7.0+

---

## 🛠️ Further Improvements

- ✅ Typing indicators
- ✅ Group chats
- ✅ File/image sharing
- ✅ User presence & online status
- ✅ End-to-end encryption
- ✅ Search & filtering
- ✅ Profile customization

---

## 👥 Team & Acknowledgements

Developed by:
- **Raviprakasha (1CE20CS063)**
- **Naveen K V (1CE20CS054)**

Under the guidance of:
- **Mrs. Shashikala H. C**, Assistant Professor, Dept. of CSE, City Engineering College

With special thanks to:
- **Dr. Thippeswamy H N** (Principal)
- **Dr. Sowmya Naik** (HOD, CSE)
- Family, friends, and City Engineering College

---

## 📄 License

This project is for academic and demonstration purposes. For reuse or distribution, contact the developers.

