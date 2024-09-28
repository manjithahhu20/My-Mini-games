
#  Run JavaScript in Python


In this class, you'll learn how to run JavaScript in python.                                                        


## Prerequisites:

1.  <b> Python Basics </b>
2.  <b> JavaScript Basics </b>
3.  <b> js2py module </b>

---

### 1. What is JavaScript?

JavaScript, often abbreviated as JS, is a programming language that conforms to the ECMAScript specification. JavaScript is high-level, often just-in-time compiled, and multi-paradigm. It has curly-bracket syntax, dynamic typing, prototype-based object-orientation, and first-class functions.

---

## Install Necessary Modules:

Open your [![Anaconda](https://img.shields.io/badge/Anaconda-342B029.svg?&style=flate&logo=anaconda&logoColor=white)](https://www.anaconda.com/products/individual) Prompt <img alt="propmt" src="https://img.shields.io/badge/-__-000000?style=flat-square&logo=Plex&logoColor=white"> and type and run the following command (individually):

 -       pip install js2py  
 
 
**[`js2py`](https://github.com/PiotrDabkowski/Js2Py)** module is used to translator JavaScript to Python & acts as a JavaScript interpreter written in 100% pure Python.

* It translates any valid JavaScript (ECMA Script 5.1) to Python.
* Translation is fully automatic.
* Does not have any dependencies - uses only standard python library.

Limitations:

* strict mode is ignored.
* with statement is not supported.
* Indirect call to eval will is treated as direct call to eval (hence always evals in local scope)

Once Installed now we can import it inside our python code.

---

## Frequently asked questions ❔

### How can I thank you for writing and sharing this tutorial? 🌷

You can <img src="https://img.shields.io/static/v1?label=%E2%AD%90 Star &message=if%20useful&style=style=flat&color=blue" alt="Star Badge"/> and <img src="https://img.shields.io/static/v1?label=%E2%B5%96 Fork &message=if%20useful&style=style=flat&color=blue" alt="Fork Badge"/> Starring and Forking is free for you, but it tells me and other people that it was helpful and you like this tutorial.

Go [**`here`**](https://github.com/milaan9/91_Python_Mini_Projects) if you aren't here already and click ➞ **`✰ Star`** and **`ⵖ Fork`** button in the top right corner. You will be asked to create a GitHub account if you don't already have one.

---

### How can I read this tutorial without an Internet connection? <img alt="GIF" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/hmm.gif" width="20vw" />

1. Go [**`here`**](https://github.com/milaan9/91_Python_Mini_Projects) and click the big green ➞ **`Code`** button in the top right of the page, then click ➞ [**`Download ZIP`**](https://github.com/milaan9/91_Python_Mini_Projects/archive/refs/heads/main.zip).

    ![Download ZIP](https://github.com/milaan9/91_Python_Mini_Projects/blob/main/img/dnld_rep.png)

2. Extract the ZIP and open it. Unfortunately I don't have any more specific instructions because how exactly this is done depends on which operating system you run.
    
3. Launch ipython notebook from the folder which contains the notebooks. Open each one of them
  
    `Kernel > Restart & Clear Output`
    
This will clear all the outputs and now you can understand each statement and learn interactively.

If you have git and you know how to use it, you can also clone the repository instead of downloading a zip and extracting it. An advantage with doing it this way is that you don't need to download the whole tutorial again to get the latest version of it, all you need to do is to pull with git and run ipython notebook again.

