# Objective

## Key Points

- We want to assess your skills as a generalist software engineer.
- We are looking for people who are able to work on a variety of projects and technologies.

We would like you to build a web application that allows users to search for activities.
The project is meant to be a simple application that you can build in a few hours.
We are not looking for a production-ready application but we will assess your project both in terms of quality (use of best practices/robust architecture) and potential (scalability).

In this repository you will find a list of activities that you can use to build your application (please find the file `activities.json` in the `resources` folder) We want you to seed the Data in any DB of your choice and integrate it with your backend service.

We bootstrapped in advance 2 skeleton applications for the back end and the front end: you will find a skeleton Nest backend application and a Next frontend application.

You can use them to speed up the implementation, or you can start from scratch choosing the technologies you are most familiar with, or you think most appropriate to fulfill the requirements.

# Requirements

- You need to provide a backend application meant to expose an API (REST or GraphQL).
- You need to provide a client application consuming the API exposed by the previous application and implement a UI.
- The client should display the list of activities to the user and allow the user to search, sort and pagination (Please come up with some good frontend designs) for activities by title by
  providing an input field.
  - The fields to be displayed are:
    - title
    - price with currency
    - rating
    - whether it has a special offer or not
    - the activity's supplier name and their location
- You need to decide if the filtering logic should be implemented on the client or on the server.
- Please ensure that the project can be run locally with the given Docker compose file with `docker compose up --build`. Modify, add any dependencies as required
- Add notes on your architectural decisions.
- Please also document any features/improvements you left out in favor of time, preferably with sufficient details on "what, why & how".
- Additionally, make sure any assumptions you made are noted down.


# How to submit your work

Please clone this repository and send us a zip file containing your work.

Also, please avoid bundling `node_modules` or other installed dependency directories in your zip file.

⚠️ **Make sure not to publish your work on a public repository.** ⚠️

We will grade your project after submission and eventually invite you for a remote live interview with our engineers.

# Presentation

- We will ask you to present your work. Please be prepared to present your work, demo it, and explain your choices.
- We will ask clarifying questions about your code and your design choices.
- In addition to the presentation we will ask you to refactor the code, add features, or fix bugs:
  please be prepared to share your screen during the interview and to code live with us.
