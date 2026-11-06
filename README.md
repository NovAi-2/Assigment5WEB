Assignment #5. JavaScript Basics (DOM Manipulation & Events)

Name: Van Alexander
Group: 2540 SE

GitHub repository: https://github.com/NovAi-2/AssigmentWEB
GitHub Pages: https://novai-2.github.io/AssigmentWEB/


Part 1: Profile Object, Data Types & Arithmetic

Task 1. The Personal Info Object
Create a JavaScript const object named userProfile that stores different data types: string (name), number (birthYear), boolean (isDeveloper) and an array (hobbies).

![Task 1](screenshots/task1.png)

Task 2. Arithmetic Calculations
Write a script that calculates the user's current age dynamically (current year minus birthYear) and another metric (age in months and the total hobbies count). Display the values in the console and on the page.

![Task 2](screenshots/task2.png)


Part 2: Form Input & Event Responses

Task 3. HTML Form Setup
Create a form with an input for Username, an input for Birth Year and a "Create / Update Profile" submit button.

![Task 3](screenshots/task3.png)

Task 4. Event Listener
Add a submit event listener to the form. When the button is clicked, capture the user's input values and update the userProfile object.

![Task 4](screenshots/task4.png)


Part 3: DOM List Manipulation

Task 5. Creating & Removing Elements
Create an unordered list (ul) with hobbies, an "Add Item" button that adds a new li item entered by the user, and a "Remove Item" button that deletes the last item from the list.

![Task 5](screenshots/task5.png)


Summary of work process

First I created the userProfile object with a string, a number, a boolean and an array. Then I wrote functions that calculate the age from the current year and the birth year, the age in months and the number of hobbies, and displayed them on the page and in the console. Next I built an HTML form and added a submit event listener that reads the input values, checks them and updates the userProfile object. Finally I made a list of hobbies and added two buttons: one creates a new li element with createElement and appendChild, the other removes the last li element. I tested everything in the browser and checked the console for errors.
