Understanding the Contents
---------------------------

This repository contains a simple *hello /* web application that runs on your *localhost* on port number *8080*.

The application is written in *Golang* and the code for the same can be found in the file *main.go*.

Another file that can be found is *Dockerfile* that is used to compile and run the application in a *Docker container*.
***

Installing and Starting the Application
----------------------------------------

To run the application, follow the following instructions: -.

After the repository is cloned in your local machine, make sure you are present in the same directory where the repository is cloned.

Type in the command '"docker build --tag=<Any tag name of your choice>"'.

To make sure that the command executed properly, type '"docker image ls"'.

You should see a *docker image* with the name of the tag that you gave in the previous command.

Now to run the application, type '"docker run --p 8080:<A port of your choice> <The tag name you mentioned previously>"'.
***

Using the Application
------------------------

Make sure that the *port number* you mention is same as the port on which you want to run the application.

Open a web browser and type *"localhost:<Port number you mentioned>/<Any text you want to be displayed>"*.

You should see on the browser *Hello "/<Your text entered in the URL"* displayed on the screen.
