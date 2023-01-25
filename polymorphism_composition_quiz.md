# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
It derives from the greek meaning of many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
Where a child class shares the information and behaviour of its parent class (inheritance) whilst also incorporating its own functionality.
*insert amazing java example here*

3. What can we use to implement polymorphism in Java?
absract class and also interfaces

4. How many 'forms' can an object take when using polymorphism?
a class can only exist in one form but more than one class can implement

5. Give an example of when you could use polymorphism.
Creating a parent class of animals which has the method mating call(), whereby each child class (a squirrel for example), will adapt that mating call to its own String. 


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
classes and objects in composition are loosly coupled, enabling the ability to change their component part without breaking the code (or at least trying not to)

7. When would you use composition? Provide a simple example in Java.


8. Give a difference between composition and aggregation?
composition is where the classes are bound together whereas aggregation they are decouped from one another but can communicate through interface abstraction.

9. What is/are the advantage(s) of using composition/aggregation?
composition allows us to pass through functionality from a parent class to its children rather than having to write it out for each one, also helps keep rigid control of the methods and data. Whereas aggregation allows classes to be seperate and not forced to inherit certain traits from respective parent classes. It also allows flexibility where certain classes could be swapped in and out like dependency inversion.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
they will all be destroyed

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
objects which are not part of the parent class and communicate via interface abstraction will not be destroyed.