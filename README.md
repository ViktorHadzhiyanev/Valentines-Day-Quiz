# ❤️ Valentine's Day Quiz ❤️

This is a website created for celebrating Valentine's Day! The project features a set of questions that partner need to answer. After answering all the questions, confetti and music are triggered on the screen, and the results are calculated immediately.

## Features

- When your partner selects the **correct answer**, a **pop-up animation** appears, celebrating the correct choice! 🎉  
- If your partner select the **wrong answer**, the website will immediately highlight the **correct answer**, so your partner can learn from his/her mistakes.  
- Instant calculation of results after answering all questions.
- Confetti and music triggered when partner answer correctly.
- Motivational messages displayed if not all answers are correct.
- Real-time feedback on the correctness of answers.
- Automatic scroll to the top to show the result when there are many questions.
- Mobile version works aswell

## How It Works

1. Users begin answering a series of questions, each with one possible answers.
2. If partner answer correctly, confetti and music are triggered.
3. If not all answers are correct, a motivational message is displayed to encourage partner to try again.
4. The confetti and music only indicate if partner have answered all correctly and completed the quiz.

## Screenshot
![Screenshot](https://i.imgur.com/cDNkWcN.png)  
_A screenshot showing the confetti and music effect after both partners answer correctly._

## Technologies Used

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) 
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) 
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript&logoColor=black) 

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/ViktorHadzhiyanev/Valentines-Day-Quiz.git
    ```

2. Navigate to the project folder:
    ```bash
    cd Valentines-Day-Quiz
    ```

3. Open `index.html` in your browser.

4. Enjoy the fun and celebrate together with your partner!

## Editing, Adding Questions and Music

To edit existing questions or add new ones to the quiz:

1. Open the `index.html` file located into root folder of the project.
Line 22 for edit, Example
```javascript 
<div class="question-box">
    <div class="question">How is your day going?</div>
    <div class="option" data-correct="true" onclick="handleAnswer(this, 'correct')">Good</div>
    <div class="option" onclick="handleAnswer(this, 'incorrect')">Average</div>
    <div class="option" onclick="handleAnswer(this, 'incorrect')">Perfect</div>
</div>
```
_The attribute data-correct="true" must be added to the correct answer so that when the partner makes a mistake, it can indicate the correct one._

## Contributions

Contributions are always welcome! If you would like to contribute to this project, feel free to fork the repository and create a pull request. Make sure to update tests and documentation as necessary.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

[Viktor Hadzhiyanev]  
[GitHub Link](https://github.com/ViktorHadzhiyanev)
