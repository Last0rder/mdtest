#CarGame

##Activity: carGame_Solved.html

###Instructions:

    *Using the code sent to you from the previous activity as a starting point, create a complete application that:

        *Users can enter keyboard input. (letters)

        *These letters then trigger the car’s functions.

        *These letters also trigger a global function called 'reWriteStats()' that logs the car’s make, model, color, mileage, and isWorking status to the console.

        *__HINT:__ Look into the 'document.onkeyup()' function to help you collect user input from the keyboard.
    
    *The resulting output should look like this.

    ![Sample Output](/8-RunCarGame_1.png)

-------------------------


###Solution:

    *Please check out the solution on YouTube.
    [![](https://img.youtube.com/vi/jtU6YrNPv7E/0.jpg)](https://www.youtube.com/watch?v=jtU6YrNPv7E)

    *Make a note of how the solution is effectively organized into sections for variables, functions, and function calls. This organization structure will help you on your upcoming homework assignment.


    *Using the 'document.onkeyup()' function, we capture keyboard input and store the letter pressed into the variable letter as a lowercase string.

    ![Solution](/9-CarGameSolved.png)

    *After the letter has been stored as a variable, we use if statements to check against the letters 'h', 'd', 'w', and 't'.


    *If any of these letters have been clicked, the appropriate car function is triggered along with the 'rewriteStats()' function, which prints out the car object data in the console.