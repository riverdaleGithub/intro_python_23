# Topics in CS: π-thon
## Building A Trivia Game
### Q1 2023

In this project, you will have an opportunity to create a trivia game in a topic of your choice. For this project, you must create 4️⃣ four trivia questions 4️⃣ with some type of response for 😵 incorrect 😵 or 🎉 correct answers 🎉. You will decide on the 🪩 theme 🪩

<img src="https://media0.giphy.com/media/KxzFpLmU5NxtSRgy4Z/200w.gif?cid=6c09b952c5vrqv0w31k9sonuqnyaw2znxjsxhizdtxkxjbcw&ep=v1_gifs_search&rid=200w.gif&ct=g">

## 📖 0: Goals & Review 📖

This lesson has three main goals. Please turn in the following:

1. ⚒️ Triva game with 4 questions (repl.it) ⚒️
2. ↔️ 3 Peer reviews: to & from  (you make doc) ↔️
3. 🏗️ 5 descriptive ideas for final project (you make doc) 🏗️

<details>
<summary>🌪️ Coding Review 🌪️</summary>

In our previous sessions, we have examined how we can use conditional statements to check for true or false. Here is an example:

<pre><code>
city = input("What city is Riverdale located in?")
if city == "New York City" or city == "NYC":
   print("correct")
else:
   print("wrong")
</code></pre>

We used the “or” & "and" statements to allow for as many possible correct solutions as possible. In the example above either New York City or NYC would work as correct answers. All other answers would be incorrect and fall into the else clause. 🤔


<pre><code>
city = input("What city is Riverdale located in?")
name = input("What is your name?")
if city == "New York City" or city == "NYC" or city == "Bronx":
   print("correct")
elif city == "NYC" and name == "Lila":
   print("You must be cool")
else:
   print("wrong")

</code></pre>

</details>

<br>

## 🔭 1: Learn 🔭

First, create a new project called trivia_game. Next, research and try to use the .lower(), .strip(), and .find() to help you learn how to control text input. 🛠️ Have an example of each in your script. Make sure you know Methods and Arguments. This is a huge part of the course.
<details>
   
   <summary>The Actual Lesson</summary>
<details><summary> Methods & Arguments </summary>

<details>
   <summary> 🛠️ Method 🛠️ </summary>

Imagine you have a toy robot 🤖. This robot can do different things like walk 🚶, dance 💃, and sing 🎤. Each of these actions is like a "method" for the robot. In Python, objects (like our robot) can have methods that allow them to do specific tasks. In Python, you can chain methods together


<pre><code>
   # Calling a Method
   robot.dance()
   # Chaining methods
   robot.dance().backfilp()
   answer = input("what is the answer?")
   anwser.find(string.upper())
</code></pre>

Here, `dance` is a method that makes the robot dance.

</details>
<br>
<details> 
   <summary> 🎁 Argument 🎁 </summary>
Now, let's say your robot can also paint 🎨, but it needs to know which color to use. You tell the robot the color by giving it a small box 🎁 with the paint inside. This box is like an "argument" you give to the method.

<pre><code>robot.paint("blue")</code></pre>

Here, `"blue"` is the argument you're giving to the `paint` method to tell the robot which color to use.
</details>
<br>
So, in simple terms:

- A  🛠️ method 🛠️ is an action or task that something can do.
  <br>
- An 🎁 argument 🎁 is extra information you give to help the method do its job.

I hope that helps! 🌟
</details>

<br>

<details>
<summary>
   Learn New Methods
</summary>
   <br>
<details>
    <summary>The lower() method</summary>
        returns a string where all characters are lower case. 📝
        <pre><code>
            city = "New York City"
            print(city.lower()) #prints new york city
        </code></pre>
</details>

<details>
<summary> The strip() method </summary>

removes any leading (spaces at the beginning) and trailing (spaces at the end) characters (space is the default leading character to remove) 🚫

<pre><code>
city = "    New York City    "
print(city.strip()) 
# removes the spaces on either side of the string 
</code></pre>
</details>

<details>
<summary> The find() method </summary>
finds the first occurrence of the specified value. The find() method returns -1 if the value is not found. 🔍
python

<pre><code>
    city = "New York City"
    print(city.find("York")) #prints 4-> the index in which it found York
    # You can even combine these methods. 🔄
</code></pre>
</details>

</details>
</details>

<br>

## ⛏️ 2: Build ⛏️

<details>
<summary>Project 🚀</summary>

When creating your 🪩 Trivia game 🪩, you want to make it as accurate as possible for the users to play the game. Using “or” statements will help you add correct answers. 

<br>

Employing methods such as .lower(), .strip(), and .find() to help us and developers to anticipate users' responses by ignoring case, extra spaces on the ends of the string, or finding a specific term in the string. 🎲
<br>
We also added some cool tricks🎉
<br>

<details>
<summary> Time </summary>
<pre><code>
    time.sleep(0.5) #pause the program for 0.5 seconds
</code></pre>
</details>

<details>
<summary> ASCII Art </summary>

Use <a href='https://www.asciiart.eu/'>ASCII characters to create drawings or designs in your game!</a>

<pre><code>
print("""
+----------------+
|    WELCOME    |
+----------------+
""")
</code></pre>

</details>

Try to chain together .find(), .strip(), and .lower()
</details>
<br>

## 💡 3: Peer Review 💡

Peer-review is the crux of all science
<br>
First, gain and give 3 Peer reviews. In this class, peer-review is simple. Give a 🌟 glow 🌟, 🌿 grow 🌿, and an 🔬 insight 🔬 as a comment. Less than a paragraph is not helpful, more than a few paragraphs is scary.

<details>
   <summary>
   Code Review Example
   </summary>

<pre><code>
   def circle_area(radius):
    pi = 3.14
    return pi * radius * radius
</code></pre>

Peer Review:

<br>

🌟 Glow 🌟:
Great job on keeping the function concise and to the point! The function name circle_area is descriptive, and it's clear what the function is intended to do. Using a clear variable name like radius also makes the code easy to understand.

<br>

🌿 Grow 🌿:
Consider using the built-in math.pi instead of hardcoding the value of pi to 3.14. This would make the calculation more accurate and also show that you're utilizing Python's built-in libraries effectively.

<br>

🔬 Insight 🔬:
Did you know that the formula you used is derived from the integral of r with respect to θ from 0 to 2π in polar coordinates? It's fascinating how math and programming often intersect in such ways!


</details>

<br>

## 🔬 4: Research Guide 🔬

 This guide will help you explore different areas of Python to inspire your final project. Today, you will pick ⚄ five ⚄ potential project ideas    you would want to follow up on. This should include the main topic (all listed below ), and a description of the project.

<details><summary>Example</summary>

Main Topic: Raspberry Pi and Python

<br>

Description:
<br>
I will turn a Raspberry Pi into a live webcam using Python! This project will involve connecting a USB webcam or Pi Camera to a Raspberry Pi and setting up a Python script to stream video over the internet. I can further enhance this by adding features like motion detection, time-lapse photography, or even facial recognition using libraries like OpenCV!
</details>

<details>
   <summary>Main Topics</summary>
  
<details>
<summary>1. Basics of Python</summary>

- <a href="https://docs.python.org/3/">Python Official Documentation</a>
- <a href="https://realpython.com/start-here/">Real Python - Basics</a>
- <a href="https://www.nostarch.com/pythoncrashcourse2e">Python Crash Course</a>

</details>

<details>
<summary>2. Game Development</summary>

- <a href="https://www.pygame.org/wiki/tutorials">Pygame Tutorials</a>
- <a href="http://inventwithpython.com/pygame/">Making Games with Python & Pygame (Book)</a>

</details>

<details>
<summary>3. Web Development</summary>

- <a href="https://flask.palletsprojects.com/">Flask: Micro Web Framework</a>
- <a href="https://www.djangoproject.com/start/">Django: High-level Web Framework</a>

</details>

<details>
<summary>4. Data Visualization</summary>

- <a href="https://matplotlib.org/stable/tutorials/index.html">Matplotlib Tutorials</a>
- <a href="https://seaborn.pydata.org/">Seaborn: Statistical Data Visualization</a>

</details>

<details>
<summary>5. Robotics and Hardware</summary>

- <a href="https://www.raspberrypi.org/documentation/usage/python/">Python with Raspberry Pi</a>
- <a href="https://micropython.org/">MicroPython: Python for Microcontrollers</a>

</details>

<details>
<summary>6. Music and Sound</summary>

- <a href="http://pydub.com/">PyDub: Audio Manipulation with Python</a>
- <a href="https://sonic-pi.net/">Sonic Pi: Code Music</a>

</details>
</details>
<br>

## 🐝 5 Turning In Work 🐝

<details>
<summary>  🌟 Try a Stretch goal(s) 🌟</summary>
   
💯 Can you add a score to the game? 1 point if the user get the correct answer. 0 or -1 points if the user does not get the correct answer. 📊
 
<br>

If you add a score to the game, 🐝 buzz feed quiz 🐝 it: depending on the score, print a specific phrase. For instance, if the user gets all four questions correct, print 

<br>

“You are amazing! You got all 4 correct!” 🏆

</details>


<details>
<summary>How To Turn IN 🔄</summary>
   
Once done with your code & peer-reviews, email the replit link which will have your other links inside of it as a comments

<pre><code>
   # www.peer_review_doc.com
   # www.my_project_ideas.com
   print("this is my repl.it code")
   print("I turn in the repl.it link")
</code></pre>

The peer_review.doc should contain the reviews you gave & recieved. I'd suggest using a table to organize this data.


- You have the entire session and homework to work on the project. It is due for homework by next class.

- Test your project with a classmate to verify that the trivia game works effectively and that you have anticipated the various answers from the user. 

- Remember to copy the Academic Honesty statement into your work and submit your project. 📤

</details>

<br>

## Bee Who You Want to Bee

<details>
<summary>Academic Honesty Statement for Computer Science Department 📜</summary>
   
Please submit this assignment with your name and a copy of this text.

<pre><code>
   I have neither given nor received improper aid in the preparation of this computer science assignment or in the completion of this code. Unless properly attributed to others, the work is exclusively my own.

Signed: (type your name here acknowledging this statement) ✍️
</code></pre>
</details>
