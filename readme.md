# Todo List

A website coded using HTML, CSS, and Javascript that let's the user add and remove tasks from their todo lists by inputting the name and date of each task. 

This website exists to focus in on Javascript and how to code buttons so that anytime a "click" event is heard, the code manipulates the html on the document and edits the array of task objects depending on if the user adds or deletes the task.



![todo_list](img/todo_list.gif)

## Core Technical Concepts

A list of task objects todoList is created and the Javascript code calls the renderTodoList function. The function grabs the name and due date of each task inputted by the user and displays the html on the page using document.querySelector. The code listens for a "click" event for the delete button for each task. If a delete button is clicked, the specific task in the list gets spliced or removed and calls the renderTodoList function again to update the html on the page.

![image-20230910191721691](C:\Users\jonat\AppData\Roaming\Typora\typora-user-images\image-20230910191721691.png)

In the addTodo function, both types of inputs (the names and dates) are stored in two constant variables and are added to the todoList array as objects whenever the "click" event is heard from the add button. 

![image-20230910214209515](C:\Users\jonat\AppData\Roaming\Typora\typora-user-images\image-20230910214209515.png)

## Getting Started/Requirements

To run this website, download the code from [github.com/JCV2022/About-Me-Website](https://github.com/JCV2022/About-Me-Website)

A code editor program is needed. Any should do fine, I used Visual Studio Code to code my website.

If you do use Visual Studio Code as your code editor, install the extension Live Server to be able to run the code in real-time.

![image-20230910181043468](C:\Users\jonat\AppData\Roaming\Typora\typora-user-images\image-20230910181043468.png)

## Contact Info

My email address is vujonathan00@gmail.com

My github is github.com/JCV2022

My linkedIn is linkedin.com/in/jonathan-vu-409a71132/
