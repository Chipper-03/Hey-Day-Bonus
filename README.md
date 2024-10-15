# Hey-Day-Bonus

This is a simple Bash script that interacts with the user by using the echo command to prompt them for their name and then greeting them in return. It uses the read command to store the input as a variable before following that with another echo that incorporates the saved input that was provided.
Here is the URL to the Auburn Hey Day website that provides date, location, and context behind the event: https://sga.auburn.edu/hey-day/

Here is the code for the script:
#!/bin/bash

# Script greets the user and asks them to input a name
echo "Hello! I am so excited to meet you! What is your name?"
read name

# The read command will take what the user inputs and saves it under the variable name

echo "Hey $name! It is so awesome to meet you!"
