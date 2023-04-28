# studyapp
This Python study app allows users to add questions to a CSV file and then study them in a randomized order. It includes features such as the ability to select questions based on specific tags, a timer, and the ability to log study results. The app is designed to help users study more efficiently and keep track of their progress.

# studyapp
This Python study app allows users to add questions to a CSV file and then study them in a randomized order. It includes features such as the ability to select questions based on specific tags, a timer, and the ability to log study results. The app is designed to help users study more efficiently and keep track of their progress.

# Installation

To use this app, you'll need to have Python and Jupyter Notebook installed on your machine. Here's how to install them:

Python: Go to the official website of Python (https://www.python.org/downloads/) and download the latest version of Python. Run the installer and follow the prompts to install Python.

Jupyter Notebook: Go to the Anaconda website (https://www.anaconda.com/download) and download the latest version of Anaconda. Run the installer and follow the prompts to install Anaconda. Open Anaconda Navigator and launch Jupyter Notebook.

# Running the Application

Clone or download the repository to your local machine. Open Jupyter Notebook and navigate to the cloned repository. Open the studyapp.ipynb notebook.

# How to Use

The study app Python code is a command line tool designed to help users study and review information by asking questions and providing immediate feedback. The code utilizes the CSV module to read and write data to and from files, the random module to select questions at random, and the time module to track the time taken to answer questions. The app allows users to add new questions, view available tags, and select questions based on a chosen tag or from random topics.

The main function of the app is the study session function. The function begins by checking if the 'questions.csv' file exists and has at least one question in it. If no questions have been added yet, the app prompts the user to add a new question from the main menu. If there are no questions in the list, the app informs the user that no questions have been added yet. Once there are questions available, the user can choose to either select a tag or get questions from random topics.

The app selects a random question from the chosen tag or topic, displays the question and its answer choices, and prompts the user to input their answer. If the user's answer is correct, the app removes the question from the selected questions and logs the question, the user's answer, and the time taken to answer the question to the 'results.csv' file. If the user's answer is incorrect, the app adds the question and the user's answer to the wrong questions list and logs the question, the user's answer, and the time taken to answer the question to the 'results.csv' file.

After answering all questions, the app displays the results of the study session. If the user answered all questions correctly, the app congratulates the user and returns to the main menu. If the user answered some questions incorrectly, the app displays the list of incorrectly answered questions along with the correct answer and the user's answer. The user can choose to continue or quit to the main menu.

The app provides a simple and efficient way for users to review information and test their knowledge on specific topics. With the ability to add new questions and select questions based on tags or random topics, the app can be customized to fit the user's needs. Additionally, the app logs the user's results to a file for future reference, allowing users to track their progress and identify areas for improvement.

# Contribute

Contributions are welcome! To contribute to the project, please follow these steps:

Fork the repository
Create a new branch
Make your changes and commit them
Push your changes to your forked repository
Create a pull request

# Author

Murat Ozder (muratozder@gmail.com)
