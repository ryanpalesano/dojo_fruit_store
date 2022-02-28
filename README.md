# dojo_fruit_store

Assignment: Dojo Fruit Store
Objectives:
Practice using git (particularly git clone)
Get more comfortable with POST and passing information via a form
Understand how to reference static css or images
Note the importance of making your key assignments/projects look better
Understand why rendering HTML on a URL that received a POST is a bad idea
Start by cloning the repo found here: https://github.com/mchoidojo/dojo_fruit_store

For this assignment, you'll be building a small web app as illustrated below:



Overview Video

Note that the template allows you to use simple if statements and for loops, but is not really a place to do much more than that. If you're wanting to do any calculations, you would want to do this in the routing file (server.py).

Also, remember that all form inputs are received as strings. If you want to work with them as numbers, use the int() method to convert a string to an integer. For example:

"1"+"2"+"3" # returns 123
int("1")+int("2")+int("3") # returns 6 copy
Note for Mac Users:

To get this code to run, you may have to add the following shebang to the top of your file to specify which version of Python to run on.

#!/usr/bin/env python3
copy
You can read about shebangs and how they work here.

Display all the provided images of fruit on the fruits.html page

When the Checkout button is clicked, have the correct information display on the checkout.html page

In the checkout method, add a print statement that says "Charging {{Customer name}} for {{count}} fruits"

While on the checkout screen, hit the refresh button in your browser. Then check your terminal--what do you notice?
