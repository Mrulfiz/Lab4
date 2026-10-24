BIC21203 Lab 4b: Client-Side Scripting (JSON and jQuery)

Name: MUHAMMAD AMIRUL HAFIZ BIN JASMANI

Student ID: AI240040

Overview

This repository contains the practical implementations for Lab #4b. The project demonstrates how to structure valid JSON data, retrieve it asynchronously using the native JavaScript fetch() API, and utilize the jQuery library to simplify DOM manipulation and event handling.

Project Structure

books.json - A valid JSON file containing an array of book objects (Question 1).

books.html - An HTML page that fetches and displays the data from books.json using native JavaScript (Question 2).

jquery-dom.html - An HTML page demonstrating equivalent DOM manipulations and event handling using jQuery 4.0.0 (Question 3).

Setup and Run Instructions

Important Note for Question 2 (books.html)

Because books.html uses the fetch() API to read a local file, you cannot open it directly by double-clicking the file (this will cause a CORS error). You must use a local development server.

Using VS Code Live Server 

Open this repository folder in Visual Studio Code.

Install the "Live Server" extension by Ritwick Dey if you haven't already.

Right-click on books.html in the file explorer and select "Open with Live Server".

The page will open in your default browser (e.g., http://127.0.0.1:5500/books.html).

Lab Evidence

Question 1: JSON Validation

Screenshot showing books.json parsing successfully without errors:
![Q1 Validation](lab4/images/4BQ1.png)

Question 2: Retrieve and Display JSON Data

Screenshot showing the successfully fetched book titles, authors, and genres:
![Q2 Output](lab4/images/4BQ2.png)

Question 3: jQuery vs Native DOM

![Q3](lab4/images/4BQ3A.png)
![Q3](lab4/images/4BQ3B.png)
