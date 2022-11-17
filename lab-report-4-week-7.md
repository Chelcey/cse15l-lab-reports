# <span style="color:navy"> **Lab Report 4 Week 7**</span>
## <span style="color:purple"> **Chelcey Do**</span>
---

# <span style="color:fuschia"> **Lab Goals:**</span>
> Writing a bash script that takes the URL of a Github repository andprints out a grade.

# <span style="color:maroon"> **Pre-Task List:**</span>
- [x] Fork the given [Repository](https://github.com/ucsd-cse15l-f22/list-examples-grader)
- [x] Given a list of repositories to test the grader

## <span style="color:pink"> **Grading Script should include:**</span>
- [ ] grade message (pass/fail, or maybe a proportion of tests passed - your choice) if the tests run.
- [ ] useful feedback message (compile error, wrong file submitted, etc.)

## <span style="color:pink"> **General Workflow for Script:**</span>
- [ ] Clone the repository of the student submission to a well-known directory name 
- [ ] Check student code has the correct file submitted. If they didn't, detect and give helpful feedback about it.
      Useful tools here are `if` and `-e`/`-f`. You can use the `exit` command to quit a bash script early. 
- [ ] Somehow get the student code and your test `.java` file into the same directory
      Useful tools here are `cp` and maybe `mkdir`
- [ ] Compile your tests and the student's code from the appropriate directory with appropriate classpath commands. 
      If compilation fails, detect and give helpful feedback. 
      Aside from `javac`, useful tools here are output redirection and error codes (`$?`) along with `if`. 
      This might be the time to turn *off* `set -e`.
- [ ] Run the tests again and report the grade based on JUnit output
      Again output redirection and `grep` is useful
      
- [ ] Screenshots of what your grader does on each of the sample cases above
      - [ ] list-methods-lab3
      - [ ] list-methods-corrected
      - [ ] list-methods-compile-error
      - [ ] list-methods-signature
      - [ ] list-methods-filename
      - [ ] list-methods-nested
      - [ ] list-examples-subtle

- <span style="color:red"> *I am unable to do this portion at this point in my lifetime. Hopefully in my next life, I will be able to be a better coder. It is not that deep.* </span>


# <span style="color:maroon"> **Part 1:Task List:**</span>
- [ ] Pick one of the tasks from the week 6 lab that your group completed in Vim in the second set of tasks.
- [ ]  give the shortest sequence of vim commands (less than 30 total keys pressed)
       1. Write out the sequence of keys to press using code formatting (with backticks `). 
       2. Use `<>` to indicate special keys (`<Backspace>` or `<Enter>` or `<Esc>`) and just the keys themselves for          other keys pressed. 
       3. Take a screenshot and describe which commands/keypresses got to that step, for each command where you move          the cursor or change the text. 
- [ ]  Write out every key pressed, including if you use the arrows or `h``j``k``l` to move around. 
- [ ] description/screenshot of typing `/apple<Enter>` and the cursor jumpting to the start of `apple`
- [ ] description/screenshot of typing `ce`, switching into input mode and deleting the word `apple`
- [ ] description/screenshot of typing `banana<Esc>`, replacing the text and returning to insert mode
- [ ] description/screenshot of typing `:w<Enter`, saving the changes
      
# <span style="color:maroon"> **Part 2:Task List:**</span>
- [ ] Start in Visual Studio Code and make the edit there (**what edit??**)
- [ ] `scp` the file to the remote server and run it there to confirm it works (you can just run `bash test.sh` on the remote to test it out)
- [ ] Start already logged into a `ssh` session
- [ ] Make the edit for the task you chose (**I didn't chose this**)  in Vim, exit Vim and run `bash test.sh`
- [ ] Report how long it took you to make the edit in seconds in both styles, and any difficulties or details that came up in doing so. 
      

## Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?
> <span style="color:blue"> I would prefer to use the easier one, but in my case I choose neither. I currently don't want to even think about working on a program that I can run remotely. I used to want to work remotely, but now at this point, I don't have what it takes. It gives me stress and anxiety. At this point, I am about to quit.</span>

## What about the project or task might factor into your decision one way or another (If nothing would affect your decision, say so and why!?) 
> <span style="color:blue"> The projects or tasks that factored in my decision is realizing that I wasted my whole life doing something that I am not even great at, believing that I can do it. This is a major factor into my current decision of my view point.  </span>





### [Back to Contents:](https://chelcey.github.io/cse11-lab-reports/)****
