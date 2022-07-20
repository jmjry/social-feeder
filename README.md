# Social-Feed 

Social-Feed is a foodie dedicated social media page. It looks to encourage foodies to share their ideas, view others content and become up-to-date with the latest foodie news. 


## Goals of the site:

1. See foodie releated posts by content creators.
2. Promote hospitaltiy businesses.
3. Share experiences, ideas and content with other foodies.

## User Experience 

### User Stories 

1. As a Site User I can view a ist of posts so that I can select which post I want to view
2. As a Site User I can view a list of posts so that I can select one to read
3. As a Site User I can click on a post so that I can read the full text
4. As a Site User I can interact with posts
6. As a Site User I can register an account so that I can comment and like
7. As a Site Admin I can create, read, update and delete posts so that I can manage my blog content]\

To manage my User Stories I created a [Trello board](https://trello.com/en). Trello is a web-based Kanban-style application popular with Agile devleopment.

### Type of Visitors 

1. Business - The site is built for Restaurants, Hotels, Cafes & other hospitlaity businesses to promote their work and network with others.
2. Blogger - Food & drink bloggers will use the site to connect with enthusiasts and businesses to grow their network.
3. Enthusiast - Access to their favourite bloggers, businesses or professionals working in hospitality.

### Wireframes 

[Wireframes were deisgned on Balsamiq](https://balsamiq.com/)

[PP4 1 .pdf](https://github.com/jmjry/social-feeder/files/9154785/PP4.1.pdf)


## Features 

### Feature 1 - Account Registration 

![sign up](https://user-images.githubusercontent.com/86608354/180088638-535fc104-ccc6-4e26-9cd7-05d5a5b133b3.png)

 Users can click Register to open the Account Registartion form. The form will allow users to enter a Username, Email and Password before confirming the Password and signing up.
 
 Username - Must be unique to Social-Feed. If the Username is not unique, an error message will appear instructing the user to pick a different username. If successful, the Username can be used to Login to it's account.
 
 Email - Emails must follow expected syntax.
 
 Password & Confirmation - Must follow specific password rules and match the Confirmation. If the password is similar to the Username or Email, an error message will appear.
 
### Feature 2 - Login

![sign in](https://user-images.githubusercontent.com/86608354/180088665-8e1c694d-2750-43ef-9caa-479f5e08fb62.png)
![Are you sure you want to sign out](https://user-images.githubusercontent.com/86608354/180089120-821461a0-55dc-44dd-9767-66e9bbfe78c7.png)

 With an account successfully made, Users can login with their credentials. Firstly, they must either click Login on the navigation bar or click Sign In when prompted during registration.
 
 Username - Users will enter their Username. If incorrect an error message will appear.
 
 Password - Users will enter the correct Password. If incorrect an error message will appear.

### Feature 3 - Home / Social

![Home](https://user-images.githubusercontent.com/86608354/180088691-0221e3f0-b795-43aa-9171-12ade9c79cf1.png)

Social is the default home page for all users. Social is the newsfeed, displaying all posts by all users in chronological order. Users can navigate the pages of posts using the page number, next, last or previous buttons available at the bottom. In the next version of Social-Feed, it will only display posts from users that you follow.

### Feature 4 - Posting

After registering, users can create their post by clicking Post. Users will then have the posting form available which has to be filled before submitting by clicking the Post button. Posts are used by users to create content such as recipes, events or promoting their business.

### Feature 5 - Posts

![Post](https://user-images.githubusercontent.com/86608354/180088743-c9216a60-fcef-415c-8778-2407f4b298f5.png)

By clicking the post title a pos
t can be opened. After opening the post, you can view more detail or if you're the post owner, you can update or delete the post. If you're not the owner of the post, you are unable to update or delete the post.

### Feature 6 - Profile 

![Profile](https://user-images.githubusercontent.com/86608354/180088769-853a9078-2db6-4fda-a2fc-05d95c3bf895.png)

After registering, a profile will be automatically generated. This will display the Username, email and profile picture with an option to update. Additionally, the Profile tab on the navigaion bar will be replaced by the users Username.

### Feature 7 - Profile Pictures 

![avatar](https://user-images.githubusercontent.com/86608354/180088785-c953f051-ceb0-4268-bd95-fee5d213f22c.png)

Users will be automatically given a standard Profile Picture when registered. They can change their picture at anytime using the Choose File field to select an image and the Update to see confirmation of a successful image change. The image will be automatically reshaped into a circle.


### Feature 8 - Navigation Bar 

![NAV](https://user-images.githubusercontent.com/86608354/180088845-ea735a9e-fac7-4c19-a444-23a4d8bdd55d.png)

The navigation bar presents a way for users to navigate the site.

### Feature 9 - Comments

![Comment](https://user-images.githubusercontent.com/86608354/180088969-717c8449-5139-46bd-ab41-9307bec81c14.png)

Users can interact with each other by leaving comments on their posts.

### Feature 10 - Likes

![Like](https://user-images.githubusercontent.com/86608354/180088982-67658b99-bd59-4d9f-bc43-e15959008700.png)

Users can like posts which will appear in the feed.

### Feature 11 - Invite User 

![Invites](https://user-images.githubusercontent.com/86608354/180089179-1e0808ce-3449-475b-b9d1-c0dd77722da9.png)
![Request](https://user-images.githubusercontent.com/86608354/180089188-2b3d2739-0471-431b-be85-d56a9d96b37c.png)

You can invite other users to add you as a friend. Invites will appear in the box and when clicked the profile and information of the user who added you will appear.


## Features to implement in future versions

### Video 

## Data Model

### Relationships 

- I planned the logic to ensure a user could register. login and generate their own profile. They can then search for other users and add them to their friends list. This data model required deep thought to ensure the process was seamless and that the user experience was a smooth transaction with minimal actions required.

### Posts 

#### Comments 

- Users comments will be stored with the post commented on. This was purposely designed so that useres could interact with friends or other users on posts that were interesting. 

#### Likes 

- Users likes will be stored with the post liked. This will increase based on the amount of likes the post recieves. Total likes are stored in a users profile.

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

- [Django-allauth](https://django-allauth.readthedocs.io/en/latest/installation.html)



## Testing 

* Tested all key features, responsiveness and links of the site. 

<img width="629" alt="Screenshot 2022-07-20 at 23 01 33" src="https://user-images.githubusercontent.com/86608354/180090155-23d4b447-295d-4fd3-8488-717c6df7d77f.png">

* Automated tests passed.

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

## Todo list

### Known Bugs

- Opening a profile does not always work. I need to rework my relationship functions and ensure you can open friends profiles and view all their information. 
- Sometimes the profile picture does not automatically generate.

### User Experience 

- New layout which is more branded (unique pictures, graphics etc)
- Implement Cloudinary which was installed


## Credits 

 * To ensure my CSS code was formatted correctly, I ran it through a formatter which can be found here: [CSS Code Formatter](https://www.freeformatter.com/css-beautifier.html#ad-output)
 * To ensure my HTML code was formatted correctly, I ran it through a formatter which can be found here: [HTML Code Formatter](https://www.freeformatter.com/html-formatter.html)
 * To ensure my JavaScript code was formatted correctly, I ran it through a formatter which can be found here: [JavaScript Code Formatter](https://beautifier.io/)
 * To ensure my Python code was formatted correctly, I ran it through a PEP8 formatter which can be found here: [Python Formatter](https://codebeautify.org/python-formatter-beautifier) 


## Content 

* Any unlinked post content was written by me.
* All accounts created were registered by me.
* [Pea Porridge by EADT](https://www.eadt.co.uk/news/pea-porridge-receives-only-michelin-star-in-suffolk-7919860)
* [FEED is owned by me.](https://jmjry.github.io/feed/)
* [Recipe of the month by BBC](https://www.bbc.co.uk/food/recipes/vegan_thai_green_curry_69640)

All content has the sole use for education.

### Code 

* As a go to reasource hub I used [W3S Schools](https://www.w3schools.com/default.asp).
* When stuck on a development issue, I checked [Stackoverflow](https://stackoverflow.com) to see if other developers had the same problems.
