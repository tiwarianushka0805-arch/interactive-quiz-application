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
| Open
