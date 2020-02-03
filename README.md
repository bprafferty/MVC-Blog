# MVC-Blog
Full stack web application powered by Python and the Django framework. Includes SQLite 
database on back end. 

This web app implements the MVC schema to promote scalablity through the creation of
dynamic applications and routes. The front end was designed in HTML with CSS bootstraps,
and repeated code was scaled down by utilizing templates. The data was stored on the back 
end with a SQLite database, which was fashioned to handle updates and data migrations. An 
admin page was created to grant control of the database, so all CRUD operations could be 
done in case it was necessary. Next, the users application was added, which facilitated 
new user registrations, logins, logouts, profiles, profile pictures, and password resets. 
Lastly, the blog application was finished by adding CRUD functions to users on the front 
end, including: posting content, updating existing content, reading other content that 
was posted, and deleting content created with their profile.

To run, first install Python 3.6 or higher and the Django framework dependencies.

To start localhost in your browser, type on commandline: python3 manage.py runserver

