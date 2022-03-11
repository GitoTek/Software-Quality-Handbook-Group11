# Coding standards

## Table of content
* [Home](/README.md)
* [Tasks estimation in SCRUM](/readme-content/tasks-estimation.md)
* [Coding standards](/readme-content/coding-standards.md)
    * [Introduction](#introduction)
    * [Repository name and Branch description](#repository-name-and-branch-description)
* [Code reviews](/readme-content/code-reviews.md)
* [The link between the tree topics](/readme-content/topics-link.md)
* [Our project retrospective](/readme-content/project-retrospective.md)


# Introduction

There are coding standards to make it easier for members of the same organization or outsiders to understand each other's work. It is very important to always keep in mind that a good quality code is a code readable by all.

##  Repository name and Branch description

It is very common to find dozens of projects within the same organization. Each project often feeds a larger project, so the question is how to deal with all the projects.<br>
Here is an example of one of my GIT with a multitude of projects<br>
<img src="./pictures/coding-standards/repository-name/gitlab_repo.png"><br>
The nomenclature we have decided upon is as follows : OrganisationName.ProjectType.ProjectName.Specificity

Now that we have the repository I want to talk about branch management.<br>
The one we will use will follow the gitflow system

**Branch description**
* main
    * Default branch
    * Used in production
    * Merge to this branch is only allowed to lead devs and architects
* develop
    * Branch used to merge features
    * Used in develop environment
    * Merge in tis branch is allowed to everyone through a pull request
* release/v<major.minor.revision>
    * Branch used to fix the service before sending it to main
    * Used in QA environment
    * Branch creation is allowed to everyone
* "dev-type"/"workitem-id"-"feature-name"
    * Branch used to develop
    * Not used in any environment

This function is used in a personal way for more information go here : https://jfrog.com/whitepaper/best-practices-structuring-naming-artifactory-repositories/