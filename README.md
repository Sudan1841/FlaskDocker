[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/_PlaFtPA)
# Instructions

This final project involves working in groups of 3 to 5 members on a web app. The goal is to apply key software engineering practices discussed throughout the semester. You and your team will have the freedom to choose what to implement during this final project, as long as the requirements described below are met.

# Requirements 

* The software must be a web app written in Python with the possibility of creating and authenticating users.
* Scrum must be used as the software development methodology. 
* The project must have a vision statement that describes the purpose of the software, the type of problem it aims to solve, and the target audience. 
* A use case diagram must be constructed to provide a high-level view of possible user interactions with the system. 
* You should describe at least six user stories in detail, including their acceptance criteria and point estimates.
* User stories must be referred to as US#1, US#2, etc. 
* At least one user story, not related to user creation or authentication, must be detailed using a sequence diagram.
* A class diagram should be built for the model classes used in the project, including their associations. 
* Create a GitHub repository for the project, following the file structure explained later in this document.
* Add all team members and the [instructor](https://github.com/thyagomota) as collaborators to the project’s GitHub repository.
* There should be two long-lived branches on this project: main (for the stable release) and dev (for the unstable release).
* The stable release is the one that is usually updated at the end of each sprint and includes the user stories that were considered done.
* The unstable release is the one that receives one or more updates during sprints.
* The main branch must be protected and require a code review before a pull request is approved.
* All source code must have a consistent header comment with a brief description and its author(s).
* Code written for this project must comply with the PEP8 code style standard.
* Code will be inspected for best practices related to commenting, naming, formatting, function decomposition, object-oriented programming (OOP), error handling, and more.
* At least one white-box and one black-box test, neither of them related to user creation or authentication, must be provided.
* A test coverage report must be generated using Python’s **coverage** tool.
* The final product must be deployed using Docker containerization technology.
* All requirements needed for the project must be frozen into a **requirements.txt** file.
* The project must have database persistence.
* A database other than SQLite must be used.
* At a minimum, a three-layer software architecture is expected for this project.
* The project should be deployed using Docker Compose (with at least two containers). 

# GitHub Repository Structure 

```
README.md
Dockerfile
docker-compose.yml
requirements.txt
src/
tests/
uml/
```
Use README_TEMPLATE.md for information about the format that you should use for the project's README file. 

Feel free to add other folders as you see fit.

# Project Submission

Commit this **README.md** file with the link of your project's GitHub repository below: 

```
GitHub repository: <URL>
```

# Rubric

+5 Project's README file: mission statement

+5 Project's README file: use case diagram

+5 Project's README file: sequence diagram 

+10 Project's README file: user stories (~ 6 x 1.5)

+5 Project's README file: class diagram for the model classes

+5 GitHub repository organization

+20 Project's README file: development process

+5 Code inspection: PEP8 compliance 

+5 Code inspection: comments, naming, functions, formatting, OOP best practices, error handling, etc.

+10 Code quality, including testing

+5 Project's README file: test coverage report using Python's **coverage**

+5 Project's Deployment

+15 team/self evaluation

Deductions: 

-10 user creation not available/working

-10 user authentication not available/working 

-5 for each user story not completed 

-5 **main** branch does not have consistent commits 

-5 **dev** branch does not have consistent commmits

-5 no burndown chart was created