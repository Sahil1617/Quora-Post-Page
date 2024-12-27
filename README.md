#Quora Post Page Application 📝✨

Project Overview 🚀
This project is a basic Quora-style post management application built using Node.js and Express. It allows users to perform CRUD (Create, Read, Update, Delete) operations on posts. The application uses EJS for templating and demonstrates key web development concepts, including routing, middleware usage, and dynamic content rendering.

Features 🌟
1.View All Posts 📰: Lists all posts available in the system.
2.Add New Post ➕: Allows users to create new posts with a username and content.
3.View Individual Post 🔍: Displays the details of a specific post.
4.Edit Post ✏️: Enables editing the content of a post.
5.Delete Post 🗑️: Removes a post from the system.

Endpoints 📌
1. View All Posts 📰
Method: GET
Route: /posts
Description: Renders a list of all posts.

2. Create a New Post ➕
Method: GET
Route: /posts/new
Description: Displays a form to create a new post.
Method: POST
Route: /posts
Description: Adds a new post to the list.

3. View a Specific Post 🔍
Method: GET
Route: /posts/:id
Description: Displays details of a specific post.

4. Edit a Post ✏️
Method: GET
Route: /posts/:id/edit
Description: Displays a form to edit a post.
Method: PATCH
Route: /posts/:id
Description: Updates the content of a specific post.

5. Delete a Post 🗑️
Method: DELETE
Route: /posts/:id
Description: Deletes a post from the list.


Dependencies 📦
Express 🌐: Web application framework for Node.js.
EJS 🖼️: Template engine for rendering dynamic views.
UUID 🔑: Generates unique identifiers for posts.
Method-Override ⚙️: Enables HTTP method override for PATCH and DELETE requests.

Future Improvements 🌱
Add a database (e.g., MongoDB or MySQL) to persist posts.
Implement user authentication for secure access 🔒.
Enhance the UI/UX using a front-end framework like Bootstrap 🎨.