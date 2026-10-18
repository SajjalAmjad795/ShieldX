# ShieldX — AI-Powered Cybersecurity Assistant

## 1. Project Overview
ShieldX is an Android application designed to identify potentially suspicious messages and URLs using machine learning and provide security alerts to users.

## 2. Project Objectives
- Detect potentially malicious or phishing messages and URLs.
- Notify users about suspicious content.
- Provide threat details, history and reports.
- Support secure user authentication.

## 3. Technologies
- Android Studio
- Java and XML
- Firebase Authentication
- Python and Google Colab
- TensorFlow Lite
- Room Database
- Git and GitHub

## 4. Main Application Screens
1. Splash Screen
2. Login Screen
3. Sign Up Screen
4. Forgot Password
5. Home Dashboard
6. Notification Monitoring
7. Threat Alert
8. Threat Details
9. Threat History
10. Reports
11. Settings
12. Help and Guide

## 5. Project Workflow and Timeline
| Phase | Timeline | Activities |
|---|---|---|
| Research and Dataset | Weeks 1–2 | Research phishing, scam and URL datasets |
| Preprocessing | Weeks 3–4 | Clean text and extract URL features |
| Model Training | Weeks 5–7 | Train, test and evaluate the model in Colab |
| Firebase Authentication | Weeks 6–7 | Login, Sign Up and password reset |
| TensorFlow Lite Conversion | Week 8 | Convert and validate the mobile model |
| Android Development | Weeks 8–11 | UI, notification listener and Room database |
| Integration | Weeks 11–12 | Integrate the ML model into Android |
| Testing and Final Demo | Weeks 13–14 | Test alerts, prepare report and final demonstration |

## 6. Detection Workflow
1. Receive an eligible notification with appropriate user permission.
2. Extract supported text or URL information.
3. Preprocess the input using the model's required format.
4. Analyze the input using the integrated TensorFlow Lite model.
5. Classify the result according to the model's supported categories.
6. Display an alert when appropriate.
7. Save relevant detection history locally, subject to user settings.

## 7. Development Tasks
- [ ] Collect and prepare datasets.
- [ ] Train and evaluate the ML model.
- [ ] Convert and validate the model for mobile use.
- [ ] Implement Firebase Authentication.
- [ ] Develop all required Android screens.
- [ ] Implement notification monitoring and permissions.
- [ ] Integrate Room database and threat history.
- [ ] Integrate ML predictions and threat alerts.
- [ ] Test the complete application.
- [ ] Prepare final documentation and demonstration.

## 8. Privacy and Security
Request only necessary permissions. Handle notification content carefully, protect user data, and avoid storing sensitive message content unnecessarily. Model predictions are estimates and should not be treated as guaranteed proof of malicious activity.

## 9. Project Status
In Development

## 10. Setup Instructions
1. Clone or download the repository.
2. Open the Android project in Android Studio.
3. Configure Firebase for the correct Android application.
4. Configure required SDKs and dependencies.
5. Add local configuration files securely.
6. Sync Gradle, then build and test the application.

## 11. Team and Contributions
Document team members, responsibilities and contributions here.
