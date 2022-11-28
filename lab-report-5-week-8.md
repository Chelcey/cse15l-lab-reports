# <span style="color:purple"> **Lab Report 5 Week 8**</span>
### <span style="color:magenta"> Chelcey Do</span>


## Here is `grade.sh` in a code block
> <span style="color:blue"> Details about the code block.</span>
```
# Create your grading script here

set -e
CPATH= '.:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar'

rm -rf student-submission
git clone $1 student-submission
echo 'Finished cloning'

#specify the location of the classes
cp TestListExamples.java student-submission

#changing the directory 
cd student-submission
#if [[<test-expr>]] 
#then [[5 -eq 10]]

#else 
#    -e file.txt
#fi 


echo -n "Submission: "
read $1

# Check if ListExamples.java Exist (1) or Not (0)
if [[ -find ListExamples.java ]]
then
	echo "ListExamples.java is 0. Submission Error."
	exit
else
	echo "ListExamples.java is 1. Submission Success."

fi

cp student-submission/ListExamples.java ./
javac -cp $CPATH *.java
java -cp $CPATH org.junit.runner.JUnitCore TestListExamples

# Check if Tests compiled successfully (1) or not (0)
if ! [[$? -eq 0]]
then
	echo "There is an errror. (0) No tests compiled successfully."
	exit
else
	echo "(1) Tests compiled successfully."
fi

java -cp $CPATH org.junit.runner.JUnitCore TestListExamples > gradeResult.txt

#Output that TestListExamples was successful
echo "TestListExamples compiled successfuly"
cat gradeResult.txt
fail=$(grep -i "Tests compiled:" grade.Result.txt)

if [[ $fail == "" ]]
then	
	echo "All tests compiled successfully."
else	
	echo "Tests did not compile succesfully."
	echo $fail
fi
```

## Student Submission 1 
![Student Submission 1](ss1.jpg)
> <span style="color:blue"> **Grade:** pending</span>

## Student Submission 2 
![Student Submission 2](ss2.jpg)
> <span style="color:blue"> **Grade:** pending</span>

## Student Submission 2 
![Student Submission 3](ss3.jpg)
> <span style="color:blue"> **Grade:** pending</span>

## Describing a trace of what your `grade.sh` 
### <span style="color:red"> Student Submission Pending</span>
- [ ] For each line with a command, what is its *standard output* and *standard error* are for this run, and whether its *return code* was zero or nonzero.

> <span style="color:blue"> Pending...</span>

- [ ] For each line with an `if` statement, whether the condition was true or false, and why

> <span style="color:blue"> Pending...</span>


- [ ] Indicate each line that *does not* run (maybe because it is an `if` branch that doesn't evaluate, or after an early exit)

> <span style="color:blue"> Pending...</span>
 

### [Back to Contents:](https://chelcey.github.io/cse15l-lab-reports/)
