# Tasks estimation in SCRUM

## Table of content
* [Home](/README.md)
* [Tasks estimation in SCRUM](/readme-content/tasks-estimation.md)
    * [How to use those estimations](#how-to-use-those-estimations)
        * [What is the velocity](#what-is-the-velocity)
        * [Representation of this estimate](#representation-of-this-estimate)
* [Coding standards](/readme-content/coding-standards.md)
* [Code reviews](/readme-content/code-reviews.md)
* [The link between the tree topics](/readme-content/topics-link.md)
* [Our project retrospective](/readme-content/project-retrospective.md)


## How to use those estimations

Estimations are key metrics to have data related to the team's performance in a sprint.
And the example we will talk about is the velocity.

### What is the velocity

Velocity represents how fast the team can solve stories in the backlog in different sprints.
This data is used only for the team and is not intended to be shared.
To have a good representation of the velocity, it must be calculated over several sprints.
The results become relevant with 3 completed sprints.


### Representation of this estimate

Here is a representation of the velocity.
This graph represents the planned work and the completed work over 5 sprints.

<img src="./pictures/tasks-estimation/using-estimation/velocity-chart.png" width="600" height="300"><br>


For further information : https://www.workfront.com/project-management/methodologies/agile/velocity

## The different estimation methods - Why do we prefer Fibonacci ?

<br>There are different estimation methods that can be userd for software projects. Here is a list of the ones we prefer:<br>

### The Bucket System Estimation

This method is pretty simple. Each member of the team discuss a number to assign to a task and place it under a "bucket".<br>
It is a nice method for quick estimations for a large number of items.

<img src="./pictures/tasks-estimation/estimation-methods/bucket-theory.jpg" width="600" height="400"><br>


### Three-Point Method

With this method, we define the optimistic (O), pessimist (P) and most likely (ML) effort value to then calculate the average time using a formula.<br>
It is a nice method for teams new to agile.<br>
There are two different formulas:<br>

<img src="./pictures/tasks-estimation/estimation-methods/three-points-method.jpg" width="500" height="300"><br>

### Planning Poker with the Fibonacci sequence

For this method, each team member has cards with numbers from the result of a sequence of the summ of the previous two numbers.<br>
Each team member selects secretly a card and all cards are revealed at the same time.<br>
The card with the most voting is the finalized estimate. If the team can't agree, a meeting is done before a new vote.<br>
If the selected card ha a too high number the task will be splitted in different tasks for which there will be a vote.<br>

<img src="./pictures/tasks-estimation/estimation-methods/planning-poker.jpg" width="600" height="300"><br>

This method is the method we prefer because it is dynamic, it enables to have good estimates, split the too complicated tasks and moreover, everyone is concerned by each tasks.<br>

## References

- Article by Ashish Dhawan, 20 April 2021, "Top 8 Agile Estimation Techniques"
    - https://www.netsolutions.com/insights/how-to-estimate-projects-in-agile/