# Library Tutorial

This project provides a prototype on creating and managing a library system.
It covers the fundamental concepts of library user management, including adding, updating, deleting, and searching for users.

## Features

- **User Management:** 
  - Register new users
  - Manage user details

## Technologies Used

- **Backend:** Python
- **Database:** SQLite (or any other preferred database)
- **Frontend:** HTML, CSS, JavaScript
- **Frameworks:** Django

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/NiK-2099/library-tutorial.git

2. Install the required dependencies:
   
   Installing Python:
   ```bash
   python -version
   pip --version
   ```
   Creating virtual environment:
   ```bash
   py -m venv myworld
   myworld\Script\activate.bat
   ```
   Install Django:
   ```bash
   py -m pip install Django
   django admin --version
   ```
3. Run the application:
   
   ```bash
   py manage.py runserver
   ```
   Open browser: 127.0.0.1:8000/members/


   ## Usage

   ```bash
   py manage.py shell
   from members.Models import Member
   Member.object.all()
   ```

   1. Adding a new User

   ```bash
   members = Member(firstname = "Jake", lastname = "Python")
   member.save()
   ```


   2. Read data
   ```bash
   Member.objects.all().values()
   ```

    3. Updating Data

    ```bash
    from Members.models import Members
    x = Member.objets.all()[4]        //x is new member at index 4.
    x.firstname = "State"
    x.save()
    ```

    4. Deleting Record
    ```bash
      from members.models import Member
      x = Member.objects.all()[5]
    ```
