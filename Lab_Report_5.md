# Lab Report 5

## Part 1: Debugging Scenario
### Background
- Students asked to create a simple bash program which asks for user input
- More Specifically, this will cover a program which has a secret number code and asks for an input from the user and the respose will be different depending on if it's correct.
### Student post
![image](https://github.com/angelocake/Lab_Report_5/assets/130005453/ae6e219b-b766-4ae3-9267-067d236f31ad)

- This image above shows a sample post of a student who ran into an issue with their program.
- Below is an image of the student's code along with two examples of them running their program with their error pointed out by a red arrow.

Student's code: 
![Start_Code](https://github.com/angelocake/Lab_Report_5/assets/130005453/9653a3ee-4bff-4067-a314-14bcbfb7df5d)

### TA Response
It seems like there was a slight error when you wrote the code. 
I would double check that all variables are written properly.

### Fixed and Bug Description
Below is an image of the fixeed code with the terminal showing that the output was the desired output.
![fixed_code](https://github.com/angelocake/Lab_Report_5/assets/130005453/d9b279c5-c78e-4947-86d2-7ae80a6b10c4)

The Bug was a misspelling of one of the variables which caused the if statement to not propery compare the user's input to the secret code.

### Info Needed about setup
- File/Directory: I did mine by creating a `.sh` file and named it `bug.sh`. Also where the file is doesn't matter as long as you are in the proper directory where the `.sh` file was locate (for me I put mine in my downloads directory so I needed to be in there to access it).
- Contents:
- Command Lines: To trigger the bug, a couple steps were needed to notice it.
  1. The code `bash bug.sh` be ran in a bash terminal
  2. Type a number that is not "3" and press `<enter>`
  3. See output is the the output meant for incorrect guesses
  4. Rerun The code `bash bug.sh`
  5. Type the number "3"
  6. Look at the input. (Notice:  It should have been the correct part of the if statement but instead was the incorrect part of the if code)
- Edit to fix Bug: The only edit needed to be done was adding an "e" at the end of the word "Cod" found on line 5 (inside the if statement). Editing could be done through the terminal but I just edited the file directly using VisCode.


## Part 2: Reflection
I learned a variaety of things that a programer could do while using a terminal. 
On top of this I also learned aout different ways in which people will use 
terminals along with vim and bash to not only edit files but also run programs.
These uses of the terminal were interesting to learn about and I do think it 
will come in handy as I continue on with the rest of my courses.


