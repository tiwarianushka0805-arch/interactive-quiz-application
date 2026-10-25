# Project Audit Report — Interactive Quiz Application

## 1. Project Overview

**Project Name:** Interactive Quiz Application  
**Purpose:** To build an interactive multiple-choice quiz that tests basic programming and software development knowledge.  
**Technologies:** HTML5, CSS3, JavaScript  
**Project Type:** Front-End Web Application

## 2. Project Structure

| File | Purpose |
|---|---|
| `index.html` | Defines the structure and elements of the quiz. |
| `style.css` | Provides the layout, colours, spacing, and visual styling. |
| `script.js` | Manages questions, answer selection, score calculation, and quiz completion. |
| `README.md` | Documents the project, features, technologies, and usage instructions. |

## 3. Functional Requirements Audit

| Requirement | Expected Result | Status |
|---|---|---|
| Display quiz title | Shows the application heading. | Passed |
| Display questions | Shows one question at a time. | Passed |
| Display answer options | Provides four options for each question. | Passed |
| Check selected answers | Compares the selected option with the correct answer. | Passed |
| Prevent multiple answers | Accepts only one answer per question. | Passed |
| Calculate score | Increases the score for each correct answer. | Passed |
| Display final result | Shows the final score out of five. | Passed |

## 4. User Interface Audit

- Uses a blue, white, and gold colour scheme.
- Displays questions and answer options clearly.
- Provides hover and focus styling for answer buttons.
- Uses spacing, borders, and rounded corners to improve readability.
- Includes a layout designed to fit different screen widths.

## 5. Code Quality Audit

- HTML elements use IDs to connect the webpage with JavaScript.
- CSS is maintained in a separate stylesheet.
- JavaScript uses an array of objects to store quiz questions and answers.
- Functions are used to display questions and check answers.
- The `answered` variable prevents multiple selections from being counted for the same question.

## 6. Testing Report

| Test Case | Expected Outcome | Result |
|---|---|---|
| Open the application | Quiz interface loads correctly. | Passed |
| Select a correct answer | Score increases by one. | Passed |
| Select an incorrect answer | Score does not increase. | Passed |
| Click multiple options for one question | Only the first selection is counted. | Passed |
| Complete all five questions | Quiz completion message and final score appear. | Passed |

## 7. Issues and Limitations

- The quiz contains five predefined questions.
- Questions cannot currently be added through the user interface.
- The quiz does not yet provide a restart button.
- The score is displayed at the end; immediate feedback for each answer is not implemented.

## 8. Repository and Deployment Audit

- [ ] `index.html` uploaded to GitHub.
- [ ] `style.css` uploaded to GitHub.
- [ ] `script.js` uploaded to GitHub.
- [ ] `README.md` added and reviewed.
- [ ] `audit.md` added to the repository.
- [ ] GitHub Pages deployment completed.
- [ ] Live application URL tested successfully.

## 9. Final Conclusion

The Interactive Quiz Application demonstrates the practical use of HTML, CSS, and JavaScript to develop a functional web application. It implements multiple-choice questions, answer validation, score tracking, and a final result display. The project was tested in a web browser, and the main quiz functionality worked as expected. Repository upload and deployment should be verified separately before the project is marked fully complete.
