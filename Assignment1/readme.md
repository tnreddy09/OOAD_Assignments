4. Write a simple OO program that implements the Shape example discussed in Lecture 2 on slide 6 but using an OO design rather than the presented functional decomposition solution. Your program should simply print out (to the console) the number of shapes in the “database” and then ask each shape to “display itself” which will also cause a line of output to be generated to the console, one for each shape. The word “database” is in quotes in the previous sentence because you should not actually use a database to write this program. It is perfectly acceptable for your main program to create a collection of shapes before moving on to sorting that collection and displaying the shapes. Your program should support circles, triangles, and squares but should use polymorphism so that the main program doesn't know the type of shape it is dealing with, but instead treats shapes uniformly (similar to the example program in Lecture 2 that involved different types of students). You may use any OO language that you'd like to write this program, just be aware that the grader may have to meet with you if you use a language that they don’t have access to.

Solution:

1.In the design there is a Base Class called "Shape", from which all the Classes of different Shapes gets derived.
2.Base class "Shape" is a abstract class with protected variables "shapeName","Area" and abstract methods, "displayShape()", "setArea()", "getArea()".
3.Derived Shape Classes have their boundary parameters and implements methods inherited from Base class "Shape".
4.In the Driver Class, we have created a ArrayList of Shapes and assigned all the Shape objects to it.
5.Area of each shape is calculated based on its boundary parameters. 
6.Sorting is done based on the area of the shapes.
7."displayShape()" is called on the ArrayList of Objects.
