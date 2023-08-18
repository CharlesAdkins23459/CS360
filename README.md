# CS360

# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
In my application I was to develop a weight tracking application.  The application allowed users to regsiter for an account, log in, add their goal weight, log, modify and delete weight entries and opt-in for SMS notifications.  The goal of the application was to help users track their weight across time to meet their personal goals.

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
I  had to create a login page, a registration page, a main landing page that displayed a grid of all weight entries, a text message opt-in page and a SQLite database.  The screens were designed to be simple, organized and intuitive, allowing the users to utilize its functionality quickly and with ease.  The placement of buttons and their labels were conspicuously placed and the navigational and interactive elements of the screens were clear.

# How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
I coded in iterations.  I made sure one component worked them added on to it to meet the complexity of the requirements.  This process can be reproduced in a real job, as gathering requirements, designing wireframes and adding functionality is the process to successfully complete an application.

# How did you test to ensure your code was functional? Why is this process important and what did it reveal?
I tested my app by pretending I was a brand new user.  I registered an account, attempted to login, added weight entries and toggled the text message notification functionality.  If I encountered errors or issues, I addressed them on a case by case basis.

# Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
Create the CRUD functionality was difficult.  I wasn't able to get the addition, modify or delete functions to work properly, as expected.  I'd like to go back and see how I can better design my code to make them work.

# In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
Validating a users' credentials was a component that I successfully demonstrated.  The users could create an account or login.  If the email and password were already stored in the DB, then it notified them to login in, if it was a new entry, it added them to the DB.  If the password was incorrect during the login process, it notified the user to correct the error.  If the email and/or password was left empty and a registration or login was attempted, it would notify the user to enter characters into the proper fields.
