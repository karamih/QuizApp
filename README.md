# Quiz Game

local data quiz game.

***

## UI

* Home Page

<img src="ui_images/home.png" alt="home-page" width="200" height="400"/>

* Me

<img src="ui_images/info.png" alt="info" width="200" height="400"/>

* Quiz Page

<img src="ui_images/quiz.png" alt="quiz-page" width="200" height="400"/>

* Quiz Info

<img src="ui_images/quiz_info.png" alt="quiz_info-page" width="200" height="400"/>

* Win Page

<img src="ui_images/win.png" alt="win-page" width="200" height="400"/>

* Lose Page

<img src="ui_images/Lose.png" alt="lose-page" width="200" height="400"/>

***

to add new questions, should modify:

```text
Path: quiz_game/lib/quiz.dart
```

    Code: void fetchData() {
    questions = [
      {
        "question": "What is Undo shortcut in computer?",
        "options": ["ctl+y", "ctl+z", "ctl+s", "ctl+p"],
        "answer": 1
      },
      {
        "question": "What is Redo shortcut in computer?",
        "options": ["ctl+y", "ctl+z", "ctl+s", "ctl+p"],
        "answer": 0
      },
      {
        "question": "which is not a program language?",
        "options": ["python", "dart", "html", "typescript"],
        "answer": 2
      },
      {
        "question": "flutter's programming language?",
        "options": ["python", "dart", "swift", "java"],
        "answer": 1
      },
      {
        "question": "backend python framework?",
        "options": ["flask", "fast api", "django", "all"],
        "answer": 3
      }
    ];

