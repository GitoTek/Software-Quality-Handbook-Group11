# Code reviews

## Table of content
* [Home](/README.md)
* [Tasks estimation in SCRUM](/readme-content/tasks-estimation.md)
* [Coding standards](/readme-content/coding-standards.md)
* [Code reviews](/readme-content/code-reviews.md)
    * [Pull request](#pull-request)
        * [ow to make a good PR](#how-to-make-a-good-pr)
* [The link between the tree topics](/readme-content/topics-link.md)
* [Our project retrospective](/readme-content/project-retrospective.md)


## Pull request

Every merge to develop MUST go through a PR <br>
A lead dev or an architect will review your code and make some comment to it. <br>
The purpose of it is to keep the code quality as good as possible.

### How to make a good PR

1. Create a PR
    *  Go through your gitlab project > Merge Request > New Merge Request
    * Select your source branch and the branch develop.

2. PR Content
    * Set an explicit title
    * Write a description explaining :
        1. What’s the purpose of the code you are asking to merge
        2. The operations if the code is complex
        3. The choices you made in term of code architecture, technology, … if you made one
        4. Any information you thing the reviewer must know about your code

3. Reviewers and Assignee
    * Feel free to assign it to the most competent person for this PR.

4. erge options
    * Always delete your branch, it avoid complex git manipulations
    * Do not check “Squash commit“ unless you have done tons of useless commits

If you have pipelines error, your PR won’t be approved except for specific reasons that you have to explain in the description.

For further information : https://betterprogramming.pub/how-to-make-a-perfect-pull-request-3578fb4c112
