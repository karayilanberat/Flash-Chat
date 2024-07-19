# Flash-Chat

## Screenshots



## Overview

Flash Chat is an internet-based messaging app similar to WhatsApp. This app uses Firebase Firestore as a backend database to store and retrieve messages in real-time. It’s designed to help you understand the fundamentals of Table Views, custom cells, and cloud-based backend integration in iOS development.

## Features

### Real-Time Messaging

- **Cloud Storage:** Store and retrieve messages using Firebase Firestore.
- **Live Updates:** Messages update in real-time with listeners for new data.
- **Message Ordering:** Messages are ordered by timestamp to show the most recent first.

### User Authentication

- **Registration:** Users can create new accounts with email and password.
- **Login:** Users can log in to their accounts with email and password.
- **Session Management:** Automatically manage user sessions and sign out.

### Custom UITableView Cells

- **MessageCell:** Custom UITableViewCell to display messages.
- **Dynamic Layout:** Messages are shown with dynamic layout adjustments for sender and receiver.
- **Custom Views:** Use of .xib files for custom view designs.

### User Interface

- **Welcome Screen:** Animated text display on the welcome screen.
- **Chat Interface:** User-friendly chat interface with message bubbles and user images.
- **Navigation:** Integration of Navigation Controllers for smooth transitions between screens.

## Learning Goals

- **Third-Party Libraries:** Integrate third-party libraries using CocoaPods and Swift Package Manager.
- **Cloud Storage:** Store and retrieve data in the cloud using Firebase Firestore.
- **User Authentication:** Implement user authentication, registration, and login with Firebase.
- **UITableViews:** Work with UITableViews, setting data sources and delegates.
- **UI Development:** Create and customize views using .xib files and UIKit components.

## What I Learned

- **Firebase Integration:** Implemented Firebase Firestore for data storage and retrieval.
- **Authentication Flow:** Managed user authentication and session handling with Firebase.
- **Custom UITableViewCells:** Designed and implemented custom UITableViewCells for messaging.
- **UI/UX:** Enhanced user experience with animated text and user-friendly interface.

## Usage

1. **Run the App:**
   - Register or log in with your email and password.
   - Start chatting by sending and receiving messages in real-time.

## Code Overview

### Models

- **Message.swift:** Defines the structure of a message with sender and body properties.

### View Controllers

- **WelcomeViewController.swift:** Displays the welcome screen with animated app name.
- **RegisterViewController.swift:** Handles user registration.
- **LoginViewController.swift:** Manages user login.
- **ChatViewController.swift:** Handles the main chat interface, message sending, and receiving.

### Views

- **MessageCell.swift:** Custom UITableViewCell for displaying messages.

## Running the Project

To run this project, follow these steps:
```bash
git clone https://github.com/yourusername/flash-chat.git
cd flash-chat
pod install
open Flash-Chat.xcworkspace
