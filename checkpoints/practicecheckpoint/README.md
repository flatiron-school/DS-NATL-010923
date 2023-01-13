# Data Science Practice Checkpoint

This assignment is designed to test your understanding of the checkpoint process. It covers:

 - Anwering a code question
 
**Note on checkpoints generally**:
 
The purpose of assessments is to assess a student's comprehension and application of our Data Science program's key content.

Checkpoints are formative, in-depth assessments

Code challenges are summative, end-to-end assessments

## Imports

You will usually have to import different packages into a checkpoint or other material we give you

Don't worry if you don't have all the mechanics about what that means at this point

Just run the cell below, which is an example that imports the `string` module

(You do not need to use the `string` module to answer these questions, although technically you can use it if you want to)


```python
# Run this cell without changes

import string
```

## Cells with `# CodeGrade step` comments

**CodeGrade** is our grading tool for checkpoints. When it assesses Jupyter notebooks, it looks for cells that have special comments that include the name `CodeGrade` as well as a "step" number. Look below: The cell with the `greet_user` function has a comment that reads `# CodeGrade step1.1`. CodeGrade will be looking for your answers in these cells and so it is critical that you DO NOT DELETE THESE COMMENTS! Delete any **None**'s but do not delete the CodeGrade comments.

## Question 1

### Question Content

In the cell below, modify the `greet_user` function to do the following:

 - take a name as an argument
 - return the statement "Greetings! I am `name` and I am pleased to make your acquaintance!"

Then assign the name `"Gene Hackman"` to the variable `name`.

Run all cells to confirm the result.

### Additional Note

You can generally ignore the language of "your code here". Instead pay attention to where the `None`s are that need to be replaced. 


```python
# CodeGrade step1.1
# Replace None with appropriate code

def greet_user(name):
    """
    this function takes a string name as an argument 
    and returns a greeting including that name 
    """
    statement = None
    
    return statement
    
```


```python
# CodeGrade step1.2
# Replace None with appropriate code
name = None
```


```python
print(greet_user(name))
```

    Greetings! I am Gene Hackman and I am pleased to make your acquaintance!


## Test Cells

Sometimes you will see cells with **assert** statements. These test cells are designed to help you toward the right answers to questions. Run these cells to make sure that you are passing the tests, but know that this doesn't fully guarantee that your answer is correct. CodeGrade will also conduct **hidden** tests that you won't be able to access.

You will see an error message explaining what is wrong if your answer does not pass the visible tests.


```python
# greet_user should return a string
assert type(greet_user("Max")) == str
# name should be a string
assert type(name) == str
```


```python

```
