# -QuizApplication-Java-Console-Quiz-with-Timer

QuizApplication is a Java-based console quiz game that challenges users with multiple-choice questions. Each question must be answered within 40 seconds, or the user is automatically exited from the quiz. The application keeps track of the user’s score and provides a summary at the end.

🔧 Features
⏱️ Timed Questions: Each question has a 40-second time limit.

🧠 Multiple Choice Format: Users choose from four possible answers per question.

🧮 Score Tracking: Displays the final score after all questions are answered.

📝 Summary View: Shows each question and the correct answer after the quiz ends.

💥 Auto Exit on Timeout: If time runs out for a question, the program exits immediately.

📋 How It Works
When you run the program, it displays instructions.

The user is presented with 5 general knowledge questions.

The user must input their answer (1-4) within 40 seconds.

After all questions:

The total score is shown.

A summary of each question with the correct answer is printed.

🖥️ Sample Output

🚀 How to Run
Save the code in a file named QuizApplication.java.

Compile using:
javac QuizApplication.java

Run the program:
java QuizApplication

📌 Notes
The quiz automatically terminates if the user fails to answer within 40 seconds.

You can add more questions by updating the questions and correctAnswers arrays.


✅ Future Improvements
Allow retrying instead of exiting on timeout.

Display the actual user's selected answer in the summary.

Store user answers and compare with the correct ones for detailed feedback.
