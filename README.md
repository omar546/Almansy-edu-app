
# Almansy Edu Platform
<img width="203" height="162" alt="logo" src="https://github.com/user-attachments/assets/2b027de8-1599-472f-8208-f45d7c06587e" />

The app allows students to view courses, access educational resources, and interact with teacher-provided materials.

---

## 📱 Features
- User authentication (login & register)
- Course browsing and viewing
- Embedded video lessons (YouTube integration)
- Resource management (PDFs, files, etc.)
- Profile management

---

## 🏗️ Architecture

The project follows **Clean Architecture** principles with a **feature-based structure** and **Cubit (via Flutter Bloc)** for state management.

- **Domain Layer** → Business logic & use cases
- **Data Layer** → Repositories, models, and data sources
- **Presentation Layer** → UI widgets, pages, and Cubit state management
- **Feature-based organization** → Each feature (e.g., `auth`, `courses`) has its own `data`, `domain`, and `presentation` subfolders

---

## 📂 Project Structure
```bash
lib/
 └── features/
     └── auth/
         └── presentation/
             └── pages/
                 └── register_screen.dart

assets/
 ├── icons & svgs
 ├── logos
 └── temp (sample images)

android/
 ├── app/
 │   ├── src/
 │   │   └── main/
 │   │       ├── kotlin/com/example/mansy/MainActivity.kt
 │   │       ├── res/ (drawables, mipmaps, styles)
 │   │       └── AndroidManifest.xml
 │   └── build.gradle.kts
 └── settings.gradle.kts
````

## 📦 Dependencies

| Package                  | Purpose                                   |
| ------------------------ | ----------------------------------------- |
| `flutter_bloc`           | Cubit/Bloc state management               |
| `get_it`                 | Service locator / dependency injection    |
| `dio`                    | HTTP client for APIs                      |
| `equatable`              | Simplifies equality comparisons in models |
| `flutter_secure_storage` | Secure key/value storage                  |
| `url_launcher`           | Open links, phone, email, etc.            |
| `flutter_svg`            | SVG asset rendering                       |
| `google_fonts`           | Custom fonts with Google Fonts            |
| `youtube_player_flutter` | Embed YouTube videos                      |
| `webview_flutter`        | WebView integration                       |
| `flutter_pdfview`        | PDF viewing                               |
| `path_provider`          | Access local filesystem paths             |
| `http`                   | Lightweight HTTP requests                 |


 
## 🖼️ Screenshots
<h3 align="center">Guest</h3>
<img width="1080" height="1080" alt="Guest" src="https://github.com/user-attachments/assets/6e9a8cbc-f5cd-45d9-b66e-25327eca996b" />

<h3 align="center">Auth</h3>

<img width="1080" height="1080" alt="auth" src="https://github.com/user-attachments/assets/6b429bf5-3eb2-43af-b692-b41bdb48b846" />

<h3 align="center">Home</h3>

<img width="1080" height="1080" alt="home" src="https://github.com/user-attachments/assets/03f23a82-63bd-404d-873d-485cf49397e7" />

<h3 align="center">Profile</h3>

<img width="1080" height="1080" alt="Profile" src="https://github.com/user-attachments/assets/d8951b51-2e10-40ca-9a37-62aaa179d6ae" />

<h3 align="center">Course content</h3>

<img width="1080" height="1080" alt="course content" src="https://github.com/user-attachments/assets/469aad81-c590-4fbb-ade0-81da6db81a5d" />
##🏢 Acknowledgments

Developed for N.I.T as part of an educational solution for Teacher Almansy.

## Demo

https://github.com/user-attachments/assets/1bf7d259-b0f7-4715-9fb7-85de326f3bef



