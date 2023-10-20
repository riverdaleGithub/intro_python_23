# 👾Are We Alone?👾

<img src='space.jpeg' width="400" height="400">


The Fermi Paradox questions why are we alon in the universe. Scientists believe that there are billions of stars in our galaxy, many of which could have planets just like Earth. With so many possibilities, it seems likely that there should be other intelligent life out there somewhere. But here's the puzzling part: if there are so many potential alien civilizations, why haven't we found any signs of them? Why is the universe so quiet?

## ⭐ Fermi Paradox ⭐

That's the Fermi Paradox: the contradiction between the high probability of extraterrestrial civilizations existing and our lack of evidence or contact with such civilizations.

Let's create a method for the Fermi Paradox so we may simulate different settings!

<img src="equation.png">


##  👩‍🍳, Functions & Arguments 🍎🥦

Functions and arguments are best buddies! 🤝 The function is like a chef 👩‍🍳, and the arguments are the ingredients. You give the ingredients to the chef, and she makes you a delicious dish! 🍲

<details>
<summary> 👩‍🍳, Functions 👩‍🍳,</summary>
A function is like a mini-program inside your program. It's a way to group code together, give it a name, and reuse it. Imagine you have a magic box 🎁 that does something for you every time you ask. That's a function!

<code><pre>
def greet():
    print("Hello, world!")
</code></pre>


To use (or "call") the function, you just write its name followed by ():

<code><pre>

greet()  # This will print "Hello, world!"
</code></pre>
</details>

<details>
<summary>🍎🥦 What are arguments? 🍎🥦</summary>

Arguments are like special messages 💌 you can send to your function. Think of them as ingredients 🍎🥦 you add to a recipe. The function takes these ingredients and uses them to do something cool!

For example, let's make a function that greets you by your name:

<code><pre>
def greet(name):
    print(f"Hello, {name}!")
</code></pre>
</details>

--- 

## Scope 🌌

<details>
<summary> 🌍What is scope? 🌍</summary>

Scope is like an invisible boundary ⛩️ around your code. Variables (those things that store data, like `x = 5`) live inside these boundaries. Python denotes scope with indents (a tab)

<br>

Imagine you have a toy box 🧸 in your room. The toys inside the box can't be seen or played with by someone in the living room. In the same way, variables inside a function can't be seen or changed by code outside the function.

<pre><code>
def my_function():
    secret_variable = "You can't see me outside the function!"

print(secret_variable)  # This will give an error! 😱
</code></pre>

But don't worry! There are ways to share variables between different parts of your code. But that's a story for another day! 😉

</details>



<details>
<summary>How do functions and arguments work? 🤖</summary>

    You call functions and provide them with arguments

<pre><code>
def make_sandwich(bread, filling):
    print(f"Here's a {filling} sandwich with {bread} bread!")
</code></pre>

Call it with:

<pre><code>
make_sandwich("whole grain", "turkey")  # This will print "Here's a turkey sandwich with whole grain bread!"
</code></pre>

</details>





