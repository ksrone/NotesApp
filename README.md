### Simply NotesApp
----------------
##### The NotesApp application was developed using Django for the backend and React for the frontend. Additionally, user authentication was implemented by JSON Web Tokens.
##### The project was created for educational purposes as an class assignment.
----------------
##### The application allows for registering a new user, logging into a newly created account, as well as adding and deleting notes.
----------------
### Authors:
##### *[@LWiecek12](https://github.com/LWiecek12)
##### *[@ksrone](https://github.com/ksrone)
----------------
### Demo:
#### Explore the functionalities of our application in real-time. 
[![Watch the video](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://vimeo.com/939613632)


### Setting up the environment:
1.**Ensure Python and Django are installed. Install Django using the command**:
 -pip install django
    ```
2. **Project Setup**:*
- Open a terminal.
- Navigate to your project directory using:
  ```
  cd path/to/your/project
  ```
3. **Database Configuration**:
- Ensure the configuration in `settings.py` is correct.
4. **Migrations**:
- Execute Django migrations to update your database:
  ```
  python manage.py migrate
  ```
5. **Running the Server**:
- Start the development server by running:
  ```
  python manage.py runserver
  ```
- Open your browser and go to http://localhost:8000 to see the project running.
6. **Testing**:
- Test the app functionality through different URL paths defined in `urls.py`.
