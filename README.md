These files with extension ".dat" can be read by some programs in my books about computer graphics, the latest of which is
Computer Graphics Programming in C++/Qt, published by Amazon in October 2029.
Some of these files contain a section at the end, starting with the word "Groups". 
This is then followed by sequences of vertex numbers, each ending with an exclamation mark (!).
We call the set of numbers in such a sequence a "group". It contains the vertex numbers of a part of the combined object.
For example, the file puzzle3a.dat is about a 3D puzzle that consists of three parts, so there a three groups.
The program Edit3D ignores this Group section but you can use the "Select vertices" command of the Edit menu
to select the vertices of a group and then apply operations such as Shift and Rotate on the selected vertices, 
that is, on one of the three parts of this puzzle.
