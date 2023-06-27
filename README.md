# TimeLine Share

This repository contains the code for an TimeLine Share built using Flutter. It aims to replicate the basic functionality and user interface of the popular social media platform TimeLine Share. 

## Features
- User authentication (login and registration)
- Feed displaying posts from followed users
- Upload and edit posts with captions and images
- Like and comment on posts
- Follow and unfollow users
- User profile with post count, followers, and following information
- Explore page with suggested users to follow
- Direct messaging between users

## Installation
1.  the repository: `git  https://github.com/IPH-Technologies-Pvt-Ltd/Timeline-Share-Flutter/TimeLine Share--flutter.git`
2. Change to the project directory: `cd TimeLine Share--flutter`
3. Install dependencies: `flutter pub get`
4. Run the app: `flutter run`

Note: Make sure you have Flutter and Dart installed and configured properly on your machine before running the app.

## Configuration
To configure the Firebase backend for authentication and database storage, follow these steps:

1. Create a new project on the [Firebase console](https://console.firebase.google.com/).
2. Add an Android app to your Firebase project and follow the setup steps to download the `google-services.json` file.
3. Add an iOS app to your Firebase project and follow the setup steps to download the `GoogleService-Info.plist` file.
4. Place the downloaded `google-services.json` file in the `android/app` directory of the project.
5. Place the downloaded `GoogleService-Info.plist` file in the `ios/Runner` directory of the project.
6. Enable Firebase Authentication using email and password in the Firebase console.
7. Enable Firebase Cloud Firestore database in the Firebase console.

## Contributing
Contributions are welcome! If you find any bugs or want to add new features, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
