# web_socket_chat

Chat WebSocket

A Flutter application for real-time messaging using WebSocket.

Setup Instructions

Prerequisites
Install Flutter SDK: Version ^3.5.3
Ensure Dart is included in your Flutter SDK.
Install a code editor like Android Studio or Visual Studio Code.

Steps to Run
Clone the Repository

Copy code
git clone <repository-url>  
cd chat_web_socket  
Install Dependencies
Run the following command to fetch all the required dependencies:


Copy code
flutter pub get  
Run the App
Launch the application on a connected device or emulator:


Copy code
flutter run  
Code Generation (if needed)
For features like auto_route, run the following command after any updates to routing configurations:


Copy code
flutter pub run build_runner build --delete-conflicting-outputs  

Assumptions and Limitations

Assumptions
The backend WebSocket server is properly configured and reachable at the specified URL.
The application is designed to work on Android and iOS platforms.

Limitations
Backend Dependency: The app won't function properly without a running backend server.
WebSocket Compatibility: Ensure the WebSocket server adheres to standard protocols for compatibility with web_socket_channel.
UI Adaptation: Currently optimized for modern smartphones; tablets may require UI adjustments.

Features
Establish WebSocket connections for real-time messaging.
Send and receive messages with state management powered by BloC.
Navigation management using AutoRoute.
Dependency injection via GetIt for better scalability and testability.
Libraries Used
web_socket_channel - WebSocket communication
flutter_bloc - State management
auto_route - Navigation
get_it - Dependency injection
cupertino_icons - iOS icons

Notes
For any issues or questions, feel free to raise a ticket in the repository.
Always ensure you are using the latest versions of the dependencies listed in pubspec.yaml.
