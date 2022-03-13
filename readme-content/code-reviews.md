# Code reviews

## Table of content
* [Home](/README.md)
* [Tasks estimation in SCRUM](/readme-content/tasks-estimation.md)
* [Coding standards](/readme-content/coding-standards.md)
* [Code reviews](/readme-content/code-reviews.md)
    * [What is a pull request](#what-is-a-pull-request-br)
    * [How to do a good review ?](#how-to-do-a-good-review)
        * [How to prepare the review](#how-to-prepare-the-review)
        * [Best practice for a good review](#best-practice-for-a-good-review)
* [The link between the tree topics](/readme-content/topics-link.md)
* [Our project retrospective](/readme-content/project-retrospective.md)

<br>
Code reviews are essential for the good development of a Softare products. In this section, we will go through the best habits to make a good code review, using <b>pull requests</b>.<br> <br>

## What is a pull request? <br>

### Git context 

When developping in a team, people save their code in a common code history system: <b>git</b>.<br>
On this git, developers create different <b>branches</b>. A branch is a copy of an original code version, on which you develop on a specific feature/fix. <br>
Once done, the branch is <b>merged</b> back to the original one, to add the work to to original version of code.<br>
It enables developers to work on the same files without corrupting them, by merging works one by one.<br><br>

### Pull request definition

Paraphrasing Nelis (2017), a pull request is <b>"a mechanism for a developer to notify team members that a feature or fix, developed on a separate branch, is ready".</b><br>
When a pull request is created by one developer, other developers are assigned to look at the work, give comments, and refuse or validate it.<br>
A pull request has a name and a description of the tasks done.<br>

<img src="./pictures/code-reviews/pull-request-definition/pull-request-screenshot.png"><br>

If the pull request is refused, the developer at the origin of the pull request has to fix the indicated problems, before asking for a new pull request.<br>
If validated, the branch is merged to the original one and the developer can do the same scenario for another feature/fix.<br><br>

## How to do a good review

Code reviews are made to have a better code
And doing better code reviews makes for even better code!
Let's see how to make code reviews more efficient

### How to prepare the review

1. The important questions to have in mind
    * Do I understand what the code does?
    * Does the code function as I expect it to?
    * Does this code fulfill regulatory requirements?

2. What to look in the code
    * Structure
    * Style
    * Logic
    * Performance
    * Test coverage
    * Design
    * Readability
    * Functionality

### Best practice for a good review

1. Build & Run the program
    * You can see how the program works
    * This allows you to ensure that the code works as intended

2. Don't review for more than 60 minutes
    * After this time, your concentration will no longer be maximal
    * Taking breaks allows you to return to the review with a clearer mind

3. Check no more than 400 lines at a time
    * After this limit, it will be more complicated to find errors

4. Give feedbacks
    * Don't be insulting or judgmental !
    * Be constructive by asking question
    * Honored the good things in the code

For more information you can find these following articles:
- https://www.perforce.com/blog/qac/9-best-practices-for-code-review
- https://betterprogramming.pub/5-practices-to-give-great-code-review-feedback-6b1a9196a716

## References

- Article by Nelis, 04 October 2017, "Why and how do we use pull request?"
    - https://co-learning.eu/2017/10/04/why-and-how-do-we-use-pull-request/
