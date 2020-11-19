# Devpost Rails exercise

Let's build a simple To-Do application in Ruby on Rails.

Some of topics we'll be looking at are:

- MVC (routes, migrations, views, etc)
- Simple context-based validations
- Relationships
- Performance

## To-Do application details

### Business rules

- Users can have multiple To-Dos
- To-Dos can have multiple tasks
- Users can be free users or paid users
- Free users can add a maximum of 3 tasks to any given To-Do
- Paid users can add as many tasks as they want to any given To-Do

### Suggested models

#### Todo

- title (maximum of 255 characters)

#### Task

- description (maximum of 1000 characters)
- done (boolean representing the completion state)

#### User

### Pages

- A User page displaying the user name and a list of their To-Dos (don't bother with pagination).
    + For each To-Do, display their title, their state, and their tasks
    + The state of a To-Do is derived from the state of its tasks. A To-Do is done only if all its tasks are done.
    + Each task should display its description, as well as its state (done/not done, ✔/✗, ... up to you)
Keep performance in mind here.

- 
- tasks under them, showing if they are complete or not. This can be accessed by anyone.
A page with a form to create a todo and add tasks for the signed in user
A page with a form to edit a todo and change for the signed in user
    Task do not need to be removed
Pages should show error messages for invalid inputs

Todo attributes: 
Title (255 max)
Done or not

Task attributes:
Title (255 max)

User attributes:
Name
Free or paid
*Users can be added directly to database or console
*User can log in with basic authentication

Testing for 2nd round possibly.
Javascript possibly for 2nd round.


