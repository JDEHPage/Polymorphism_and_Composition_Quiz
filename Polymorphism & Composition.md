
# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

The word Polymorphism is derived from the Greek poly- and -morph meaning "having multiple forms". With reference to programming it means the ability of a programming language to process objects differently depending on their data type or class.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

An example in Java would be to apply a uniting method/s to different classes so they share a common behaviour.

3. What can we use to implement polymorphism in Java?

We can use an interface to implement it.

4. How many 'forms' can an object take when using polymorphism?

Only one at a time but in theory it could have the ability to morph infinitely.

5. Give an example of when you could use polymorphism.

When wanting to group multiple different classes that share a common method into an arraylist.


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

The principle of composition refers to the fact that a class can refer to one or more objects of other classes in its instance variables thus reusing their compositions to gain access to other classes etc.

7. When would you use composition? Provide a simple example in Java.

We would use composition when a class requires other objects to exist. For example a car will require a engine that is a class as well as it has attributes detailed in its instance variables such as fuel requirements.

8. What is/are the advantage(s) of using composition?

Composition allows one to more easily construct complex classes and systems that require multiple levels of interlinked functionality and requirements.

9. When an object is destroyed, what happens to all the objects it is composed of?

They will be destroyed too as they cannot exist without the central unifying object. For example a car may have a engine and a engine can exist by its self but when you destroy the car the concept of the engine being part of the car must cease to exist too as (even if the engine has been removed prior to the cars destruction) there is no longer a car to say the engine is a element of.
