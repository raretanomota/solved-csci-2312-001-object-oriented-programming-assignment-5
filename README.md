Download Link: https://assignmentchef.com/product/solved-csci-2312-001-object-oriented-programming-assignment-5
<br>
<strong>Assignment 5</strong>

This assignment will have you read information in from various files, perform exception handling when reading those files, and create a base class and derived classes with virtual functions to read the various files, perform some computations on the inputs as described below, and print the file details.




For this assignment, create a base class called Animal.  It should have as member variables any variables that are contained across all animals in this assignment along with any associated mutator and accessor member functions.  You will create a derived class for each of the following: dog, fish, horse, monkey and lizard.  The member functions to read and output the object’s information will be virtual functions.  Each derived class must contain the additional member variables and member functions needed to include all fields in each input file.




Each input file will contain data about one object; you will not be required to read in information about multiple objects from one file.




I have included one sample file for each of the five animal types.  When I am testing your code, I will be using additional files with errors to see how you have implemented exception handling and gracefully recover.  You may want to create additional files for your testing.




In your main, create an object of each derived class type, read in the object information from the provided files to populate the objects using the derived virtual read function.  For the dog, subtract 10 pounds from its weight; for the horse, add one hand to its height; for the monkey, change its endangered flag (if endangered, make it not endangered; if not endangered, make it endangered).  Finally, use the virtual print function to print to the screen the information about each animal.




Your main should create an object of each of the derived class types, use the readfile function of each object to read the files, call the subtract10 function for the dog, the add1 function for the horse, and the changeEndangered function for the monkey, and then use the overridden print function of each derived class to output the information about each animal.










File contents:

Dog.txt: name, breed, age, color, weight

Fish.txt: name, color, freshwater?, habitat, predator?

Horse.txt: name, color (body color), maneColor, age, height

Monkey.txt: name, color,  age, wild?, home, endangered?

Lizard.txt: name, color, habitat, protected?, weight