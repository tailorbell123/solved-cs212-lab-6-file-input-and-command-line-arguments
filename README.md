Download Link: https://assignmentchef.com/product/solved-cs212-lab-6-file-input-and-command-line-arguments
<br>
<span class="kksr-muted">Rate this product</span>

File input and command line arguments.

<ol>

 <li>Copy your Lab5Program1.java file to Lab6Progam1.java. Since the file name is different, change the name of the class to Lab6Program1.This program will read integer values from a file, and compute the sum and the average. Change the String array to an integer array in Lab6Program1. Rewrite the inputFromFile method so that it reads from the file given in args[0], converts the string value on each line to an integer and stores it in the next cell of the array.If the name of the input file is lab6input.txt, you would run the program using:<pre>     c:&gt;java Lab5Program1 lab6input.txt</pre>The file lab6input.txt is available on Blackboard.</li>

 <li>Write a method with the following signature:<pre>     public static int sum (int[] myArray, int myArraySize);</pre>This method should return the sum of all the integers in the partially-filled array that was created by inputFromFile. Use a JOptionPane.showMessageDialog to display the sum.</li>

 <li>Write a method with the following signature:<pre>     public static int average (int[] myArray, int myArraySize);</pre>This method should return the average of all the integers in the partially-filled array that was created by inputFromFile. Note that this method can call the method sum. Use a JOptionPane.showMessageDialog to display the sum.The program from Lab 4 initialized the array of words by an assignment statement. Modify the program so that it will read from a file, and the name of the file is given as a command line argument. For example, if the name of the input file is lab5input.txt, you would run the program using:<pre>     c:&gt;java Lab5Program1 lab6input.txt</pre></li>

 <li>Run your program, and show your lab instructor.</li>