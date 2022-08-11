# Professional README Generator

Password generator
Project Repository address: https://github.com/JhonatanDP/pwd-generator

Project live web page: https://jhonatandp.github.io/pwd-generator/

Full Site
jhonatandp github io_pwd-generator_

## User History

- AS A developer
- I WANT a README generator
- SO THAT I can quickly create a professional README for a new project

## Acceptance Criterial

- GIVEN a command-line application that accepts user input
- WHEN I am prompted for information about my application repository
- THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, - Usage, License, Contributing, Tests, and Questions
- WHEN I enter my project title
- THEN this is displayed as the title of the README
- WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
- THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
- WHEN I choose a license for my application from a list of options
- THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
- WHEN I enter my GitHub username
- THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
- WHEN I enter my email address
- THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
- WHEN I click on the links in the Table of Contents
- THEN I am taken to the corresponding section of the README


Descripton
This project is about creating a password generator using javascript.
Acceptance Criteria
GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page
Work done to complete the challenge
I declared some variables that will save the user selection during the prompt.
I declared some variables with the corresponding arrays (lowercase, number and special character).
I created the uppercase array using toUpperCase method.
I declared a function called generatePassword () name was giving.
I declared a new variable to save the lenght. (user input)
I used if and else if to check variables based on user selections.
I divided those selection based on combinations.
I used concat to merge arrays selected by the user.
I used a for loop to created a random array based on the user selection and use join to removed "" and covert it to string.
I passed the value of the variable to the function to writePassword.
