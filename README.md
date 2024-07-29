# Find-the-Golden-Star
Find the Golden Star


Instructions
You are going to write a program which will automatically place the Golden STAR in a map and we will find it by marking a spot with an X.

In the starting code, you will find a variable called map.

This map contains a nested list. When map is printed this is what the nested list looks like:

['⬜️', '⬜️', '⬜️'],['⬜️', '⬜️', '⬜️'],['⬜️', '⬜️', '⬜️']
In the starting code, we have create function to format nested list to print out like this.

⬜️ ️⬜️ ️⬜️
⬜️ ️⬜️ ️⬜️
⬜️ ️⬜️ ️⬜️
This is to try and simulate the coordinates on a real map.



Your job is to write a program that places golden star in the map in a random place and allows you to mark a square on the map using a two-digit system. The first digit is the vertical column number and the second digit is the horizontal row number. e.g.:

First your program prints out the initial version of map and then it must take the user input and convert it to a usable format.

Next, you need to use it to update your nested list with an "x".

Example Input 1
row 2, column 3 would be entered as:

This is our initial map...
⬜️ ️⬜️ ️⬜️
⬜️ ️⬜️ ️⬜️
⬜️ ️⬜️ ️⬜️
What do you think: where is the Golden Star in the map? 23
Example Output 1
Unfortunatly you could find it 🙁
⭐️ ️⬜️ ️⬜️
⬜️ ️⬜️ ️🆇
⬜️ ⬜️ ⬜️
Example Input 2
row 1, column 1 would be entered as:

This is our initial map...
⬜️ ️⬜️ ️⬜️
⬜️ ️⬜️ ️⬜️
⬜️ ️⬜️ ️⬜️
What do you think: where is the Golden Star in the map? 11
Example Output 2
Congratulations!!! You have found the Golden STAR!
⭐️ ⬜️ ️⬜️
⬜️ ️⬜️ ⬜️
⬜️ ️⬜️ ️⬜️
Hint
Remember that Lists start at index 0!
map is just a variable that contains a nested list. It's not related to the map function in Python.
