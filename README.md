# Interview Practice
Udacity Interview Practice

1. <b>What is the most influential book or blog post you’ve read regarding web development?</b>   
&#9758; The most influential book regarding web development is "HTML & CSS: The Complete Reference, Fifth Edition" after read this book I knew little about html elements and css, and know about that "how to create a stylish and awesome website".

2. <b>Tell me about a web application you have built. Why did you choose to build it? What did you learn? What challenges did you face and how did you overcome them?</b>  
&#9758; I built a web Application that "Item Catalog Application". I built the web application because it was a requirement for the Udacity Full Stack project. I learned GoogleSignIn Api, Facebook login, JSON-endpoint and dealing with json file. When i built this project I faced the problem routing in Json-endpoint. I overcome this challenges by going the documentation and stackoverflow.com and finally solve this issue.
    
3. <b>Write a function in Python that takes a list of strings and returns a single string that is an HTML unordered list (&lt;ul&gt;...&lt;/ul&gt;) of those strings. You should include a brief explanation of your code. Then, what would you have to consider if the original list was provided by user input?</b>   
&#9758;
    ```python
    def ulify(elements):
        string = "<ul>\n"
        for s in elements:
            string += "<li>" + str(s) + "</li>\n"
        string += "</ul>"
        return string
    ```
    This code is define with Python list within a function. The function contains a for loop that will iterate through the list an display each element in an unordered list.If the original list was provided by user input. Then we considered the function would have to make sure that the input is a list and it contains strings else we escape any data inputted by the user.
4. <b>List 2-3 attacks that web applications are vulnerable to. How do these attacks work? How can we prevent those attacks?</b>  
    <i><u>Here are two popular attacks:</u></i>
    * SQL injection: SQL Injections are one of the most serious type of attack on the internet. These attacks take advantage of web application vulnerabilities to gain control of databases and all of the information contained within them.  
    &nbsp;&nbsp;&nbsp;&nbsp; For prevent we use SQL parameters, SQL parameters are values that are added to an SQL query at execution time, in a controlled manner.
                     
    * Cookie poisoning: On the Web, cookie poisoning is the modification of a cookie by an attacker to gain unauthorized information about the user for purposes such as identity theft. The attacker may use the information to open new accounts or to gain access to the user's existing accounts.  
    &nbsp;&nbsp;&nbsp;&nbsp;This can be prevented through generating an access token that must match the server’s token in order to complete a request. 
                        
5. <b>Here is some starter code for a Flask Web Application. Expand on that and include a route that simulates rolling two dice and returns the result in JSON. You should include a brief explanation of your code.</b>
   ```python
   from flask import Flask
   app = Flask(__name__)

   import json
   import random

   @app.route('/')
   def hello_world():
     return 'Hello World!'

   if __name__ == '__main__':
     app.debug = True
     app.run()
   ```
   
&#9758;
6. <b>If you were to start your full-stack developer position today, what would be your goals a year from now?</b>