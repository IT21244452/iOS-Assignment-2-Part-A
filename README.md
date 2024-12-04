# iOS-Assignment-2-Part-A

# Voice-Controlled AR Robot App

## Introduction
The *Voice-Controlled AR Robot App* is an augmented reality (AR) application developed for iOS using RealityKit, ARKit, and Swift. The app allows users to control a virtual robot using voice commands such as "forward," "back," "left," and "right." By leveraging AR capabilities, the app enables users to interact with 3D models in a real-world environment, creating an immersive experience.

---

## Features
- *Augmented Reality (AR):* Detects horizontal planes in the real world and allows placing a 3D robot model on them.
- *Voice Control:* Uses speech recognition to interpret user commands and move the robot accordingly.
- *3D Animations:* Animates the robot's movements, such as walking forward, turning, and more.
- *Interactive User Interface:* Provides a splash screen and intuitive interactions for users to engage with the AR environment.

---

## User Guide

### Prerequisites
- iPhone with ARKit support (e.g., iPhone 6s or later running iOS 11 or above).
- Xcode 15.2 or later installed on a macOS system.

### Installation
1. Clone the repository:
   bash
   git clone <repository-url>
   
2. Open the project in Xcode:
   bash
   open VoiceControlledARRobot.xcodeproj
   
3. Connect an iPhone and select it as the target device in Xcode.
4. Build and run the app using the *Run* button (▶️).

### Usage
1. Move your device to detect horizontal surfaces.
2. Tap on a detected surface to place the robot.
3. Use voice commands such as:
   - *"forward"*: Move the robot forward.
   - *"back"*: Move the robot backward.
   - *"left"*: Rotate the robot to the left.
   - *"right"*: Rotate the robot to the right.

---

## Technical Documentation

### Tools & Frameworks
- *Xcode 15.2*: Development environment.
- *RealityKit*: Handles 3D rendering and interactions.
- *ARKit*: Manages augmented reality plane detection and tracking.
- *Speech Framework*: Enables speech recognition for voice commands.

### File Structure
- ContentView.swift: Entry point of the app. Manages splash screen and AR view navigation.
- ARViewController.swift: Handles AR session configuration, plane detection, and object placement.
- SpeechRecognizer.swift: Implements speech recognition to capture and process voice commands.
- RobotModel.usdz: 3D model of the robot.
- Animations.usdz: Animation assets for the robot's movements.

### Architecture
The app follows a modular structure:
- *AR Module*: Manages AR scene and interactions.
- *Speech Module*: Processes voice inputs and translates them into commands.
- *UI Module*: Handles navigation and user interface elements.

---

## Development Process

### Design Decisions
- *RealityKit vs SceneKit*: RealityKit was chosen for its modern approach to AR development and its seamless integration with ARKit.
- *SwiftUI*: SwiftUI provided a declarative syntax for building the user interface, making it easier to integrate the ARView.
- *Voice Control*: Adding voice control with the Speech framework enhanced user interaction.

### Challenges
- *Speech Recognition Accuracy*: Ensuring the app correctly interprets voice commands required testing with different accents and speech patterns.
- *AR Plane Detection*: Handling edge cases where plane detection failed or was inconsistent.
- *3D Model Integration*: Loading .usdz models and ensuring smooth animations within the AR environment.

### Testing Results
- *Device Compatibility*: Successfully tested on iPhone 12 and later models.
- *Speech Commands*: Achieved 95% accuracy for common commands (e.g., "forward," "back").
- *AR Interaction*: Objects were placed accurately on detected planes with minimal drift.

### Reflections
This project highlighted the importance of combining user-friendly interfaces with robust AR and voice technologies. The modular design ensured ease of development and testing.

---

## Future Enhancements
- Add voice feedback to confirm robot actions.
- Enable dynamic scaling of 3D models.
- Introduce additional animations and behaviors for the robot.
- Improve AR plane detection with advanced algorithms.

---

## Conclusion
The *Voice-Controlled AR Robot App* demonstrates the power of combining augmented reality with voice interaction. It provides an engaging and intuitive experience for users to interact with 3D models in real-world environments. This project serves as a foundation for future AR applications with voice-controlled features.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
For inquiries or contributions, please contact:
- *Email*: [umayanganawijayasiri@gmail.com.com]
- *GitHub*: [GitHub Profile]([https://github.com/IT21244452])
