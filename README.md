# Coding4You
Discussion 3: Array vs. Array Lists

In Java, arrays and array lists both let you group related data, but they don’t operate the same once you start using them in a program. An array has a fixed length, so you have to decide its size the moment you decide to create it. That size can’t be changed at a later point in time. Because of this reason arrays are efficient and work well with primitive types such as int or double. They’re simple to use, but their inflexible size can be limiting.

Array lists take a different approach. They are part of the Collections Framework and are designed to adjust while the program runs. Instead of committing to a specific length, you can add/remove items on the fly and the list resizes itself in the background automatically. It acts like a more malliable version of an array, sparing you from dealing with manual resizing. The tradeoff is that it introduces a bit more overhead, and array lists can’t hold primitive values directly you need to use wrapper types like Integer or Double.

I wrote a small Java program in the online IDE provided week one and copy and pasted it to github naming it Difference-Arrays Array Lists to show how these two structures are different in actual code. The example demonstrates that an array must be given a size upfront and stays fixed, while an ArrayList can accept new elements through methods such as .add(). I also added comments throughout the program to clarify why certain operations work on one structure but not the other. After testing the code, I uploaded the project to a new Git Hub repository and included a README that summarizes the main distinctions.

References
Oracle. (n.d.). The Java™ Tutorials: Collections. https://docs.oracle.com/javase/tutorial/collections/
Oracle. (n.d.). Java Arrays. https://docs.oracle.com/javase/tutorial/java/nutsandbolts/arrays.html
