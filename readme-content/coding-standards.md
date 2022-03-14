# Coding standards

## Table of content
* [Home](/README.md)
* [Tasks estimation in SCRUM](/readme-content/tasks-estimation.md)
* [Coding standards](/readme-content/coding-standards.md)
    * [Work with cyclomatic complexity](#work-with-cyclomatic-complexity-br)
        * [Quick definition](#quick-definitionbr)
        * [How to evaluate it](#how-to-evaluate-itbr)
        * [How to work with too complex code](#how-to-work-with-too-complex-codebr)
* [Code reviews](/readme-content/code-reviews.md)
* [The link between the tree topics](/readme-content/topics-link.md)
* [Our project retrospective](/readme-content/project-retrospective.md)


## Work with cyclomatic complexity <br>

### Quick definition<br>

<b>Cyclomatic complexity</b> is a software metric that developer can use to indicate the complexity of a code section or an entire program.<br>
It can be understood as the number of linearly independent paths a code section has in it.<br>
E.g. a code with no flow statement has a <b>cyclomatic complexity of 1</b>.<br>
E.g. a code with one if condition has a <b>cyclomatic complexity of 2</b> as the result of a if condition can be true or false.<br> 


### How to evaluate it<br>

According to akash1295 (2021), there is a simple formula to calculate the cyclomatic complexity of a code section:<br>

<img src="./pictures/coding-standards/cyclomatic-complexity/cyclomatic-complexity-formula.png"><br>

Example for a simple code section, the cyclomatic complexity is : 7 - 7 + 2 = 2<br>
<img src="./pictures/coding-standards/cyclomatic-complexity/code-section.png">
<img src="./pictures/coding-standards/cyclomatic-complexity/flow-graph.png"><br>

### How to work with too complex code<br>

In case of a too complex code, you have several options of optimisation:
- remove duplicated/obsolete code
- smaller functions
- reduce the number of decision structures
- don't code methods from the framework you are using<br><br>

## References

- Article by akash1295 - GeeksforGeeks, 21 June 2021, "Cyclomatic Complexity"
    - https://www.geeksforgeeks.org/cyclomatic-complexity/
    - https://linearb.io/blog/reduce-cyclomatic-complexity/