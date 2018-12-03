# Interview Practice
Udacity Interview Practice

Q1. What is the most influential book or blog post you’ve read regarding web development?  
Q2. Tell me about a web application you have built. Why did you choose to build it? What did you learn? What challenges did you face and how did you overcome them?  
Q3. Write a function in Python that takes a list of strings and returns a single string that is an HTML unordered list (&lt;ul&gt;...&lt;/ul&gt;) of those strings. You should include a brief explanation of your code. Then, what would you have to consider if the original list was provided by user input?  
Q4. List 2-3 attacks that web applications are vulnerable to. How do these attacks work? How can we prevent those attacks?  
Q5. Here is some starter code for a Flask Web Application. Expand on that and include a route that simulates rolling two dice and returns the result in JSON. You should include a brief explanation of your code.
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
Q6. If you were to start your full-stack developer position today, what would be your goals a year from now?  