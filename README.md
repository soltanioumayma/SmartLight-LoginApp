# SmartLight-LoginApp

A simple Android application that simulates a login flow for a Smart Light Controller system. Built with Java and Android Studio, the app demonstrates basic UI handling, input validation, and activity navigation.

## Features

- Simple and clean login screen with username and password fields
- Input validation (checks for empty fields)
- Navigation from Login screen to Dashboard screen
- Dashboard placeholder screen ready for future smart light control features

##  Built With

- **Java** – Core application logic
- **Android SDK** – UI components and activity management
- **AppCompatActivity** – Backward-compatible activity base class
- **LinearLayout** – XML-based UI layouts

  ##  Project Structure
app/

├── src/main/java/com/example/exercice1/

│   ├── MainActivity.java          

│   └── activity_dashbord.java     

├── src/main/res/layout/

│   ├── activity_main.xml          

│   └── activity_dashbord.xml     

##  Getting Started

### Prerequisites

- Android Studio (latest version recommended)
- Android SDK installed
- A connected device or emulator

### Installation

1. Clone the repository:
```bash
   git clone https://github.com/soltanioumayma/SmartLight-LoginApp.git
```
2. Open the project in **Android Studio**.
3. Let Gradle sync and build the project.
4. Run the app on an emulator or physical device.

##  How It Works

1. The user enters a **username** and **password** on the login screen.
2. If either field is empty, a **Toast message** prompts the user to fill them in.
3. If both fields are filled, the app navigates to the **Dashboard** screen.
4. The Login activity is finished (`finish()`) so the user can't navigate back to it.


