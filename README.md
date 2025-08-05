# 🗨️ Prattle - Android Chat App

**Prattle** is a minimalist, cactus-themed Android chat application built using **Java** and **Firebase**. It offers real-time chatting, story sharing, user profiles, and authentication—all within a clean and friendly UI.

---

## 📲 Features

- 🔐 **Email/Password Authentication** via Firebase
- 🧑 **Profile Management** with image, status & contact
- 💬 **1-to-1 Messaging** with clean bubble UI
- 📖 **Stories Section** (status-like updates)
- 👥 **User Contact List** with email IDs
- 🎨 **Cactus-themed Aesthetic** for a modern and simple look

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Java | Android app development |
| XML | UI Design |
| Firebase Authentication | User login/signup |
| Firebase Realtime Database | Chat data |
| Firebase Storage | Profile/Story images |
| Glide | Image loading and caching |

---

## 📸 App Screenshots

### 🔐 Sign In & Sign Up
<p float="left">
  <img src="Prattle files/screenshots/Sign-in-page.jpg" width="200"/> 
  <img src="Prattle files/screenshots/Sign-up-page.jpg" width="200"/>
</p>

### 🏠 Home (Chat List)
<img src="Prattle files/screenshots/Home-page.jpg" width="200"/>

### 💬 Chat Interface
<img src="Prattle files/screenshots/Chatting-Interface.jpg" width="200"/>

### 📖 Stories Section
<img src="Prattle files/screenshots/Stories-page.jpg" width="200"/>

### 👤 Profile Page
<img src="Prattle files/screenshots/Profile-page.jpg" width="200"/>

---

## 🚀 How to Run

### Prerequisites

- Android Studio (latest recommended)
- Firebase project set up with:
  - Authentication (Email/Password)
  - Realtime Database
  - Firebase Storage
- Internet connection

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/prattle.git
   cd prattle

2. 📝 Note: Replace values with your actual `google-services.json` by downloading it from Firebase Console and placing it in the `/app` directory.

✅ **Firebase Realtime Database Rules (for testing):**

```json
{
  "rules": {
    ".read": "true",
    ".write": "true"
  }
}
```

✅ Firebase Storage Rules (for development)
```
service firebase.storage {
  match /b/{bucket}/o {
    match /{allPaths=**} {
      allow read, write;
    }
  }
}
```

✅ Structure of google-services.json 
```json

{
  "project_info": {
    "project_id": "your-firebase-project-id",
    "project_number": "1234567890",
    "name": "Prattle"
  },
  "client": [
    {
      "client_info": {
        "mobilesdk_app_id": "1:1234567890:android:abcdef123456",
        "android_client_info": {
          "package_name": "com.yourcompany.prattle"
        }
      }
    }
  ]
}
```


👨‍💻 Developer

Name: Arpan Khare

📧 Email: kharearpan7777@gmail.com

📞 Phone: +91 6306462328

