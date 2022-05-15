# Daily Journal
A simple blog website template built with JavaScript, HTML and CSS. This uses Express on node.js to create a stand alone application that allows a user to set up a basic blog or daily journal.

## How to run
  
1. <code>node</code> app.js (or use <code>nodemon</code> for server monitoring)
2. Open up browser to localhost:3000 to pull up the base application.
3. The app interface comes pre populated with 4 pages: Home, About Us, Contact Us and Add Topic.
4. Add journal entries by heading over to localhost:3000/compose or clicking on the Add Topic button. Fill out a title and some post content for your blog.
5. You will then be redirected back to the home page, this time containing your new blog post!
6. Posts displayed on the home page are currently concatenated to 80 characters, but you can click on the content to open up a new page with the full post.
7. If you try to pull up a page that doesn't exists, the application will send a page with the message "Error - Page Not Found".

<img src="https://i.imgur.com/vylGr7o.png">
