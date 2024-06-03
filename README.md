# Chatter

Chatter is a real-time chat application built using Flutter and Firebase. It supports features such as user authentication, real-time messaging, image sharing, and more. This app leverages Firebase for backend services, including authentication, database, and storage.

## Features

- **User Authentication**: Sign up and login functionalities.
- **Real-Time Messaging**: Send and receive messages in real time.
- **Image Sharing**: Share images in the chat.
- **Profile Management**: Manage user profiles.
- **Push Notifications**: Get notified of new messages (if implemented).

## Screenshots

![Login Screen](screenshots/login.png)
![Home Screen](screenshots/home.png)
![Chat Screen](screenshots/chat.png)

## Technologies Used

- **Flutter**: Frontend framework for building cross-platform mobile applications.
- **Firebase**: Backend-as-a-Service for authentication, real-time database, and storage.
- **GetIt**: Service locator for dependency injection.
- **Google Fonts**: Custom fonts for UI enhancement.

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Firebase Project: [Create a Firebase project](https://console.firebase.google.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/chatter.git
   cd chatter
   ```

2. Set up Firebase:

   - Follow the instructions to add your app to Firebase and download the `google-services.json` file.
   - Place `google-services.json` in the `android/app` directory.

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## Project Structure
