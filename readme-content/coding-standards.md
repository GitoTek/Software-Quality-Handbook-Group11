# Coding standards

## Table of content
* [Home](/README.md)
* [Tasks estimation in SCRUM](/readme-content/tasks-estimation.md)
* [Coding standards](/readme-content/coding-standards.md)
    * [Different code norms](#different-code-norms)
        * [The goal](#the-goal)
        * [The rules](#the-rules)
    * [Code documentation](#code-documentation)
* [Code reviews](/readme-content/code-reviews.md)
* [The link between the tree topics](/readme-content/topics-link.md)
* [Our project retrospective](/readme-content/project-retrospective.md)

## Different code norms

The coding rules are decided according to the needs of the company and the languages.

### The goal

Having rules to code allows to have a uniform code for all developers.
This makes it easier to read during reviews and increases maintainability.
Code can be more easily reused and errors much more easily detected.
Finally, the efficiency of the team is improved.

### The rules

Below is a non-exhaustive list of the most commonly used rules

1. Naming conventions for variables and function

    * Have meaningful variable names.
    * Avoid numbers in variable names
    * Have explicit function names with a verb

2. Identation

    Indentation concerns the number of spaces (or tabs) in a function or an if, while statement and even the spaces to put between 2 arguments of a function.
    
    For example, the braces that can be on a new line and the block of code that follows that must be on a new line too
3. Length of function

    Having short functions makes the program more structured and easier to read.
    Short functions with explicit names make debugging and code review much faster
4. Not use the GOTO keyword
    
    This keyword makes the program difficult to understand and follow. Debugging becomes much more complicated

For further information : https://www.geeksforgeeks.org/coding-standards-and-guidelines/

## Code documentation

Writing code documentation is not an easy task but it is very important.
Whether it is for other developers who will use your code or even for you later when you have to proofread it.

Each part of a project documentation is important and has its role.

<img src="./pictures/coding-standards/code-documentation/code-documentation.svg" width="600" height="300"><br>

* The short description allows the person who will read your code to know right away what it is used for.

* The Getting Started Guide should be accompanied by a basic example to show how your code works

* Tutorials should show examples of code with comments on the most likely use cases of the code

* The example projects show how an entire project using your code can work.

* The API documentation is the densest part to do but the most useful for other developers.
Every function, class, variable that can be used must be documented.
    
    Each element should be explained with a short description and if possible accompanied by a practical example

* The Architecture section is not as important as the previous sections but it is useful for people who could contribute to the project.


For further information : https://www.sohamkamani.com/blog/how-to-write-good-documentation/
