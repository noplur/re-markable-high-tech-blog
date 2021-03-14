# The Re-Markable High-Tech Blog
## by Aaron Rosenblatt

### I wrote code to build a CMS-style blog site where developers can publish their blog posts and comment on other developers’ posts as well. I built the site completely from scratch following the Model View Controller paradigm in its architectural structure, using Handlebars.js as the template language, Sequelize as the Object–Relational Map, and the Express-Session NPM package for authentication.

### When the user visits the site, the homepage will be displayed. The homepage includes the existing blog posts and navigation links for the homepage, the dashboard and an option log in. The log in option allows a link to sign up or sign in. Choosing sign up prompts a form to create a username and password. The credentials are saved and the user is logged into the site. After logging out the user can return at a later time and choose to sign in by entering the username and password. When logged in, if the user navigates to the homepage the existing blog posts include the post's title, content, creator's username and date created. Clicking on a post allows the user to enter a comment and submit the comment. The post will then be updated and comment will be saved along with the comment creator’s username and date created. The dashboard presents the posts created by the specific user logged in and the option to create a new post. The button to add a new blog post prompts the user to enter the title and contents for the blog post and user is taken back to dashboard. Clicking on an existing post in dashboard allows the user to update or delete that post and the user is taken back to dashboard. Clicking on the logout button will prompt the user to log out of the site. The user will also automatically be signed out of the site by idling on the page for more than 10 minutes.

### The Re-Markable High-Tech Blog app can be viewed here: https://rosenblatt-hi-tek-blog.herokuapp.com/

### The GitHub repository for The Re-Markable High-Tech Blog can be viewed here: https://github.com/noplur/re-markable-high-tech-blog

### Here is a screenshot of a sample from The Re-Markable High-Tech Blog:
### ![](./images/re-markable-high-tech-blog.jpg)