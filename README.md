# Student Marks Calculator

A simple, responsive web-based calculator that helps students calculate their internal marks, external exam contribution, final marks, grades, and required external marks to achieve a target grade.

## Features

- Calculate internal marks out of 40.
- Calculate external exam contribution out of 60.
- Calculate final marks out of 100.
- Automatically determine the grade.
- Calculate the external marks required to achieve different grades.
- Responsive design for mobile, tablet, and desktop.
- Simple and user-friendly interface.
- No login or installation required.

## Mark Calculation

### 1. Internal Marks (40)

The internal marks are calculated using:

- Class Tests (CT1 and CT2): 10 marks
- Sessionals (ST1 and ST2): 20 marks
- Home Assignment (HA): 10 marks

For both class tests and sessionals:
- Higher mark receives 2/3 weightage.
- Lower mark receives 1/3 weightage.

**Formula:**

```text
CT = (Higher CT × 2/3) + (Lower CT × 1/3)

ST = (Higher ST × 2/3) + (Lower ST × 1/3)

Internal = CT + ST + HA
```

### 2. External Marks (60)

The external examination is entered out of 100 and converted into 60 marks.

```text
External Contribution = (External Marks × 60) / 100
```

### 3. Final Marks (100)

```text
Final Marks = Internal Marks + External Contribution
```

## Grade System

The following grade boundaries are used by this calculator:

| Grade | Minimum Marks |
|---|---:|
| EX | 90 |
| A+ | 80 |
| A | 70 |
| B+ | 60 |
| B | 50 |
| C | 40 |
| F | Below 40 |

**Note:** These are configurable example grade boundaries and are not verified official university grading rules. Confirm the applicable grading regulations before relying on the result.

## Technologies Used

- HTML5
- CSS3
- JavaScript

## How to Use

1. Open the calculator website.
2. Enter your CT1 and CT2 marks.
3. Enter your ST1 and ST2 marks.
4. Enter your Home Assignment marks.
5. Enter your external examination marks.
6. Click Calculate.
7. View your internal marks, external contribution, final marks, and grade.

## Project Structure

```text
student-marks-calculator/
│
├── index.html
└── README.md
```

## Run Locally

1. Clone this repository:

```bash
git clone https://github.com/AbhinavKadiyala1014/student-marks-calculator.git
```

2. Open the project folder.
3. Open `index.html` in your web browser.

No additional dependencies are required.

## Deployment

This project can be hosted for free using GitHub Pages.

## Disclaimer

This is an independent student utility created for educational purposes. It is not an official university website or grading portal. Always verify marks and grade requirements with your institution.

## Author

**Abhinav Kadiyala**

GitHub: [AbhinavKadiyala1014](https://github.com/AbhinavKadiyala1014)

---

If this project helps you, consider giving the repository a ⭐.
