#### Assessment schedule/Mahere Aromatawai: Digital Technologies: Hangarau Matihiko
### Achievement Standard 91883 – Automate the Boring Stuff

# *The student has developed a computer program.*

**Evidence/Judgements for Achievement/Paetae**

The student has written a simple, functional program in the language of their choice. The program may not be structured very well.
## Writing a program that performs the specified task, using a suitable programming language
### The program has:

- variables which store at least two different data types
- sequence, selection and iteration control structures
- input either from a user or an external source
- either data stored in a list, array or dictionary **or** user defined methods, procedures or functions
_Note that BOTH functions AND lists are not required to pass this standard._
>For example (partial evidence): The program works as expected
_The student has written the code in a procedural manner, including use of loops, conditions and functions or indexed structures._

## Setting out the program code clearly and documenting the program with comments

Comments are present but may not be particularly descriptive of frequent.
>For example (partial evidence): 
`# this code creates the main loop`

## Testing and debugging the program to ensure that it works on a sample of expected use cases.

The student has shown some evidence of expected use cases that were used to test and debug the program to show that the program works when the user inputs data that is expected.Testing may be trial and error rather than clearly thought out.
>For example (partial evidence): _The student has written about some expected use case data and has tested what happens when the program is run. Such testing may be observed by the teacher, presented in table form with minimal notes, or simply explained using examples._

_The examples above are indicative samples only_


# *The student has developed an informed computer program.*
**Evidence/Judgements for Achievement with Merit/Kaiaka**


The student has frequent clear comments throughout the code that helps to describe relevant functions or sections of code. The variable names clearly describe the data they hold.

## Documenting the program with variable names and comments that describe code function and behaviour

> **For example (partial evidence)**_eg. `# this function tests that the user input is a number. It will continue to ask for input until the input is a number. e.g. answer = is_a_number(question)`

## following conventions of the chosen programming language
The student has followed most common programming conventions for their chosen language.
> **For example (partial evidence)** _Python files and functions contain a docstring explaining the purpose of the program/function. Constants are ALL\_CAPS with underscores separating the words if required. __Variable names use underscore rather than Camel case.__ Functions appear before loose lines of code and main section of code is all at bottom, not between the functions, thus making the program easier to read._

## testing and debugging the program in an **organised** way to ensure that it works on a sample of both expected and relevant boundary use cases.


The student tests frequently during development (observed) and the final program works when the user inputs the data that is expected and checks or handles when the data is outside of specific thresholds.

The student may have kept some form of notes showing what was tested and the outcome of that testing.Test use cases by student include expected and boundary use cases.

>**For example (partial evidence)** _Student code has been tested to show that if there are boundaries (eg: choose a level between 1 and 3), code has been tested for 0 (too low), 1 (low valid), 3 (high valid) and 4 (too high)._
_The program might not correctly handle unexpected data and fail when a word is typed in where a number was expected._

_The examples above are indicative samples only_ 

# *The student has developed a refined computer program.*
**Evidence/Judgements for Achievement with Excellence/Kairangi**

## Ensuring that the program is a well-structured, logical solution to the task

> **For example (partial evidence)**_The code is clean, concise, efficient and easily readable. The main program may be short and might consist of multiple reusable user defined functions which do most of the logic and processing.__The layout might include sections as follows (all the material might be in a loop to allow multiple questions to be asked until a condition is met)_
>- _import modules (eg: import random)_
>- _user defined functions_
>- _set up constants_
>- _initialise variables_
>- _generate / ask question_
>- _calculate correct answer_
>- _get user answer and check it is valid_
>- _compare user answer with correct answer and update score / counters_
>- _give user feedback_


## Making the program flexible and robust


- The student has used methods, functions, procedures, actions and control structures effectively.
- User input is checked to ensure that it is valid
- Expected, boundary and invalid user input is handled correctly \&lt;see testing\&gt;
- Constants, variables and derived values are used instead of hard coded values

>**For example (partial evidence)**: Student uses a series of if, elif, else statements rather than multiple, single &#39;if&#39; statements . eg: to check a user answer where &#39;x&#39; is a special exit code, their code might say:

```
if user_ans == 'x':
    do something 
elif user_ans == correct 
    do something 
else
    do something
```
_rather than separate statements_
```
if user_ans == 'x': 
    break out of loop
if user_ans == correct 
    do something
if user_ans != correct
    do something
```
> Code handles expected and boundary values correctly (as for merit). In addition, it has also been tested for a decimal (eg: 2.5, invalid) and a string (eg: &#39;two&#39;, invalid). Students may have used &#39;try / except&#39; code to ensure that their program handles invalid data gracefully.

## Comprehensively testing and debugging the program in an organised and time-effective way to ensure the program is correct on expected, boundary and invalid use cases.

The student tests their program in a systematic way to ensure that it works correctly for all logical pathways.
> **For example (partial evidence)**: _Test cases have been well-thought out and notes may have been made showing that the code works as expected for all use cases. The student has checked all the logical pathways for their program to ensure that it works as expected._

_The examples above are indicative samples only_


Final grades will be decided using professional judgement based on a holistic examination of the evidence provided against the criteria in the achievement standard.

