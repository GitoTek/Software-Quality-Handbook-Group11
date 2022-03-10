# Code reviews

## Table of content
* [Home](/README.md)
* [Tasks estimation in SCRUM](/readme-content/tasks-estimation.md)
* [Coding standards](/readme-content/coding-standards.md)
* [Code reviews](/readme-content/code-reviews.md)
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

## References

- Article by Nelis, 04 October 2017, "Why and how do we use pull request?"
    - https://co-learning.eu/2017/10/04/why-and-how-do-we-use-pull-request/