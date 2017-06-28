---
title: Working on my blog
layout: post
author: daniel.hutchings
permalink: /working-on-my-blog/
source-id: 1oq5M9pmMye2jJwtP922GexzcJ4vJoV8UEs3F9iu8ndE
published: true
---
In this lesson we did a starter activity, this was to make a program that asks the user their name and tells them how long it is in comparison to the average. This was done by using the input commands and the len function which tells me how long the word is, i then subtracted the average length of a name (which was 5 letters) and then it gave me how many letters bigger or smaller the user's name was compared to the average. This process was then repeated to have the same function for the surname. In the end the code looked something like this:

#Asking the user what their name is

Name1 = input("What is your first name?")

Name2 = input("What is your surname?")

#Greeting the user

print("Hello Mr. "+ Name2)

#Working out how long the user's name is

Lengthname1=int(len(Name1))

Lengthname2=int(len(Name2))

#Giving back the information in a final summary

print("your first name is "+Lengthname1-5+"letters longer than the average name length. Your last name is ")

