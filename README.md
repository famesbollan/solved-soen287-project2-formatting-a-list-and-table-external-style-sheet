Download Link: https://assignmentchef.com/product/solved-soen287-project2-formatting-a-list-and-table-external-style-sheet
<br>
<strong><u>Question #1:</u></strong><strong> – Formatting a list and table/External style sheet</strong>

Script the webpage in figure 2 using an html file for the format and content and an external CSS file for the presentation. You choose the topic; here are a few ideas: cars, animals, sports, foods ….

Here are the specifications:

<ol>

 <li>The <strong>background</strong> of your page has a repeated image of your choice.</li>

 <li>The <strong>header</strong> must be formatted using the box model.</li>

</ol>

The image to the right illustrates the CSS box model.

To accomplish this use the &lt;div&gt; tag. You can use any color combinations for the border and the background. The color of your header must be the same color as the border of the box model. Set the margin of the box model to be the same as the margin of the table that follows (so they line up nicely). Set the border to be at least 10px and solid. Set the internal padding to be at least 10px. Set the width to a value of your choice other than 100%.

<ol start="3">

 <li>The table must have 3 rows and 2 columns.

  <ol>

   <li>Set the table margin the same as the header margin.</li>

   <li>Set the border of the table to be at least 15px, dashed and a different color from any other colors in the table.</li>

   <li>The 1<sup>st</sup> row is for headings. The background color must be different from any of the other cells in the table, and the text must be any color other than black. Add a padding of at least 10px for the heading cells.</li>

   <li>The cells in rows 2 and 3 must all have a different color background and a different colored border.</li>

   <li>The cells in the column 1 of row 2 and 3 each have an ordered list whose list style is upper roman. Notice that the numbering of the list items in the cell col 1/row 3 starts at 3 (and not 1).</li>

   <li>The cell in row 2/col 2 has an ordered list whose list type is uppercase letters. The 1<sup>st</sup> nested unordered list has bullets that are a 25px x 25px image of your choice and first element of this list has one nested unordered list. The second nested unordered list’s bullets are the default circle. The color of the text in the 2<sup>nd</sup> unordered list is the same as the border of that cell.</li>

   <li>The cell in row 3/col 2 has an ordered list whose list type is armenian numbering. The 1st nested unordered list’s bullets are square. The 2<sup>nd</sup> nested unordered list has bullets that are a 25px x 25px image of your choice, different from the image used in cell Row 2/col 2. The color of the text in the 1st unordered list is the same as the border of that cell.</li>

   <li>The borders on top and bottom sides of the table are dashed and on the left and right sides of the table are dotted.</li>

  </ol></li>

 <li>All style need to be entered in an external CSS.</li>

 <li>Be sure to include your name in the page as well as the sources of your images with links to the pages at a location of your choice.</li>

 <li>Validate your code using the HTML5 validator.</li>

</ol>







<ol>

 <li><em> Figure 2 – Template of page to script for question #1 </em></li>

</ol>




<strong><u>Question #2:</u></strong>

Write a script that prompts the user to enter numerical data until they click “OK” with an empty string input. The program displays the following results:

<ul>

 <li>The total number of values entered.</li>

 <li>The number of odd values entered.</li>

 <li>The number of even values entered.</li>

</ul>

The program should only accept positive integer values and ignore other values. If the user clicks cancel, then it should ignore all values entered and output zeroes for all results.

Here is a sample to illustrate the expected behavior of your program if you enter 10, 15, 14.5, 21, A, -17 and then an empty string:













<strong><u>Question #3:</u></strong>

Write a script in the head section that prompts the user to enter a number and then shows the multiplication table of that numbers. The program displays the resulting values in HTML5 table format including the width = 50% and border = 1, below is one example for the case that user enters 6:




<strong><u>Note:</u></strong>You don’t need to develop any function to calculate the multiplications.




<strong><u>Question #4:</u></strong>

Write a function named <strong><em>a2q4</em></strong> in JavaScript declared in an external file named <strong>a2q4.js</strong>, and included in the html file in the head element. This function takes as a parameter an array of strings called <strong><em>names</em></strong>. This function returns the number of names in the given array that start with either the “pa” or “po” patterns and that do not contain the letter “u” in their names.

The function must be called from inside the body element with these array values:

“party”, “flight”, “cave”, “whole”, “bubble”, “pollution”

The program displays the result as follows:




<strong><em><u>Hint:</u></em></strong>

<ul>

 <li>Use a for loop</li>

 <li>Use the existing method <strong><em>search()</em></strong> to provide you the position of these patterns in the array.</li>

</ul>