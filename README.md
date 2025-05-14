# Calculator-App
Flutter Calculator App:
A simple and elegant calculator application built using Flutter. This app allows users to perform basic arithmetic operations with a responsive and interactive UI, following a standard calculator layout.

📱 Features:
🧠 Basic arithmetic operations: Addition, Subtraction, Multiplication, Division
🔢 Supports decimal inputs and percentage calculation
🎨 Clean and minimal user interface
🚀 Fast and responsive performance
🧩 Uses math_expressions package for expression parsing and evaluation

🔧 Tech Stack:
Flutter: Frontend framework for building the UI
Dart: Programming language used with Flutter
math_expressions: For parsing and evaluating math expressions

🧩 Project Structure
lib/
├── Components/
│   └── my_button.dart       # Custom reusable button widget
├── main.dart                # Entry point
└── HomeScreen.dart          # Calculator UI and logic

💡 How It Works
The calculator interface is built using a column of rows of custom MyButton widgets.
User input is collected in a string, and pressing = triggers parsing via the math_expressions library.
Operators like x are internally converted to * before evaluation.
The result is shown dynamically below the input field.

🙌 Contributing
Contributions are welcome! If you'd like to improve the app or fix any issues:
Fork the repo
Create your feature branch (git checkout -b feature/your-feature)
Commit your changes (git commit -m 'Add new feature')
Push to the branch (git push origin feature/your-feature)
Open a Pull Request



