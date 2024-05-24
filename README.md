# Disucssion-3

Java allows both arrays and array Lists to serve as data structures for storing collections of elements. However, there are many differences between both methods. 
An Array in Java is a fixed-sized data structure that stores elements of the same type in memory; once the size of the array has been created, then it is impossible to change it. An array has some important functions such as
Fixed Size: Arrays have a fixed size determined at the time of declaration. Once allocated, the size cannot be changed dynamically.
Random Access: Elements in an array can be accessed directly using an index, allowing for fast random access.
Efficient Memory Usage: Arrays are memory-efficient and provide direct access to elements, making them a reliable choice for certain scenarios.
In contrast, An ArrayList is a part of the Java Collection Framework (which is an object that represents a group of objects (such as the classic Vector class) Just like the array, there are benefits to using this method such as:
Dynamic Size: ArrayLists can dynamically resize themselves, allowing for flexible element storage.
Automatic Resizing: When the number of elements exceeds the capacity, ArrayList automatically increases its size internally.
Supports Generics: ArrayLists can hold elements of any type, including primitive types and objects, and support generics for type safety.
Now, let's compare the differences between both methods; Arrays have a fixed size, while ArrayLists have a dynamic size that can expand or minimize as needed. 
Moreover, Arrays can hold both primitive data types and objects directly, while ArrayLists can only hold objects (or boxed versions of primitive types), and since an ArrayList can’t be created for primitive data types, members of ArrayList are always references to objects at different memory locations, that’s why in an ArrayList the actual objects are never stored at contiguous locations. References of the actual objects are stored at contiguous locations.
