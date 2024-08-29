# useful-lessons
These are useful python lessons from the Coursera IBM Data Science Professional Certificate


***STRING OPERATIONS***

TABLE OF CONTENTS
What are Strings?
Indexing
Negative Indexing
Slicing
Stride
Concatenate Strings
Escape Sequences
String Manipulation Operations
Quiz on Strings

*Functions:*
- upper() and lower()
REGEX
- import re
- re.search(pattern, text)
- re.split
- findall
- sub

***SETS***
unique collection of objects denoted by {}

*Functions*
- Convert a list to a set: new_set = set(list)
- set.add, set.remove
- confirm if element is in a set: "set_element" in set
- set_intersection = set1 & set2 OR set1.intersection(set2)
- in set2 but not set1: set2.difference(set1)
- set1.union(set2), set1 = issubset(set2), set2 = issuperset(set1)
  

***CLASSES***
Example of a Class:
class Car(object):

    #Constructor
    def __init__(self, max_speed, mileage, color = "white"):
        self.max_speed = max_speed
        self.mileage = mileage
        self.color = color

    #method
    def seating(self, seating_capacity):
        self.seating_capacity = seating_capacity

    def display_properties(self):
        print("Color: ", self.color)
        print("Max Speed: ", self.max_speed)
        print("Mileage: ", self.mileage)
        print("Seating Capacity: ", self.seating_capacity)

car1 = Car(200, 20)
car1.seating(5)
car1.display_properties()

car2 = Car(180, 25)
car2.seating(4)
car2.display_properties()
