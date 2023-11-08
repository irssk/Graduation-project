# Graduation project
A graduation project application where users can join or create chat rooms to communicate. Developed with Django 4.1 and Django Channels.

<p id ="top" align="center">
  <img width="960" alt="homepage" src="https://user-images.githubusercontent.com/59337853/210165087-b135a862-da10-4123-8d7d-d20668a3ca97.png">  
</p>

# Table of contents
- [Technologies_and_Tech_stack_involved](#Technologies_and_Tech_stack_involved)
  * [Chat_room](#Chat_room)
  * [Conversation_room](#Conversation_room)
  * [Multi_users](#Multi_users)
  * [Login_Page](#Login_Page)
  * [Sign_up_page](#Sign_up_page)
- [Installation](#Installation)
  * [application_setup](#application_setup)

## Technologies_and_Tech_stack_involved
- Python
- Django (4.1)
- Django Channels
- light weight sqlite database

### Chat_room
Here users can create or join an existing chat room.
<p align="center">
  <img width="960" alt="chat room" src="https://user-images.githubusercontent.com/59337853/210165259-3cbcec26-3810-4f98-87c9-f37247996ca2.png">
</p>

### Conversation_room
The page displays the number of people present in the room, as well as the conversation. 
<p align="center">
  <img width="960" alt="conversation" src="https://user-images.githubusercontent.com/59337853/210165314-24e8fb32-adbd-466b-b42c-e73cace5dec6.png">
</p>

### Multi_users
Multiple users can join the room once logged in.

### Login_Page
<p align="center">
  <img width="958" alt="login" src="https://user-images.githubusercontent.com/59337853/210165347-cce761c7-a867-42a0-b6d8-f9fee7c30a54.png">
</p>

### Sign_up_page
<p align="center">
  <img width="960" alt="sign up" src="https://user-images.githubusercontent.com/59337853/210165353-00f21a00-b6ab-4c3b-af10-53e9c9b4a535.png">
</p>

## Installation
after downloading/cloning the repository code, follow below steps:

### application_setup

- create your virtual environment
`python -m venv myenv` 

- activate your virtual environment
`myenv\scripts\activate`

- install project dependencies
`pip install -U channels["daphne"] django crispy_bootstrap5`

- make your first migration
`python manage.py makemigrations`

- migrate your changes
`python manage.py migrate`

- run the server
`python manage.py runserver`

### All set :)