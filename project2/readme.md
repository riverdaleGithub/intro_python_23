# Topics in CS: π-thon
## Building A Trivia Game
### Q1 2023

<img src="https://media0.giphy.com/media/KxzFpLmU5NxtSRgy4Z/200w.gif?cid=6c09b952c5vrqv0w31k9sonuqnyaw2znxjsxhizdtxkxjbcw&ep=v1_gifs_search&rid=200w.gif&ct=g">

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

We used the “or” statements to allow for as many possible correct solutions as possible. In the example above either New York City or NYC would work as correct answers. All other answers would be incorrect and fall into the else clause. 🤔


<pre><code>
city = input("What city is Riverdale located in?")
if city == "New York City" or city == "NYC" or city == "Bronx":
   print("correct")
else:
   print("wrong")
</code></pre>

</details>

---

## Learn

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

## Build

<details>
<summary>Project 🚀</summary>

In this project, you will have an opportunity to create a trivia game in a topic of your choice. For this project, you must create four trivia questions with some type of response for incorrect or correct answers. You will decide on the theme. 

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
--- 

## Shine

<details>
<summary>Stretch goals 🌟</summary>
Can you add a score to the game? 1 point if the user get the correct answer. 0 or -1 points if the user does not get the correct answer. 📊
If you add a score to the game, buzz feed quiz it: depending on the score, print a specific phrase. For instance, if the user gets all four questions correct, print “You are amazing! You got all 4 correct!” 🏆
</details>


<details>
<summary>Replit 🔄</summary>
You can find the Python Trivia Project in replit. You have the entire session and homework to work on the project. Test your project with a classmate to verify that the trivia game works effectively and that you have anticipated the various answers from the user. Remember to copy the Academic Honesty statement into your work and submit your project. 📤

</details>
<details>
<summary>Academic Honesty Statement for Computer Science Department 📜</summary>
Please submit this assignment with your name and a copy of this text.
I have neither given nor received improper aid in the preparation of this computer science assignment or in the completion of this code. Unless properly attributed to others, the work is exclusively my own.

Signed: (type your name here acknowledging this statement) ✍️

</details>

Note: The emojis are added for a fun touch, but ensure they align with the tone and context you want to convey.