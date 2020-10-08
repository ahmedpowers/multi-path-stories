Approach

The first approach I took was to store data into an array from the form. I made a get request that takes an id parameter and it displays a form. I then made a post method that stores the data in an array. I tested it by console logging my array to see the output.
The second approach was to display a link after the post method is executed. I did this by making a Boolean to see if the form is submitted. 
I then duplicated the form to see multiple forms in action. I tested this by console logging some outputs. 
For going back to start, I made the get request check for a Boolean similar to the post method. After testing I realised the links display at points depending which form is submitted first. I created a position variable inside the array object. Then I was able to check the position and display it in the correct place. 
Lastly I finished off by making html tables for a better layout. 

Improvements 

I opted not to use a DB because I wanted the program to run with minimum configuration, perhaps MongoDB would have been easier due to a table relationship.
Some of the functions can be broken down to more methods for better readability and reusability, such as the forEach function inside the getMethod function. 

To run the app

Extract files into your local computer, run “npm install” on terminal to make sure all dependencies are installed. Then execute the following depending on your machine. 
On MacOS or Linux, run the app with this command:
$ DEBUG=myapp:* npm start
On Windows Command Prompt, use this command:
> set DEBUG=myapp:* & npm start
On Windows PowerShell, use this command:
PS> $env:DEBUG='myapp:*'; npm start

Go to your browser and type 

localhost:8000


