BIC21203 Lab 4a: Client-Side Scripting (JavaScript)

Name: MUHAMMAD AMIRUL HAFIZ BIN JASMANI

Student ID: AI240040

Overview

This repository contains the solutions for Lab #4a, focusing on modern client-side JavaScript. The objective of this lab is to develop interactive web pages by applying JavaScript functions, event handling, input validation, loops, and DOM manipulation.

 Project Structure

The repository is divided into three main parts:

Q1/ - Question 1: Interactive Text Changer

Q2/ - Question 2: Smart Number Validator

Q3/ - Question 3: Dynamic Number Generator

🚀 How to Run the Code

Clone this repository to your local machine:

git clone https://github.com/[Mrulfiz]/bic21203-lab4a-javascript.git


Navigate to the specific question folder (e.g., Q1, Q2, or Q3).

Open the .html file inside the folder using any modern desktop web browser (e.g., Chrome, Firefox, Edge). No external libraries or local servers are required.

🔍 Lab Questions & Evidence

Question 1: Interactive Text Changer

Description: A simple webpage that uses DOM selection methods, a custom function (changeMessage()), and an event listener to change a paragraph's text from "Welcome to my website!" to "Hello there!" when a button is clicked.

Output Screenshot:

![Q1 Output Before](lab4/images/4AQ1A.png)
![Q1 Output After](lab4/images/4AQ1B.png)

Question 2: Smart Number Validator

Description: An interactive webpage that accepts user input, validates it, and displays a specific message based on the value. It handles empty inputs, invalid strings (e.g., "abc"), and compares valid numbers against the number 10.

Test Cases Handled:

5 -> "The number is lower than 10"

10 -> "The number is equal to 10"

15 -> "The number is higher than 10"

abc / Empty space -> "Please enter a valid number!"

Output Screenshots:


![Q2 Output](lab4/images/4AQ2low.png)
![Q2 Output](lab4/images/4AQ2high.png)
![Q2 Output](lab4/images/4AQ2wrong.png)
![Q2 Output](lab4/images/4AQ2equal.png)

Question 3: Dynamic Number Generator

Description: A webpage that generates an ordered list (<ol>) from 1 to 5 using a for loop and DOM creation methods (document.createElement). It clears previous entries upon repeated clicks to prevent list duplication.

Output Screenshot:

![Q3 Output Before](lab4/images/4AQ3,1.png)
![Q3 Output After](lab4/images/4AQ3,2.png)