
# Simple Products Management System

## How is the system going to work?

First, create an admin access which will allow many admins to login with their username and password.

Once they are logged in they will be able to do following:

* Add a product
* View the full list of products
* View a product's details
* Edit a product
* Delete a product


## Coding standard

Still, I'm going for Object Oriented Paradigm, because I intend to promote good habits. 

That said I am going to use a simple folder structure, and make a single file for each functionality we have to implement. For example, `index.php` for the home page, `list-products.php` to display the list of products, etc.


## Project structure

The project structure/folder structure actually shows how your code is saved in your hard drive. It also shows how different files/functionalities are co-related. That actually helps you know how you can make each part of your application interaction with other.

The other advantage of this is that it helps make clean and maintainable codes, and all frameworks are very good at that.

For this project I will go simple. The root folder will be called `clickevolue`. Inside it I will be creating an `index.php` file which is going to be the starting point of our application. In the root folder I will also add some folders: `config`, this one will contain the configuration files of the application like database connection, and parameters settings; `includes` folder will contain all common parts to the application's files like headers, footers, etc; a `public` folder to put in all images and css files, though we will not have much to do with them, but it's good to explain it. Also I have added a css refering to `CreativeButtons` to make our project more beautiful.
