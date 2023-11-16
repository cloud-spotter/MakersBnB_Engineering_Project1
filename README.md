# 🏘️ MakersBnB (Engineering Project I)

A four-day project to build a web application in a team. The goal of the project was to learn effective teamwork, project management, and agile development practices while creating an AirBnB-style property listing and booking platform. 

## 🚀 Project Goals
**Team Collaboration:** Learn to work effectively as part of a team, communicate with your team members, and collaborate to achieve project goals.  

**Project Management:** Learn how to break down projects into manageable tasks and assign them to pairs of developers. Create a Trello board to track the project's progress.  

**Agile Development:** Use agile ceremonies, such as stand-up meetings and retrospectives, to organize our work, improve our processes, and plan our project's development in short sprints.  

**Developer Workflow:** Follow a developer workflow to plan, implement, and peer-review features, ensuring that our code meets quality standards.  

# 💻 Tech Stack
Python: The primary programming language for building the web application.  

Pytest: A testing framework for writing and running unit tests to ensure the reliability of your code.  

Flask: A micro web framework for Python that will be used to build the web application.  

PostgreSQL: A powerful open-source relational database management system used to store and retrieve data for your application.  

# 🏃 Agile Sprints and Ceremonies

We followed an agile development approach with short sprints of two days each. We rotated out team lead each day to ensure that everyone got a chance to lead either a daily stand-up (to discuss progress and address any blockers) or an end-of-sprint retrospective (to reflect on our teamwork and identify areas for improvement).

# Minimum Viable Product (MVP)
We achieved our goal to reach the Minimum Viable Product (MVP) stage by the end of the first sprint. The MVP represented the basic application functionality and allowed for iterative development. We prioritised user stories that contributed to the core functionality and used a disciplined, Test-Driven Development approach to maintain focus on our MVP scope.

# MakersBnB Python Project Seed

This repo contains the seed codebase for the MakersBnB project in Python (using 
Flask and Pytest).

Someone in your team should fork this seed repo to their Github account. 
Everyone in the team should then clone this fork to their local machine to work on it.

## Setup

```shell
# Install dependencies and set up the virtual environment
; pipenv install

# Activate the virtual environment
; pipenv shell

# Install the virtual browser we will use for testing
; playwright install
# If you have problems with the above, contact your coach

# Create a test and development database
; createdb YOUR_PROJECT_NAME
; createdb YOUR_PROJECT_NAME_TEST

# Open lib/database_connection.py and change the database names
; open lib/database_connection.py

# Run the tests (with extra logging)
; pytest -sv

# Run the app
; python app.py

# Now visit http://localhost:5000/index in your browser
```