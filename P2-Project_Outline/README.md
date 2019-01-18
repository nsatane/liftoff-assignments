# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
 Being foodie I always wanted to have one food-hub where I can find Best recepies from all over the world. This gave me an idea to develop a Food Blog system which will be an open blog for evereone. The person just have to log in and posts his Recepies with details. Each recepie will be catogorized in Veg, Non-Veg , Vegan. Author can post step by step recepie and can upload step by step photos too.
  Readers can find recepies according to Author too and they can rate the post and post their reviews for each Recepies. For this activity too, they should have thei User account on the blog. 
  
  
### Features
Home : 
  1.Show the last 3 posts at the home page, ordered by date (from the most recent).
  2.Show also the last 5 post titles at the home page (as a sidebar) with a link to the post.
  3.Show [Login] and [Register] buttons (when no user is logged in)

User Login/Logout/Register:
  Login:
    1.Login in the blog with existing account (username + password).
    2.Show a success message after login or error message in case of problem.
  Logout:
    1.Register a new user in the MY SQL database (by username + password + full name).
    2.Show a success message after registration or error message in case of problem.
  Register:
    1.Logout the current user.
    2.This [Logout] button is available after successful login only.
    
View / Create / Edit / Delete Posts (CRUD Operations):
  1.Logged in users should be able to view all posts, create new post (by title + content) / edit / delete their own posts.
  2.Posts are displayed in a table (one row for each post). At each row a link [Edit] and [Delete] should be displayed.
  3.Create post shows a form to enter the post data (title + content). After the form submission, the post is created in the database.     4.Implement field validation (non-empty fields are required).
  5.Edit post fills an existing post data in a form and allows it to be edited. After successful form submission, the post is edited.     6.Implement field validation.
  7.Delete post shows the post to be deleted and asks for confirmation.
  
View All Users
  Logged in users should be able to view all users (username + full name) in a table.

Search Recepies:
  1.Readers will be able to search for blog posts containing given text and Author.


### Technologies
  The blog will use:
  1.Java
  2.Spring Framework
  3.Spring MVC 
  4.Thymeleaf template engine
  5.Spring Data JPA
  6.JPA
  7.Hibernate 
  8.MySQL.

### What I'll Have to Learn
New Technologies:
1.JPA
2.Spring Data JPA
3.MySQL
4.Maven 
