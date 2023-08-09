# PASSWORD-GENERATOR
Python project for a user-friendly Password Generator.

1. Importing Modules
    - We import all the necessary modules that are required for creating a user-friendly GUI.
    - The Tkinter module is used to create the graphic interface.
    - The random module is used to generate a random pattern/value.
    - The string module is used to take the help of the string functions.
      
2. Function to Generate Password
    - We create a function named generate_pwd for this purpose.
    - The function takes length as an entry.
    - Depending on the length the user entered the function generates a password that is a random pattern containing ASCII letters, digits, and punctuation symbols.
      
3. Function to Display Message
    - We create a function named display_msg that displays a message once the user accepts the password.
    - This function takes the username from the entry and the generated password and displays a suitable message.
      
4. Function to Reset
    - We create a function named reset to clear all the input values, generated values as well as the message by setting it all to "".
      
5. Function to Exit
    - This function destroys the created Tkinter window and all data is lost.
    
6. Setting up the Window
    - We then set up a window with the desired title, size, background, etc.
    - The username and length labels are then created to get the values from the user. These are then packed into the window.
    - The generate button and accept button are used to create buttons for the generate_pwd function and display_msg function.
    - The message label creates a label where the desired message is displayed once the user accepts the password.
    - The reset button and exit button are used to create buttons for the reset and exit functions.
    - The window is finally looped for proper execution.
