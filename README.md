Download Link: https://assignmentchef.com/product/solved-cs4328-cs5305-operating-systems-programming-assignment-3
<br>
<ol>

 <li>Overview</li>

</ol>

In this project, we are going to write a program that implements several virtual-memory page replacement algorithms<em>. The goal of this project is to compare and assess the impact of these algorithms on the number of page faults incurred across a varying number of physicalmemory page frames available.</em>




<ul>

 <li>Page replacement Algorithms</li>

</ul>

We are going to implement the following page replacement algorithms that we discussed in class:

<ol>

 <li>First-In, First-Out (FIFO)</li>

 <li>Least Recently Used (LRU)</li>

 <li>Optimal (OPT)</li>

</ol>

Implement the algorithms so that the number of page frames available can be passed in as an argument.




<ul>

 <li>Performance Metric</li>

</ul>

We are interested in computing the following metric:

<ul>

 <li>The number of page faults incurred</li>

</ul>




<ol start="2">

 <li>The Process</li>

</ol>

First, generate a random <u>page-reference string</u>, of 100 items, where the virtual page numbers

Page 1 of 2

range from 0 to 49.

Apply the same page-reference string to each algorithm, and record the number of page faults incurred by each algorithm.

Assume that demand paging is used. Structure the program to run so that you can vary the number of physical-memory frames available from 1 to 30.

You will need to run the 3 different algorithms, each for the 30 different values of physicalmemory frames available. This is a total of 90 runs (each using the same 100-page-reference string) with the goal to calculate the number of page faults for each run.




<ol start="3">

 <li>Submission details</li>

</ol>

Submission shall be done using the <strong>Assignments</strong> tool on the Canvas website for this class. Please submit a single zip file including all your files.

Name your file <strong>program3_xxxxx.zip</strong> where xxxxx is your TX State NetID.

Submissions shall include:

<ul>

 <li>the program’s source code, and</li>

 <li>a report containing:

  <ul>

   <li>a brief overview of the design and implementation, o instructions for how to compile and run the program on one of the CS Linux servers, and</li>

   <li>the results of the runs and their interpretation (more below).</li>

  </ul></li>

</ul>




<strong>The report shall include a single plot for the above metric.</strong> The plot on the x-axis will vary the number of frames available, and represent the number of page faults on the y-axis, with a different-color line for each of the <u>three algorithms</u>.

See an example plot on chapter 10, page 404 (Fig. 10.11, “Graph of page faults versus number of frames.”). It’s also on the slide deck for chapter 10, slide 31.

You can write your program in any of these languages (C, C++, Python or Java), however, it is your responsibility to ensure it runs on the CS Linux servers with a command line – nothing graphical (GUI-based) or IDE. Please indicate clearly how to compile and run your program.




<ol start="4">

 <li>Grade breakdown</li>

</ol>

20% of the grade is on developing the correct design and data structures.

30% of the grade is on obtaining the correct results (i.e., the metric and plot) for the algorithms.

20% getting the program to compile and run as expected.

30% of the grade is on the report (overview, explanation of the results, providing the compile and run instructions).

Page 2 of 2