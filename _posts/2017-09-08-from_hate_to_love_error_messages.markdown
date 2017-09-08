---
layout: post
title:  "From hate to love error messages :)"
date:   2017-09-08 01:16:28 +0000
---

At the beginning, I quickly passed some small lab tests, so I started thinking that learn to code is easy. 

Then I got a wake-up call when I stuck in a Tic Tac Toe lab for three days. Oh my God! I felt like I was taking crazy pills when I fail too many times. Whenever I run "learn", I got a huge information in the error messages. I read and tried again and again, and again............until I turned off my computer. I hated error messages :(

![](http://cdn-images-1.medium.com/max/1600/1*JC0kpz-kqreE1KLJH-kahg.jpeg)

After taking a break for a while, I came back and read a Reading Error Messages lesson again. I thought that maybe I forgot something in it. 

"READING ERROR MESSAGES

Error messages have 3 parts:

lib/a_name_error.rb:3:in `<main>': undefined local variable or method `hello_world' for main:Object (NameError)

 1) The location of the error, the "where".
 
lib/a_name_error.rb:3:in `<main>':

 2) The description, the "why".

undefined local variable or method `hello_world' for main:Object
The interpreter does the best job it can to tell you what it thinks went wrong.

3) The type of error, the "who".

(NameError)


You've solved games of Clue with less information. This is one of the best parts of programming: debugging and fixing errors. It's like you're a detective solving a crime. The only bad thing is that more often than not, you're also the criminal that caused the error in the first place.
Errors are clues, and reading them is the interpreter telling you what to do to fix the program and move on.

FOUR COMMON ERROR TYPES

NAME ERRORS

NameErrors are caused when a given name is invalid or undefined. Whenever the Ruby interpreter encounters a word it doesn't recognize, it assumes that word is the name of a variable or a method. If that word was never defined as either a variable or a method, it will result in a name error.

SYNTAX ERRORS

Syntax errors are pretty self-explanatory: they're the result of incorrect syntax. Thankfully, they're usually followed by a guess about the location of the error. For instance:
2.times do
  puts "hi"
Will result in:
2: syntax error, unexpected end-of-input, expecting keyword_end
Here, Ruby is saying that on line 2, there is a missing end (every do keyword must be followed by some code and then an end keyword). Always read the full details of syntax errors and look for line numbers, which usually appear at the beginning of the error message.

TYPE ERRORS
When you try and do a mathematical operation on two objects of a different type, you will receive a TypeError. For example if you try and add a string to an integer, Ruby will complain.
1 + "1"
Will produce the following error:
TypeError: String can't be coerced into Fixnum

DIVISION ERRORS
DivisionErrors are caused when a given number is divided by 0.

 Being able to read an error message and fix it, no matter how basic, is a huge step in being a programmer. Get comfortable with broken code. It's totally normal in programming."
 
 
 
 Yes, I looked down on this lesson, read it too fast and then I can not pass a small test. Even though I knew that I had some errors in my code, but I don't know exactly where to focus on. Now, I am familiar with these types of error messages and feel like they are nothing to get rid of. They are really useful because I can get some hints from that, and go through all problems. 
 
 
 Thank you error messages. I fall in love with you every day :D
 
 ![](http://cocolinobr.files.wordpress.com/2012/10/children-love-photo-102.jpg)
 
 




