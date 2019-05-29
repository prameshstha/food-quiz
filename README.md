# food-quiz
Run "foodquiz.py"
1. “admin.py”, a CLI program that allows the user to add, list, search, view and delete
nutritional information about fast food menu items, and stores the data in a text file.
Develop this program before “foodquiz.py”.
2. “foodquiz.py”, a GUI program that uses the data in the text file to quiz the user about the
nutritional information of the fast food menu items. Develop this program after “admin.py”.

This program allows the user to manage a collection of fast food menu item nutritional information
that is to be stored in a text file named “data.txt”. Those information are stored in “json” format and also used it to read the
JSON data from the file back into Python.Use the  module to write data to the text
file in JSON format form the file back to the Python.

To illustrate the structure of the data, below is an example of the file’s content in JSON format
(which is almost identical to Python):
This example file contains the details of two fast food menu items in a list.

[{
 "name": "Big Mac",
 "calories": 540,
 "fat": 29,
 "protein": 25,
 "carbohydrates": 45,
 "sodium": 1040,
 "cholesterol": 75
 },
 {
 "name": "Whopper",
 "calories": 760,
 "fat": 47,
 "protein": 33,
 "carbohydrates": 53,
 "sodium": 1410,
 "cholesterol": 100
 }]
 
Each of those items is a dictionary consisting of 7 items which have keys of “name”, “calories”, “fat”, “cholesterol”, “sodium”,
“carbohydrates” and “protein”. If this file was to be read into a Python variable named data, then “data[0]” would refer to the
dictionary containing the first menu item (Big Mac), and “data[0]['fat']” would refer to the integer of 29.

The pseudocode for each of your functions clearly describes the parameters that the function
receives and what the function returns back to the program.
It may help to think of the pseudocode of the program as the content of a book, and the
pseudocode of functions as its appendices: It should be possible to read and understand a book
without necessarily reading the appendices, however they are there for further reference if needed.

