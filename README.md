# EduLearn - Group Project

An educational website for learning HTML, CSS and JavaScript.

## How to run
Unzip the folder and double-click `index.html` to open it in any browser. No installation needed.

## Files
- `index.html` - Home: logo, navigation, welcome message, search bar, course cards, Start Learning button
- `courses.html` - Courses: all courses with descriptions, Open Course buttons, topic filters and search
- `tutorial.html` - Tutorials: HTML, CSS and JavaScript basics, code snippets, Copy buttons, Mark as Completed
- `quiz.html` - Quiz: multiple-choice questions per topic, automatic scoring, correct answers and feedback
- `about.html` - About & Progress: purpose, team, completed lessons, quiz results, Reset Progress
- `css/style.css` - all styling (shared by every page, responsive for phones)
- `js/script.js` - all interactivity; course, lesson and quiz data live at the top of this file

## How progress is saved
Progress is stored in the browser with `localStorage` under the key `edulearnProgress`.
It stays after closing the browser and is cleared by the Reset Progress button.

## Customising
- Add a course: add an object to the `COURSES` array in `js/script.js`.
- Add a quiz question: add an object to `QUIZZES.html`, `QUIZZES.css` or `QUIZZES.javascript`.
- Add a lesson: add an `<article class="lesson" id="...">` in `tutorial.html` and the same id to `LESSONS`.
- Put your group members' names in the Team panel of `about.html`.
