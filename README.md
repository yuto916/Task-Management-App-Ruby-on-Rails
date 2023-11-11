# README

## Technologies Used
1. Ruby 3.22
2. Ruby on Rails 7.11
3. Bootstrap


## Using the Application
The application manages list of tasks.
A user can create, retrieve, update, and delete tasks.

- To create a student: 
1. Go to "Create Task" page by clicking "Create Task" link in the navbar.
2. Fill out the required text boxes.
3. Click the "Create Task" button.

- To view the list of tasks and update/delete records:
1. Go to "Task List" page.
2. It will list the tasks along with the options to show, edit, and delete each record.


## Features Implemented
### Enhanced UI/UX
- Added navbar with links to each pages.
- Reorganized task list page to make it more visually appealing.
- Added bootstrap classes to the forms generated automatically.

### Authentication
- Used Devise gem to create user model, view, and controller and CRUD for each user.
- User can sign up or sign in, and after successully authenticated, they have access to task pages and pages to edit their profile.