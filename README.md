# GeoTrack Attendance System

GeoTrack Attendance is a geofencing-based attendance system that uses location services to ensure users are within a predefined geographical area before allowing them to mark their attendance.

## Features
- **Geofencing:** Ensures attendance can only be marked within a specific geographical area.
- **User Authentication:** Secure login for users.
- **Attendance Tracking:** Real-time attendance marking and history.
- **Mobile-Friendly:** Built using Flutter for a seamless cross-platform experience.

## Technologies Used
- **Frontend:** Flutter
- **Backend:** Firebase (or specify your backend if different)
- **Database:** Firestore (or specify your database if different)
- **APIs:** Google Maps API for geofencing and location services

## Prerequisites
- Flutter SDK installed on your system
- A Google Maps API key
- A Firebase project set up with Firestore

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd GeoTrack-Attendance-main
   ```

3. Install Flutter dependencies:
   ```bash
   flutter pub get
   ```

4. Set up the Google Maps API key:
   - Obtain an API key from the [Google Cloud Console](https://console.cloud.google.com/).
   - Add the API key to the `android/app/src/main/AndroidManifest.xml` file and the `ios/Runner/AppDelegate.swift` file.

5. Set up Firebase:
   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Add the Firebase configuration files (`google-services.json` for Android and `GoogleService-Info.plist` for iOS) to the respective project directories.

6. Run the application:
   ```bash
   flutter run
   ```

## Usage
1. Log in using your credentials.
2. Ensure your device's location services are enabled.
3. Mark your attendance within the designated geofencing area.

## File Structure
```
GeoTrack-Attendance-main/
|-- lib/                # Flutter application code
|   |-- main.dart       # Entry point of the application
|   |-- screens/        # UI screens
|   |-- widgets/        # Reusable widgets
|   |-- services/       # Geofencing and Firebase integration
|-- pubspec.yaml        # Flutter dependencies
|-- android/            # Android-specific files
|-- ios/                # iOS-specific files
```

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Thanks to Google for the Maps API and Firebase.
- Inspired by innovative geofencing solutions.
