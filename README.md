#Title
Arrays and ArrayLists in Java

#Project Description
Class assignment to show functional differences between arrays and array lists through code examples.

Arrays and ArrayLists are both great tools utilized to store a collection of elements in programming. While similar in function they have unique differences for their respective uses. An array’s size is fixed once it’s declared and can’t be changed afterwards. To declare and initialize an array you would use one of the following syntax variations:

e.g:  double[ ] array = new double[5];
		Or
e.g:  double[] array = {1, 2, 3, 4, 5};

The first variation declares the array and its size. The second variation declares the array and initializes the values within it which provides the size for the array without explicitly declaring it first. To access elements in an array you call the array name and the index of the element within a bracket [] like this:

	e.g:  array[1];

 An ArrayList is dynamic and can increase or decrease in size after its declaration. To declare an ArrayList you can use the following syntax:
	
	E.g: Arraylist<String> list = new Arraylist<String>();

When declaring the array type you use class names which would be uppercase for the first letter like Double, String, Int, etc. The main conceptual differences between an array and ArrayList is that the array size is fixed and the ArrayList isn’t, with an array you have to provide the size by declaring the size or listing the values initially and with an Arraylist you don’t have to specify the size. Also, an array can be multidimensional while Arraylist is single dimensional. Each of them are valuable and provide different unique functionalities that developers can utilize. For the project I’ve created two files, array.java and ArrayLists.java, with example of there specific uses respectively. For my array example I wrote code showing that the only way to add elements to a static array is to copy it to another array that has an increased length. This shows a workaround to increase an array size by copy its elements to another array with a bigger size through a for loop. For my arraylist example the code shows that you can dynamically increase the size of an arraylist with the “.add” method.

#How to Use Project
1. Clone repository: #git clone https://github.com/omarbowen01/Arrays_ArrayLists
2. Install java extension packs: Extension Pack for Java , Debugger for Java
3. Run code.





