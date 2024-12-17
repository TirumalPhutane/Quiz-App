# Quiz App - Flutter  

A simple and interactive Quiz App built using **Flutter**. This app allows users to answer quiz questions, view their results, and see the correct answers for questions they got wrong.

---

## Features  

- **Home Page to Start Quiz**  
  - The app welcomes users with a clean initial screen to begin the quiz.  

- **Multiple Quiz Questions**  
  - Users can attempt a set of quiz questions one by one.  

- **Results Page**  
  - After answering all questions, users are shown:  
    - **Correct answers**: Questions answered correctly.  
    - **Wrong answers**: Questions answered incorrectly.  
    - **Correct answers for wrong questions**: Helps users learn and improve.

- **User-Friendly Interface**  
  - Smooth navigation with an intuitive UI built using Flutter.  

- **Cross-Platform Support**  
  - Works seamlessly on both Android and iOS devices.  

---

## Tech Stack  

- **Framework**: Flutter  
- **Language**: Dart  

---

## Screenshots

## Project Structure
```
lib/
├── main.dart                  # Entry point of the app
├── quiz.dart.dart             # Quiz question display logic
├── questions_screen.dart      
├── results_screen.dart        # Displays results and correct answers
├── start_screen.dart          # Initial page to start the quiz
├── summary.dart               
├── summary_item.dart          # Custom Widget
├── answer_button.dart         # Custom Widget
├── question_identifier.dart   
├── data/
│   └── questions.dart  # List of Questions
└── models/
    └── quiz_question.dart   # Question model class
```


## Future Improvements
- Add a timer for each question.
- Integrate categories and difficulty levels for questions.
- Include a scoring system.
- Fetch quiz questions dynamically using an API.

## Author
Tirumal Phutane

- LinkedIn: [Tirumal Phutane](https://www.linkedin.com/in/tirumal-phutane-09543915a/)