# MEANStack_App
A MEAN Stack in Devops Flow
This project is created by going through the docs 
URL:
https://docs.microsoft.com/en-us/learn/modules/build-a-web-app-with-mean-on-a-linux-vm/1-introductionhttps://docs.microsoft.com/en-us/learn/modules/build-a-web-app-with-mean-on-a-linux-vm/1-introduction


# Why would I pick MEAN?
All of the components of the MEAN stack are reliable, well-understood, and open source, but so are many other development stacks. Here are some reasons you might choose MEAN over other development stacks.

Your data isn't highly structured

MongoDB is what's called a NoSQL database. A NoSQL database doesn't require data to be structured in a pre-defined way as it would with a relational database like Microsoft SQL Server or MySQL. Instead, MongoDB stores its data in JSON-like documents that don't require the rigid data structures that MySQL or other relational databases require.

# MEAN is well documented

The components of the MEAN stack are all popular right now. Resources for working with MongoDB, Express, AngularJS, and Node.js are easy to find.

# MEAN runs almost anywhere

You can also develop MEAN stack applications from your favorite development environment – whether that's Windows, macOS, or Linux.


# Folder Structure
cd ~
mkdir Books
touch Books/server.js
touch Books/package.json
mkdir Books/app
touch Books/app/model.js
touch Books/app/routes.js
mkdir Books/public
touch Books/public/script.js
touch Books/public/index.html
Here's what's included:

Books – the project's root directory.
server.js defines the entry point to the web application. It loads the required Node.js packages, specifies the port to listen on, and begins listening for incoming HTTP traffic.
package.json provides information about your application, including its name, description, and what Node.js packages your application needs to run.
Books/app – contains code that runs on the server.
model.js defines the database connection and schema. Think of it as the data model for your application.
routes.js handles request routing. For example, it defines GET requests to the /book endpoint by providing the list of all books in the database.
Books/public – contains files that are served directly to the client's browser.
index.html contains the index page. It contains a web form that enables the user to submit information about books. It also displays all books in the database and enables you to delete entries from the database.
script.js contains JavaScript code that runs in your user's browser. It can send requests to the server to list books, add books to the database, and delete books from the database.
