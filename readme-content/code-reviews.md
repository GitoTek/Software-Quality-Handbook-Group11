# Code reviews

## Table of content
* [Home](/README.md)
* [Tasks estimation in SCRUM](/readme-content/tasks-estimation.md)
* [Coding standards](/readme-content/coding-standards.md)
* [Code reviews](/readme-content/code-reviews.md)
    * [Closing a pull request](#closing-a-pull-request-br)
        * [When to close a pull request](#when-to-close-a-pull-requestbr)
        * [How to close a pull request](#how-to-close-a-pull-requestbr)
* [The link between the tree topics](/readme-content/topics-link.md)
* [Our project retrospective](/readme-content/project-retrospective.md)


## Closing a pull request <br>

Created pull request are not always accepted and merged as they don't meet requirements.<br>
In this section, we will discuss the best habits for closing a pull request.<br>

### When to close a pull request<br>

There are different scenarios for closing a pull request:<br>

* <b>The feature/fix is uncomplete</b><br>
In this situation, you must discuss in the description/comments with the developer(s) why the pull request has been refused, according to the feature plan, and why it must be fixed before asking a new one.
* <b>The code does not pass continuous integration tests</b><br>
In this situation, you must pinpoint the tests that encountered a failure and ask for a new pull request with successful tests.
* <b>The project does not accept any further changes</b><br>
In this situation, you can close the pull request, indiciting that the project refuses future changes (the README.md must indicate this too).
* <b>Virulent debate on accepting/refusing the pull request</b><br>
If a developper does not recognize its mistakes and keep discussing about it, you must close the pull request in order to keep a good work atmoshpere, and wait for a new one with the discussed fixes.

### How to close a pull request<br>

It is pretty simple to close a pull request. Using github for example, you just have to click on <b>"Close pull request"</b> at the bottom of the pull request, after leaving a comment detailling the reasons.<br>

<img src="./pictures/code-reviews/close-a-pull-request/pull-request-close.png"><br><br>

## References

- Article by Mike McQuaid, 15 March 2016, "Kindly Closing Pull Requests"
    - https://github.blog/2016-03-15-kindly-closing-pull-requests/
- Article by Github, Unknown date, "Closing a pull request"
    - https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/closing-a-pull-request