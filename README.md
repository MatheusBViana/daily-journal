# Daily Journal
A simple blog website template built with JavaScript, HTML and CSS. This uses Express on node.js to create a stand alone application that allows a user to set up a basic blog or daily journal.
<img src="https://i.imgur.com/vylGr7o.png">

## How to run
  
1. Download the files or git clone https://github.com/MatheusBViana/daily-journal.git
2. <code>npm i</code> (this should create node_modules folder using dependencies defined in package.json).
3. <code>node</code> app.js (or use <code>nodemon</code> for server monitoring).
4. Open up browser to localhost:3000 to pull up the base application.
5. The app interface comes pre populated with 4 pages: Home, About Us, Contact Us and Add Topic.
6. Add journal entries by heading over to localhost:3000/compose or clicking on the Add Topic button. Fill out a title and some post content for your blog.
7. You will then be redirected back to the home page, this time containing your new blog post!
8. Posts displayed on the home page are currently concatenated to 80 characters, but you can click on the content to open up a new page with the full post.
9. If you try to pull up a page that doesn't exists, the application will send a page with the message "Error - Page Not Found".

