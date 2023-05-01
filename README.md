Download Link: https://assignmentchef.com/product/solved-ch231a-assignment5-fibonacci-numbers
<br>
<h1></h1>

<ul>

 <li> Implement all four methods to compute Fibonacci numbers that were discussedin the lecture: (1) naive recursive, (2) bottom up, (3) closed form, and (4) using the matrix representation.</li>

 <li> Sample and measure the running times of all four methods for increasing <em>n</em>. For each method, stop the sampling when the running time exceeds some fixed amount of time (same for all methods). If needed, you may use classes or structs for large numbers (selfwritten or library components). Create a table with your results (max. 1 page). <em>Hint</em>: The ”gap” between samples should increase the larger <em>n </em>gets, e.g. <em>n </em>∈{0<em>,</em>1<em>,</em>2<em>,</em>3<em>,</em>4<em>,</em>5<em>,</em>6<em>,</em>8<em>,</em>10<em>,</em>13<em>,</em>16<em>,</em>20<em>,</em>25<em>,</em>32<em>,</em>40<em>,</em>50<em>,</em>63<em>,…</em>}.</li>

 <li> For the same <em>n</em>, do all methods always return the same Fibonacci number? Explain your answer.</li>

</ul>

<ul>

 <li><strong>Bonus</strong> Plot your results in a line plot, so that the four approaches can be easily compared. Briefly interpret your results. <em>Hint</em>: Use logarithmic scales for your plot.</li>

</ul>

<h1><strong>Problem 5.2 </strong>Divide &amp; Conquer and Solving Recurrences</h1>

Consider the problem of multiplying two large integers <em>a </em>and <em>b </em>with <em>n </em>bits each (they are so large in terms of digits that you cannot store them in any basic data type like long long int or similar). You can assume that addition, substraction, and bit shifting can be done in linear time, i.e., in Θ(<em>n</em>).

<ul>

 <li>Derive the asymptotic time complexity depending on the number of bits <em>n </em>for a brute-force implementation of the multiplication.</li>

 <li> Derive a Divide &amp; Conquer algorithm for the given problem by splitting theproblem into two subproblems. For simplicity you can assume <em>n </em>to be a power of 2.</li>

 <li> Derive a recurrence for the time complexity of the Divide &amp; Conquer algorithmyou developed for subpoint (b).</li>

 <li><strong>Bonus</strong> Solve the recurrence in subpoint (c) using the recursion tree method.</li>

 <li> Validate the solution in subpoint (d) by using the master theorem to solve therecurrence again.</li>

</ul>