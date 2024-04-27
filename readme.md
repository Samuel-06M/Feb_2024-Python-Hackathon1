Random Content Display
This Django application displays a random fact, a random dog image, and a random student's name on a webpage. The name of the student is randomized each time the page is reloaded.


Run the development server using python manage.py runserver.

Access the application at http://localhost:8000/.

Code Explanation
The views.py file contains the index() function that handles the rendering of the webpage.
The function makes requests to external APIs to fetch random facts, a random dog image, and a list of students.
A random student's name is selected and passed to the template for display.
Template
The index.html template displays the fetched data on the webpage.

It dynamically renders the random fact, dog image, and student's name using the Django template language.