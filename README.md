# Array_And_object

             ** Arrays **

1. What is the default value of Array for different data types?
Ans : Initialize an array using length
Data Type	Default Values
Long	   0
Float 	 0.0
Double	 0.0
Boolean	 false

2. Can you pass the negative number in Array size?
Ans : Array dimensions cannot have a negative size

3. Where does Array stored in JVM memory ?
Ans : Memory is allocated in Heap are for the Array in Java. In Java reference types are stored in the Heap area.
As arrays are also reference types, (they can be created using the “new” keyword) they are also stored in the Heap area.

4. What are the disadvantages of Array?
Ans : Disadvantages of Arrays in Java
The size of the array cannot be increased or decreased once it is declared—arrays have a fixed size.
Java cannot store heterogeneous data. It can only store a single type of primitives.

5. What is an Anonymous Array in Java ? Give an example?
Ans : An array in Java without any name is known as an anonymous array. It is an array just for creating and using instantly.
 Using an anonymous array, we can pass an array with user values without the referenced variable

 6.What are the different ways to traverse an Array in java?
 Ans : For Loop to Traverse Arrays. We can use iteration with a for loop to visit each element of an array.
 This is called traversing the array. Just start the index at 0 and loop while the index is less than the length of the array.

7. What is the difference between length and length() method Give an Examples?
Ans : length is a field, containing the capacity (NOT the number of elements the array contains at the moment) of arrays.
 length() is a method used by Strings (amongst others), it returns the number of chars in the String; with Strings,
 capacity and number of containing elements (chars) have the same value.


                   ** Objects **

1. How to create an object in java ?
Ans : Java provides five ways to create an object.
Using new Keyword.
Using clone() method.
Using newInstance() method of the Class class.
Using newInstance() method of the Constructor class.
Using Deserialization

2. What is the use of a new keyword in Java ?
Ans : The new keyword in Java is used to create an instance of a class, also known as an object.
The new keyword in Java is used to allocate memory for the object on the heap, the memory space where objects are stored.
 The new keyword in Java calls the constructor of a class to initialize the object's state.

3. What are the different types of variables in Java ?
Ans : There are three different types of variables in Java, we have listed them as follows:
Local Variables.
Instance Variables.
Static Variables.

4. What is the difference between Instance variables and Local variables ?
Ans : Variables declared within a method are local variables. An instance variable is declared inside a class but outside of any method or block.
 Static variables are declared inside a class but outside of a method starting with a keyword static.

5. In which area memory is allocated for instance variable and local variable ?
Ans : Stack is a memory place where the methods and the local variables are stored.
 (variable references either primitive or object references are also stored in the stack).
 Heap is a memory place where the objects and its instance variable are stored.

6. What is method overloading ?
Ans : Method overloading is a feature in Java that allows a programmer to define multiple methods in a class with the same name,
 but with different parameters. What is the difference between Overloading and Overriding? Method Overloading has two or more methods in a class with the same name but different parameters.

  
       
