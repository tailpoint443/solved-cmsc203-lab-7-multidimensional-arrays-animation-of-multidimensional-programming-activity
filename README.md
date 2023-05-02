Download Link: https://assignmentchef.com/product/solved-cmsc203-lab-7-multidimensional-arrays-animation-of-multidimensional-programming-activity
<br>
<strong>Lab Objectives</strong>

 Be able to declare two-dimensional arrays

 Be able to pass two-dimensional arrays to methods

 Be able to return a two-dimensional array from methods

 Be able to process a two-dimensional array in a Java Method

 Be able to work with individual rows and columns in a two-dimensional array




<strong>Introduction</strong>

Writing methods that take multi-dimensional arrays as parameters and/or return multi-dimensional arrays is similar to working with single-dimensional arrays.

The syntax for a method that accepts a two-dimensional array as a parameter is as follows:

<strong>returnType methodName( arrayType[][] arrayParameterName )</strong>

The syntax for a method that returns a two-dimensional array is the following:

<strong>returnArrayType [][] methodName( arrayType [ ][ ] arrayParameterName )</strong>

In this Lab, you will work with a 4-row, 20-column, two-dimensional array of integers. You will write methods that perform the following operations:

<ol>

 <li>Fill the 2-D array with random numbers between 50 and 80.</li>

 <li>Print the array.</li>

 <li>Set every array element of a given row to a specified value. The value is a parameter of a method.</li>

 <li>Find the minimum value in a given column of the array. The column is a parameter of a method.</li>

 <li>Count the number of elements of the array having a specified value. The value is a parameter of a method</li>

</ol>

To visualize how the two-dimensional array is working, your result will animate a bar graph. The

Code for the bar graph is provided to you as <strong>BarChart.java</strong>. So, the framework for this lab will animate your algorithm, which will support you in checking the accuracy of your Java program.




<strong>Lab Instructions</strong>

The source files required to complete this activity has been provided. Copy both the files to a folder in your computer. It is important that both the files stay in the same folder.




Open the TwoDimArrayPractice.java source file. For your convenience, the sample code for task number 1 has been provided under comment 1. inside the <strong>fillValues() method</strong>. You may use this as a model for completing the remaining four tasks. You will need to complete those rest of the four tasks in four other methods. In each one of these four remaining tasks, you will fill in the code for a method that will manipulate an existing array of 4 rows and 20 columns. You need not instantiate the two-dimensional array. That has been done for you.




<strong><u>SAMPLE OUTPUT:</u></strong>

Following shows a sample output from the <strong>fillValues( ) method</strong>.

<strong><u> </u></strong>

<strong>Task #1 Print Array to Console.</strong>

<ol>

 <li>For printing array to console, please make a complete implementation of the method:</li>

</ol>

<strong>public void printArray( )</strong>

This method is under comment 2.

<ol>

 <li>For console printing, elements are separated by a space. The instance variable named <strong>intArray</strong> is the integer array to be printed.</li>

 <li>To animate the algorithm, put this method call as the last element in your inner for loop<strong>animate( row, column );</strong>Here row is the index of the array’s current row, and column is the index of the array’s current column.</li>

</ol>

<strong><u>OUTPUT:</u></strong>

Following shows the screen capture of the required output from the <strong>printArray( ) method</strong>.

<strong>Task #2 Set All Elements in A Row to A Specified Value</strong>

<ol>

 <li>This is under comment 3. Please, implement the <strong>setValues( int value, int row )</strong> method that sets all the elements in the specified row to a specified value.</li>

 <li>The instance variable named <strong>intArray</strong> is the integer array.</li>

 <li>To animate the algorithm, put this method call as the last element in your for loop<strong>animate( row, column );</strong>Here row is the index of the array’s current row and column is the index of the array’s current column.</li>

</ol>

<strong><u>OUTPUT:</u></strong>

Following shows the screen capture of the required output from <strong>setValues(65, 2)</strong>.







<strong>Task #3 Find Minimum Value in the Specified Column</strong>

<ol>

 <li>Implement the method <strong>public int findMinimum( int column ) </strong>that finds the minimum value in the specified column.</li>

 <li>Again, the instance variable named <strong>intArray</strong> is the integer array</li>

 <li>To animate the algorithm, put this method call as the last element in your for loop<strong>animate( row, column );</strong> Here row is the index of the array’s current row and column is the index of the array’s current column</li>

 <li>Notice that a dummy return statement (return 0) is provided at the end of <strong>public int findMinimum( int column ) </strong>method so that the source code will compile in its present state. In this way, you can write and test each method separately, which is known as the step-wise refinement. When you are ready to write the <strong>public int findMinimum( int column ) </strong>method, just replace the dummy return statement with the appropriate return statement for the method.</li>

</ol>

Following shows screen shot of the output for <strong>findMinimum(3)</strong>.

<strong><u>OUTPUT:</u></strong>

<strong> </strong>










<strong>Task #4 Find Frequency of a Given Value in the Array</strong>

<ol>

 <li>Implement the method <strong>public int countFound( int value ) </strong>that counts the number of times a given value is found in the array.</li>

 <li>The instance variable named <strong>intArray</strong> is the integer array.</li>

 <li>To animate the algorithm, put this method call as the last element in your for loop<strong>animate( row, column );</strong> Here row is the index of the array’s current row and column is the index of the array’s current column</li>

 <li>Notice that a dummy return statement (return 0) is provided at the end of <strong>public int countFound( int value ) </strong>method so that the source code will compile in its present state. In this way, you can write and test each method separately using the step-wise refinement. When you are ready to write the <strong>public int countFound( int value ) </strong>method, just replace the dummy return statement with the appropriate return statement for the method.</li>

</ol>

<strong><u>OUTPUT:</u></strong>

Following shows screen capture for <strong>countFound(66)</strong>.

The two .java files (TwoDimArrayPrac.java and BarChart.java) running under the same project will animate your algorithm so that you can visually watch your code work. For this to happen, make sure that your single or nested for loops call the method <em>animate. </em>The arguments that you send to <em>animate</em> are not always the same and the location of the call to animate will differ depending on the task you are coding.




Since the values in the two-dimensional array are randomly generated, the values will be different each time the program runs. To test any of the methods that you have implemented, please click on the appropriate button.