---
title: Pseudocode & Comments
description: This is a post about Pseudocode
date: 2021-06-16
tags: Coders Guild
layout: layouts/post.njk
---

<h3>About the Lesson</h3>
Pseudocode is used as a learning & reasoning tool. It helps developers understand a problem and draft solutions. Because we don't have to worry about syntax, standards, language or frameworks it allows us to concentrate on the problem without getting caught up in these details that could slow us down. It allows us to work more efficiently.

There is no syntax for writing Pseudocode. However some rules we can use are:

 <ol>
 <li>Capitalise key commands eg. IF number >100 THEN do this</li>
 <li>Write one statement per line</li>
 <li>Use indentation and spacing</li>
 <li>Be specific</li>
 <li>Keep it simple - non techy</li>
 </ol>

<h3>Tasks</h3>
<h4>Task One- Fix Start</h4>
<p>
FUNCTION called fixStart(string)
FOR LOOP to cycle through the string characters in the argument, start from the second character
IF string character == first character
character = "*"

PRINT ba\ \*_le _/

OR

FUNCTION fixStart(inputString)
VARIABLE firstCharacter = GET FIRST CHARACTER OF inputString
VARIABLE newString = REMOVE FIRST CHARACTER of inputString

newString = newString REPLACE CHARACTERS WHERE CHARACTER == firstCharacter WITH "\ \*"
RETURN firstCharacter + newString

</p>

<h4>Task Two- Reading List</h4>
<p>
Keep track of which books you read and which books you want to read!
Create an array of objects, where each object describes a book and has properties for the title (a string), author (a string), and already read (a boolean indicating if you read it yet).
Iterate through the array of books. For each book, log the book title and book author like so: “The Hobbit by J.R.R. Tolkien”.
Now use an if/else statement to change the output depending on whether you read it yet or not. If you read it, log a string like ‘You already read “The Hobbit” by J.R.R. Tolkien’, and if not, log a string like ‘You still need to read “The Lord of the Rings” by J.R.R. Tolkien.’

create ARRAY object eg.

let bookOne{
title: 'Hello World'
author: 'Me'
read: TRUE
}

LOOP THROUGH array and PRINT title + "by" + author

IF read === true
PRINT (`You already read ${title} by ${author}`)
ELSE PRINT (`You still need to read ${title} by ${author}`)

</p>

<h4>Task Three - Recipe</h4>
<p>
Create an object to hold information on your favourite recipes. It should have properties for:
recipeTitle (a string)
servings (a number)
ingredients (an array of strings)
directions (a string)
List all recipes
Create a loop to list all the ingredients.

CREATE array object
faveRecipes[
{
title: 'burger'
servings: 6
ingredients: ['tomato, 'mince', 'burger bun']
directions: 'blah blah blah '
},
{
title: 'pizza'
servings: 6
ingredients: ['tomato, 'cheese', 'flour']
directions: 'blah blah blah '
}
LOOP THROUGH the objects in faveRecipes array
PRINT title of each recipe in the array
LOOP through ingredients array
PRINT ingredients

</p>
