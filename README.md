# Social-Feed 

Social-Feed is a foodie dedicated social media page. It looks to encourage foodies to share their ideas, view others content and become up-to-date with the latest foodie news. 


## Goals of the site:

1. See foodie releated posts by content creators.
2. Promote hospitaltiy businesses.
3. Share experiences, ideas and content with other foodies.

## User Experience 

### User Stories 

1. As a Site User I can view a paginated list of posts so that I can select which post I want to view
2. As a Site User I can view a list of posts so that I can select one to read
3. As a Site User I can click on a post so that I can read the full text
4. As a Site User I can view the reccomended posts
6. As a Site User I can register an account so that I can comment and like
7. As a Site Admin I can create, read, update and delete posts so that I can manage my blog content

### Type of Visitors 

1. Business - The site is built for Restaurants, Hotels, Cafes & other hospitlaity businesses to promote their work and network with others.
2. Blogger - Food & drink bloggers will use the site to connect with enthusiasts and businesses to grow their network.
3. Enthusiast - Access to their favourite bloggers, businesses or professionals working in hospitality.

### Wireframes 

[Wireframes were deisgned on Balsamiq](https://balsamiq.com/)

## Features 

### Feature 1 - Account Registration 

ENTER SCREENSHOT 

 Users can click Register to open the Account Registartion form. The form will allow users to enter a Username, Email and Password before confirming the Password and signing up.
 
 Username - Must be unique to Social-Feed. If the Username is not unique, an error message will appear instructing the user to pick a different username. If successful, the Username can be used to Login to it's account.
 
 Email - Emails must follow expected syntax.
 
 Password & Confirmation - Must follow specific password rules and match the Confirmation. If the password is similar to the Username or Email, an error message will appear.
 
### Feature 2 - Login

ENTER SCREENSHOT 

 With an account successfully made, Users can login with their credentials. Firstly, they must either click Login on the navigation bar or click Sign In when prompted during registration.
 
 Username - Users will enter their Username. If incorrect an error message will appear.
 
 Password - Users will enter the correct Password. If incorrect an error message will appear.

### Feature 3 - Home / Social

ENTER SCREENSHOT 

Social is the default home page for all users. Social is the newsfeed, displaying all posts by all users in chronological order. Users can navigate the pages of posts using the page number, next, last or previous buttons available at the bottom. In the next version of Social-Feed, it will only display posts from users that you follow.

### Feature 4 - Posting

ENTER SCREENSHOT 

After registering, users can create their post by clicking Post. Users will then have the posting form available which has to be filled before submitting by clicking the Post button. Posts are used by users to create content such as recipes, events or promoting their business.

### Feature 5 - Posts

ENTER SCREENSHOT 

By clicking the post title a pos
t can be opened. After opening the post, you can view more detail or if you're the post owner, you can update or delete the post. If you're not the owner of the post, you are unable to update or delete the post.

### Feature 6 - Profile 

ENTER SCREENSHOT 

After registering, a profile will be automatically generated. This will display the Username, email and profile picture with an option to update. Additionally, the Profile tab on the navigaion bar will be replaced by the users Username.

### Feature 7 - Profile Pictures 

ENTER SCREENSHOT 

Users will be automatically given a standard Profile Picture when registered. They can change their picture at anytime using the Choose File field to select an image and the Update to see confirmation of a successful image change. The image will be automatically reshaped into a circle.

### Feature 8 - Reccomended Posts

ENTER SCREENSHOT 

The Reccomended Posts or Feed highlights interesting posts to users such as News, Recipes or Promotions. All of the titles are clickable, a new tab will be opened and the user directed to that page. 

### Feature 9 - Sidebar

ENTER SCREENSHOT 

On the left of the screen I've added a Sidebar to provide easier navigation for Users. New pages will be added in the future to improve User Experience when navigating the site.

### Feature 10 - Navigation Bar 

ENTER SCREENSHOT 

The navigation bar presents the page name, Social, Feed, Post, User and Logout. All of the links work as intended and provide simple navigation for users.

### Feature 11 - Comments & Likes

### Feature 12 - Video 


## Features to implement in future versions



## Technologies used

### Frameworks, Libraries & Programs

- HTML5

- CSS

- JavaScript

- Python 3.8

- [GitHub](https://github.com/) is the repository used for projec codes to be pushed from VSCode.

- [VSCode](https://code.visualstudio.com/) was the version control used.

- [Balsamiq](https://balsamiq.com/) used to create user flowmaps during the design process.

- [Heroku](https://dashboard.heroku.com/) used to deploy the app to a live cloud based application.

- [Django 2.1](https://www.djangoproject.com/): 

- [Django Crispy Forms](https://django-crispy-forms.readthedocs.io/en/latest/)

- [Bootstrap](https://getbootstrap.com/)

- [DJ_Database_URL](https://pypi.org/project/dj-database-url/)

- [OS](https://docs.python.org/3/library/os.html)

- [PIL](https://pillow.readthedocs.io/en/stable/reference/Image.html)

- [Sys](https://docs.python.org/3/library/sys.html)



## Testing 

* Tested all key features, responsiveness and links of the site. 

* Automated tests setup for the .py pages. All results came back as anticipated.


## Deployment 

1. On Heroku create an account and log in.
2. Click new and create new app.
3. Choose a unique name for your app, select region and click on Create App
4. Under the Settings click Reveal Config Vars and set IP to 0.0.0.0 and the PORT to 5000
5. Go to the CLI and type $ sudo snap install --classic heroku
6. Type $ heroku login command into the terminal
7. Create requirements.txt ($ sudo pip3 freeze --local > requirements.txt)
8. Create a Procfile ($ echo web: python app.py > Procfile)
9. Go back to Heroku, under Deploy find Existing Git repository and copy the command:$ heroku git:remote -a <app_name> Paste this into the terminal.
10. (If repository was not created already, type:
11. $ cd my-project/
12. $ git init
13. $ heroku git:remote -a <app_name>)
14. Type $ heroku ps:scale web=1 into the terminal.
15. Go back to Heroku, and at Settings copy https://<app_name>.herokuapp.com/
16. In the terminal type git remote add http://<app_name>.herokuapp.com/
17. Type git push -u heroku master
18. In the app dashboard, under Settings click on Reveal Config Vars
19. Set "SECRET_KEY"
20. Once the build is complete, go back to Heroku and click on Open App


## Credits 

 * To ensure my CSS code was formatted correctly, I ran it through a formatter which can be found here: [CSS Code Formatter](https://www.freeformatter.com/css-beautifier.html#ad-output)
 * To ensure my HTML code was formatted correctly, I ran it through a formatter which can be found here: [HTML Code Formatter](https://www.freeformatter.com/html-formatter.html)
 * To ensure my JavaScript code was formatted correctly, I ran it through a formatter which can be found here: [JavaScript Code Formatter](https://beautifier.io/)
 * To ensure my Python code was formatted correctly, I ran it through a PEP8 formatter which can be found here: [Python Formatter](https://codebeautify.org/python-formatter-beautifier) 
 * To create representation images of the site [Am I Responsive](https://ui.dev/amiresponsive)


## Content 

* Any unlinked post content was written by me.
* All accounts created were registered by me.
* [Reccomended Post] Pea Porridge by EADT(https://www.eadt.co.uk/news/pea-porridge-receives-only-michelin-star-in-suffolk-7919860)
* [Reccomended Post] FEED is owned by me.(https://jmjry.github.io/feed/)
* [Reccomended Post] Recipe of the month by BBC(https://www.bbc.co.uk/food/recipes/vegan_thai_green_curry_69640)
* [Reccomended Post] Pub chain opening new pubs by EADT (https://www.eadt.co.uk/news/business/suffolk-pub-chain-snaps-up-two-pubs-8372208)

All content has the sole use for education.


### Code 

* As a go to reasource hub I used [W3S Schools](https://www.w3schools.com/default.asp).
* When stuck on a development issue, I checked [Stackoverflow](https://stackoverflow.com) to see if other developers had the same problems.
* CREDIT CODE 
* CREDIT CODE 
* CREDIT CODE 
* CREDIT CODE 
* To learn about Crispy forms I used the [documentation available](https://django-crispy-forms.readthedocs.io/en/latest/)

