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


# <span style="color:maroon"> **Part 1:Task List:**</span>
- [ ] Pick one of the tasks from the week 6 lab that your group completed in Vim in the second set of tasks.
- [ ]  give the shortest sequence of vim commands (less than 30 total keys pressed)
       1. Write out the sequence of keys to press using code formatting (with backticks `). 
       2. Use `<>` to indicate special keys (`<Backspace>` or `<Enter>` or `<Esc>`) and just the keys themselves for other    
          keys pressed. 
       3. Take a screenshot and describe which commands/keypresses got to that step, for each command where you move the         
          cursor or change the text. 
- [ ]  Write out every key pressed, including if you use the arrows or `h``j``k``l` to move around. 
- [ ] description/screenshot of typing `/apple<Enter>` and the cursor jumpting to the start of `apple`
- [ ] description/screenshot of typing `ce`, switching into input mode and deleting the word `apple`
      
# <span style="color:maroon"> **Part 2:Task List:**</span>

## What is the main point of the Big O Notation?
> <span style="color:blue"> Describe the asymptotic behavior of functions (which is how fast the f(x) grows/declines)</span>

## What is asymptotic behavior? 
> <span style="color:blue"> method of describing limiting behavior</span>

## What is limiting behavior?
> <span style="color:blue"> limit is value that f(x) approaches as input approaches some value</span>
> <span style="color:blue"> The limit of f(x), as x approaches a, is equal to L.</span>
> <span style="color:blue"> means: As x gets closer to a, f(x) gets closer to L.</span>

## Why do we need to use Big O for?
> <span style="color:blue"> used to classify algorithms according to run time or space requirements</span>

## Why do we need to classify algorithms according to run time or space requirements?
> <span style="color:blue"> Knowing how the algorithm works efficiently can add value to the way we do programming</span>
> <span style="color:blue"> Can make the program behave in required optimal conditions</span>

## What does optimal conditions means? 
> <span style="color:blue"> best level or state that it could achieve</span>

https://www.freecodecamp.org/news/all-you-need-to-know-about-big-o-notation-to-crack-your-next-coding-interview-9d575e7eec4/

### [Back to Contents:](https://chelcey.github.io/cse11-self-study/)****
