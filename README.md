#cwblog
TO RUN IT USING DOCKER SERVICES, MAKE SURE ALL .ENV FILES IN SERVICES ARE AS 
CONFIGURATION_SETUP="config.ProductionConfig"
THEN YOU CAN RUN PROJECT "sudo bash run.sh"

IF YOU WOULD LIKE TO USE DEVELOPMENT SERVER AND RUN APPLICATION WITHOUT DOCKER SERVICES
GO INTO ALL SERVICE FOLDERS, CHANGE .ENV FILES AS
CONFIGURATION_SETUP="config.DevelopmentConfig"
THEN RUN SERVICES USING TERMINAL "python3 run.py" IN EACH SERVICE FOLDER.


1.Functional requirements
i. Users should be able to sign up and log in using only their university email account.
ii. Users should be able to create a post with or without an image and read all posts on
their home page.
iii. Users should be able to create a comment on an existing post.
iv. Users should be able to delete their own posts/comments.
v. Users should be able to filter out the posts according to a category of their choice.
vi. Users should be able to search the posts according to keywords of their choice.
vii. Users should be able to see the weekly popular posts determined by number of
comments entered.
viii. Users should be able to see email and role of post owner in case contact is necessary.
ix. Users should be able to see their own posts in profile page.
x. Users should be update their own profile information and profile picture.
xi. Users should be authenticated before navigating through the application.
xii. Users should be able to log out and end their session.
2 Non-functional requirements
i. The application should be available to multiple concurrent users at any given time.
ii. The application should handle the load of multiple concurrent users at any given time.
iii. Users should be able to navigate through the application as soon as they are
authenticated.
iv. The application should be compatible with multiple browsers across different
platforms.
v. The design of the frontend should be simple and user-friendly.
vi. The application’s storage should be scalable to meet increasing demand.
vii. The application should be available most of the time and should not experience critical
failures.
