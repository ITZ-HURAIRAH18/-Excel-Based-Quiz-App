# 🧠 Excel-Based Quiz App

A dynamic and interactive web-based quiz application that allows users to create and take quizzes using custom question sets from uploaded Excel files. This app is designed to provide a flexible and engaging quiz experience with features like real-time answer validation and a countdown timer for each question.

---

## 🚀 Features

The Quiz App comes packed with the following key features:

* **Dynamic Question Loading:** Users can upload an Excel file (`.xlsx`) containing Multiple Choice Questions (MCQs). The app dynamically reads the questions, options, and correct answers from the file.
* **Configurable Quiz Settings:**
    * **Number of Questions:** Users can specify the exact number of questions they wish to take from the uploaded Excel file.
    * **Time per Question:** A configurable countdown timer ensures that users answer each question within a set time limit, promoting quick thinking.
* **Real-Time Answer Validation:** As users select an answer, the app provides instant feedback by highlighting:
    * **Correct Answers:** Marked with a green indicator (✅).
    * **Incorrect Answers:** Marked with a red indicator (❌), with the correct answer simultaneously revealed.
* **Countdown Timer:** Each question is accompanied by a visible countdown timer. If the time runs out before an answer is selected, the app automatically highlights the correct answer and proceeds to the next question.
* **Quiz Result Summary:** Upon completion of the quiz, users receive a comprehensive result summary showing their score.
* **Responsive Design:** Built with Bootstrap, ensuring a consistent and appealing layout across various devices (desktops, tablets, mobile phones).
* **User-Friendly Interface:** An intuitive design with clear navigation and input fields makes it easy for anyone to create and take quizzes.
* **Attractive Visuals:** Utilizes a background video on the landing page and subtle styling for an engaging user experience.

---

## 📂 Project Structure

The project is organized into the following main components:

* `index.html`: The main landing page of the Quiz App, introducing its features and guiding users.
* `quiz.html`: The core quiz interface where users upload files, configure quiz settings, and take the quiz.
* `style.css`: Custom CSS for the `index.html` page, providing unique styling.
* `quiz.css`: Custom CSS for the `quiz.html` page, defining the layout and appearance of the quiz interface.
* `quiz.js`: The main JavaScript file containing the logic for reading Excel files, managing quiz flow, handling timers, and validating answers.
* `vedio/bgvedio.mp4`: The background video used on the landing page.
* `images/me.png`: The profile image used in the "About Us" section.
* **External Libraries:**
    * **Bootstrap 5.3:** For responsive design and pre-built UI components.
    * **Font Awesome 6.0.0:** For iconic fonts used across the application.
    * **SheetJS (xlsx.full.min.js):** A powerful library for reading and parsing Excel files directly in the browser.
    * **Web3Forms:** Used for the contact form submission.

---

## 💡 How to Use / Run Locally

**Live Demo:**
You can access a live version of the Quiz App here: [https://eraquiz.netlify.app/](https://eraquiz.netlify.app/)

Follow these steps to set up and run the Quiz App on your local machine:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Quiz-App.git](https://github.com/YOUR_USERNAME/Quiz-App.git)
    ```
    * **Note:** Replace `YOUR_USERNAME` with your actual GitHub username and `Quiz-App` with your repository name if it's different.

2.  **Navigate to the project directory:**
    ```bash
    cd Quiz-App
    ```

3.  **Open `index.html`:**
    Simply open the `index.html` file in your preferred web browser. You can do this by double-clicking the file or by dragging it into your browser window.

4.  **Using the Quiz App:**
    * From the `index.html` page, click on the "Let's Start" button or navigate to `quiz.html`.
    * On the `quiz.html` page:
        * **Upload Excel File:** Click "Choose File" and select your `.xlsx` file containing the quiz questions. (Refer to the "Excel File Format" section below for the required structure).
        * **Set Questions and Time:** Enter the desired number of questions and the time limit per question in seconds.
        * **Start Quiz:** Click the "Start Quiz" button to begin the quiz.

---

## 📄 Excel File Format for Questions

For the quiz app to correctly read your questions, your Excel file (`.xlsx`) must follow a specific format:

| Column Header | Description | Example Value (Row 1) |
| :------------ | :---------- | :-------------------- |
| `Sr` | Serial Number of the question. | `1` |
| `Question` | The full text of the question. | `What is the capital of France?` |
| `Option A` | The text for the first option. | `Berlin` |
| `Option B` | The text for the second option. | `Madrid` |
| `Option C` | The text for the third option. | `Paris` |
| `Option D` | The text for the fourth option. | `Rome` |
| `Correct Answer` | The letter corresponding to the correct option (e.g., `A`, `B`, `C`, `D`). | `C` |

**Example Data (as seen in your HTML table):**

| Sr | Question | Option A | Option B | Option C | Option D | Correct Answer |
| -- | -------- | -------- | -------- | -------- | -------- | -------------- |
| 1 | What is the capital of France? | Berlin | Madrid | Paris | Rome | C |
| 2 | Which language is used for web development? | Python | HTML | Java | C++ | B |
| 3 | What is 5 + 3? | 6 | 7 | 8 | 9 | C |

---

#
## 🤝 Contributing 

Contributions are always welcome! If you have suggestions for improvements, new features, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create your feature branch (`git checkout -b feature/YourFeatureName`).
3.  Commit your changes (`git commit -m 'Add some YourFeatureName'`).
4.  Push to the branch (`git push origin feature/YourFeatureName`).
5.  Open a Pull Request.

---

## 📄 License (Optional)

This project is licensed under the MIT License - see the `LICENSE` file for details.

---

## 📧 Contact (Optional)

* **Muhammad Abu Hurairah** - muhammadabuhurairah558@gmail.com

Live Demo: [https://eraquiz.netlify.app/](https://eraquiz.netlify.app/)
