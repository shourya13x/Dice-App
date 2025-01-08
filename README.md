# **Dicee Flutter App**

## **Project Description**

The **Dicee** app is a beginner-friendly Flutter project that simulates rolling dice. This app demonstrates the use of `StatefulWidget`, random number generation, and Flutter’s widget system to create a fun and interactive user experience.

---

## **Features**

- **Two Dice Simulation**: Two dice are displayed on the screen.
- **Random Dice Rolls**: Tapping on either dice generates a random number between 1 and 6 for both dice.
- **Interactive Design**: Uses Flutter’s `setState()` to dynamically update the UI when dice are rolled.
- **Dynamic Image Updates**: Dice faces update based on the rolled numbers.

---

## **Project Structure**

- **`main.dart`**: Contains the app’s core logic, including UI layout and random dice face generation.
- **Images Folder**: Stores dice face images (`dice1.png` to `dice6.png`). These images are used to represent the dice rolls visually.

Ensure that the images are placed in the `assets/images` directory, and the `pubspec.yaml` file is updated accordingly:

```yaml
flutter:
  assets:
    - images/dice1.png
    - images/dice2.png
    - images/dice3.png
    - images/dice4.png
    - images/dice5.png
    - images/dice6.png

How It Works
	1.	Initial State: The app starts with two dice showing the number 1.
	2.	Rolling the Dice: When the user taps on either dice, the changeDiceFace() function generates random numbers between 1 and 6 for both dice.
	3.	Dynamic UI Update: The dice images update to reflect the new random numbers, providing a seamless and interactive experience.

Requirements
	•	Flutter SDK: Install and set up Flutter on your system.
	•	Assets Setup: Ensure dice images (dice1.png to dice6.png) are present in the assets/images folder and properly configured in pubspec.yaml.

How to Run
	1.	Clone the repository or copy the project files.
	2.	Add dice face images (dice1.png to dice6.png) to the assets/images directory.
	3.	Open the project in your preferred Flutter IDE (e.g., Android Studio or VS Code).
	4.	Run the following commands in your terminal:

flutter pub get
flutter run

	5.	The app will launch on your connected device or emulator.

Future Enhancements
	•	Add a rolling animation for the dice to improve user experience.
	•	Display the total of the two dice rolls.
	•	Add sound effects for a more engaging app.

License

This project is licensed under the MIT License. You are free to use, modify, and distribute it as you see fit.

