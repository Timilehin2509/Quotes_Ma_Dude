
# Quotes Ma Dude

Welcome to the Quotes Ma Dude project! This app provides uplifting or mood-complementing quotes based on the user's selected emoji. Below are the steps and tasks to be carried out by each sub-team, including directory structures and file paths.

## Overview

**Quotes Ma Dude** is an Android app that:

- Prompts users to select an emoji representing their current mood.
- Displays a related quote with a subtle animation.
- Allows users to copy the quote or select a different emoji for another quote.

## Core Functionalities

- **Emoji (Mood) Selection:** Users select an emoji based on their current mood.
- **Animation:** Show a subtle animation when an emoji is clicked.
- **Quote Display:** Display a related quote when an emoji is selected.
- **Copy Quote:** Option to copy the displayed quote.
- **Repeat Functionality:** Allow users to select the same or a different emoji to get another quote.

## Technical Requirements

- **IDE:** Android Studio with Kotlin (IntelliJ can be used for initial development, but final development and testing should be done in Android Studio).
- **UI Components:** XML
- **Built-In Animation Library:** Use Android's built-in animation tools.
- **Built-In Clipboard Manager:** Use Android's clipboard manager for the copy functionality.
- **Data Storage:** JSON file for storing quotes.
- **Version Control:** Git and GitHub
- **Deployment:** Firebase

## Project Setup

### 1. Setup and Configuration

- **Set up a new project on Android Studio:** Initialize the project and configure it for Kotlin development.
- **Create GitHub repository:** Ensure that the project is linked to the GitHub repository created earlier.

### 2. Layout Design

- **Design Layout with XML:** Create the user interface using XML. Ensure that the UI is user-friendly and aesthetically pleasing.

### 3. Data Gathering and Setup

- **Quotes JSON File:** Use the provided quotes in the JSON format. Place the `quotes.json` file in the `assets` directory.

```json
{
  "angry": ["Anger is only one letter short of danger.", "Don't let anger control you, let wisdom guide you.", "Holding on to anger is like drinking poison and expecting the other person to die."],
  "sad": ["It's okay to not be okay. You're not alone.", "Sadness is like rain, it nourishes the soul.", "Sometimes, the heaviest crown is the one you give yourself."],
  "in_love": ["Love is the only force capable of transforming an enemy into a friend.", "To love is to risk not being loved in return.", "The greatest happiness of life is to love and be loved."],
  "confused": ["Confusion is just another word for growth.", "It's okay to be lost, as long as you're looking for the right path.", "The only way out is through."],
  "tired": ["Tired is the body, but determined is the soul.", "Rest is not idleness, and to lie sometimes on the grass under trees on a sunny day is not laziness.", "You don't have to do everything at once. Take breaks."],
  "happy": ["Happiness is not something ready-made. It comes from your own actions.", "The only way to do great work is to love what you do.", "Gratitude turns what we have into enough."]
}
```

### 4. Programming

- **Class for Reading Quotes:** Implement a Kotlin class to handle reading from the `quotes.json` file.
- **Main App Logic:** Write the main program logic for handling user interactions and displaying quotes.
- **Click Listeners:** Set up click listeners for each emoji to fetch and display quotes.
- **Animations:** Implement animations for emoji selection.
- **Copy Functionality:** Implement the ability to copy quotes to the clipboard.

### 5. Quality Assurance and Testing

- **Testing:** Conduct thorough testing to ensure the app functions as expected.
- **Bug Fixing:** Identify and fix any bugs or issues.

### 6. Deployment

- **Firebase Setup:** Configure Firebase for the project.
- **Build APK:** Build the APK using Android Studio.
- **Distribute via Firebase App Distribution:** Share the APK with testers and stakeholders.

## Directory Structure

### IntelliJ IDEA / Android Studio

When working in IntelliJ IDEA or Android Studio, the project directory includes:

```plaintext
Quotes_Ma_Dude/
├── .idea/                        # Project settings
│   ├── codeStyles/
│   │   └── codeStyleConfig.xml
│   ├── inspectionProfiles/
│   │   └── Project_Default.xml
│   ├── libraries/
│   │   ├── KotlinJavaRuntime.xml
│   │   ├── kotlin.xml
│   │   └── kotlinc.xml
│   ├── misc.xml
│   ├── modules.xml
│   ├── vcs.xml
│   └── workspace.xml
├── out/
│   └── production/
│       └── Quotes_Ma_Dude/
│           ├── META-INF/
│           │   └── Quotes_Ma_Dude.kotlin_module
│           └── MainKt.class
├── src/
│   └── Main.kt
├── assets/                       # Assets (e.g., quotes.json)
│   └── quotes.json
├── res/                          # Resources
│   ├── layout/                   # XML layout files
│   │   └── activity_main.xml
│   ├── drawable/                 # Drawable resources
│   │   └── emoji_icons.xml
├── .gitignore
├── Quotes_Ma_Dude.iml
└── External Libraries/
    └── KotlinJavaRuntime
```

## Contributions

Please ensure to:

- **Follow Code Standards:** Adhere to Kotlin and Android coding standards.
- **Use Descriptive Commit Messages:** For clarity and tracking.
- **Manage Branches:** Use branches for feature development and bug fixes.

## Contact

For any questions or issues, please contact Ajayi Anjolaoluwa at [Email Address].
