# Topics in CS: π-thon
## Building A Trivia Game
### Q1 2023

<img src="https://media0.giphy.com/media/KxzFpLmU5NxtSRgy4Z/200w.gif?cid=6c09b952c5vrqv0w31k9sonuqnyaw2znxjsxhizdtxkxjbcw&ep=v1_gifs_search&rid=200w.gif&ct=g">

## Goals
This lesson has three main goals. Please turn in the following:

1. Triva game (link)
2. Peer review document (linked in 1)
3. Ideation for final project (linked in 1)

First, let's start with some review

<details>
<summary>Review</summary>

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

---

## 🔭 1: Learn 🔭

Today, research the .lower(), .strip(), and .find() to help you generalize the text input. 🛠️

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

---

## ⛏️ 2: Build ⛏️

<details>
<summary>Project 🚀</summary>

In this project, you will have an opportunity to create a trivia game in a topic of your choice. For this project, you must create four trivia questions with some type of response for incorrect or correct answers. You will decide on the theme.

<br>

When creating your Trivia game, you want to make it as accurate as possible for the users to play the game. Using “or” statements will help you add correct answers. Employing methods such as .lower(), .strip(), and .find() to help us and developers to anticipate users' responses by ignoring case, extra spaces on the ends of the string, or finding a specific term in the string. 🎲

We also added some cool tricks🎉

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


## 💡 3: Research Guide 💡

This guide will help you explore different areas of Python to inspire your final project. Today, you will pick ⚄ five ⚄ potential project ideas you would want to follow up on. This should include the main topic (all listed below ), and a description of the project.

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

## 🐝 4 Turning In Work 🐝

<details>
<summary>  🌟 Try a Stretch goal(s) 🌟</summary>
   
💯 Can you add a score to the game? 1 point if the user get the correct answer. 
 0 or -1 points if the user does not get the correct answer. 📊
   
If you add a score to the game, 🐝 buzz feed quiz 🐝 it: depending on the score, print a specific phrase. For instance, if the user gets all four questions correct, print 
“You are amazing! You got all 4 correct!” 🏆

</details>


<details>
<summary>How To Turn IN 🔄</summary>
   
Once done with your code & peer-reviews, email the replit link which will have your other links inside of it as a comments

<pre><code>
   # www.peer_review_doc.com
   # www.my_project_ideas.com
   print("this is an example")
</code></pre>

The peer_review.doc should contain the reviews you gave & recieved. I'd suggest using a table to organize this data.


- You have the entire session and homework to work on the project. It is due for homework by next class.

- Test your project with a classmate to verify that the trivia game works effectively and that you have anticipated the various answers from the user. 

- Remember to copy the Academic Honesty statement into your work and submit your project. 📤

</details>

---

<details>
<summary>Academic Honesty Statement for Computer Science Department 📜</summary>
   
Please submit this assignment with your name and a copy of this text.

<pre><code>
   I have neither given nor received improper aid in the preparation of this computer science assignment or in the completion of this code. Unless properly attributed to others, the work is exclusively my own.

Signed: (type your name here acknowledging this statement) ✍️
</code>
</pre>

</details>
