# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

It effectively translates as many forms. Looking at myself, I am a person, a man, a CodeClan student, a cyclist, a gamer, a son, an uncle, a homeowner ..... etc. I may not need to fulfil all of these forms (roles?) at the same time though.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
As Java is a statically typed language there are certain restrictions. For example, when we create an ArrayList in Java we must define the type of objects that the ArrayList will contain and all of the objects must be of the same type. Using the example of a shop which sells video games, they might want to store all of the games they stock in a single list. But the games for different systems may have different properties. e.g. storage media could be cartridge, optical disc, download code (or floppy drive for old games). Each system might have its own Class (SuperNitendoGames, Playstation4Games etc.) but they might all inherit from a VideoGames super Class which would likely be an abstract class.

3. What can we use to implement polymorphism in Java?
We can implement Polymorphism in Java using a super class and inheriting from it or by using interfaces. The superclass could be an abstract class.

4. How many 'forms' can an object take when using polymorphism?
As many as you want I suppose (or as many as required if the system is designed properly). This is because it can take the forms of all Classes above it in the inheritance chain (it can have only one direct super class, but there could be a further chain of super classes above that one) but interfaces can also be used to treat an object as a different class. When a class implements an interface it gains the type of the interface. A class can have as many interfaces as you want.

5. Give an example of when you could use polymorphism.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
In general, it's when we take the approach of thinking about what an object is made up of. i.e. the object is built up of a number of components. These components are themselves objects.

7. When would you use composition? Provide a simple example in Java.

8. What is/are the advantage(s) of using composition?
compared to inheritance, we can get the behaviours we need from the components. Our object can consist of as many components as required and we can build up our required functionality from the components. In comparison, using inheritance, we can only inherit from one super class as we may end up with a complicated hierarchy of classes and may get ourselves into a situation where we need to override inherited methods to get the functionality we require.

9. When an object is destroyed, what happens to all the objects it is composed of?
Those objects are destroyed also.
