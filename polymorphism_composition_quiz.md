# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

- A self-made class can be more than one class - of either its interface or superclass type.   

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

- We can group different classes into data structures (i.e. arrays) that only specify one data-type.

3. What can we use to implement polymorphism in Java?

- Inheritance and interfaces.

4. How many 'forms' can an object take when using polymorphism?

- Unlimited.

5. Give an example of when you could use polymorphism.

- You want to return an ArrayList of of objects of different classes. Polymorphic objects have the ability to conveniently morph
'upwards' into one class they all belong to. Sometimes we use casting to return them to their 'sub' or lower class.  

# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

- Class A relies on the existence of class B because it is composed of it somewhere in its constructor.  

7. When would you use composition? Provide a simple example in Java.

- Class A might want properties that are actually instances of a Class B that have their own unique properties and methods.
Potentially, instances of class B have the chance to interact with the methods and properties of Class A and maybe other classes.

8. What is/are the advantage(s) of using composition?

- It might be more effecient and flexible than inheritance. More effecient because a sub class inherits all properties and methods
from its super; a 'has' class can choose what instances of the 'belong' class it wants. Moreover, a sub class can only inherit one
super; a 'has' class can import as many instances of other 'belong' classes as it wants.

9. When an object is destroyed, what happens to all the objects it is composed of?

- If class A is composed of class B, when class B is destroyed, class A can't exist. When class A is destroyed, class B can still exist. 
