Download Link: https://assignmentchef.com/product/solved-big-homework-2-data-structures-and-algorithms-linked-lists-graphs
<br>
! Observation: The linked list and graph used will be in headers (.h) and will be generic classes (template) – the implementation from the course, at which you can add other methods, if necessary.




Tasks:

<ol>

 <li>Projects at FILS Scientific Session (5p)</li>

</ol>

The Data Structures teacher wants to distribute projects to students, for them to participate at FILS Scientific Session. She prepared k projects and she has n students who want to participate (n&gt;=k). Each project must be given at least once, but the n students can work in teams to implement a certain project. This means that each project is given to a team of students, which is built from 1 or more students.

The values n and k will be read from the console, as well as the title of the subject and the name of the students.

You will have to:

<ul>

 <li>(2p) Display at the console all possibilities of distributing the k projects to the n students, as well the number of possible solutions, in the below form: For n=3 (students), k=2 (projects) There are 6 solutions:</li>

</ul>

Tom – “Java Animation”, Jane-“Java Animation”, Kate – “3D Game”

Tom – “Java Animation”, Jane – “3D Game”, Kate- “Java Animation”

Tom-“Java Animation”,Jane-“3D Game”,Kate-“3D Game”

Tom – “3D Game”, Jane – “Java Animation”, Kate –“Java Animation”

Tom – “3D Game”, Jane – “Java Animation”, Kate – “3D Game”

Tom – “3D Game”, Jane – “3D Game”, Kate –“Java Animation”

<ul>

 <li>(1.5p) Use a linked list to store the distribution from point 1.1. Each element of the linked list will contain a student (id and name) and a project (id and title). You will know that every n-th element of the list is the ending of a distribution. Implement the add function, in which you add a pair of (student, project) to the list.</li>

 <li>(1p) A student is sick, and the teacher has to delete the student from all possible distributions. Implement the delete function.</li>

 <li>(0.5p) The “3D Game” project uses an Oculus Rift for implementation and the Oculus is broken. The teacher decides to replace the project from the list with another project. Implement the replace function.</li>

</ul>







<ol start="2">

 <li>Johny’s Trip (2pts)</li>

</ol>

Johnny bought a car and decided to visit all his friends, but he has a lot of friends, on every street he has another friend. He started thinking how he can make his trip as shorter as possible. Soon, he realized that the best way is to pass on every street once and only once and he should finish his trip from the place where he started – his parents ’house. The streets are uniquely numbered from 1 to n, n&lt;1995. The intersections are numbered from 1 to m, m&lt;=44.  No intersection connects more than 44 streets. Every intersection is uniquely numbered. Each street is determined by exactly 2 intersections.  If there are more than one possible route, he has to choose the shortest one, from lexicographically point of view. All the streets have double ways, there are not isolated streets, but the streets are very narrow, and Johnny can’t turn the car on the street, just in intersections.   Help Johnny to find the best route for his trip. He leaves at intersection 0. Use a graph to solve the problem. The input data will be read from the console or from a file and the proposed route will be written at the console. If there are no solutions, a message will be displayed to Johnny.




<ol start="3">

 <li>Ancient alphabet decoder (3pts – 0.5 pts for working with files, 2.5 pts for topological sort)</li>

</ol>

Sydney Fox (world famous teacher of ancient history) and her assistant, Nigel Bailey, found a book written in an unknown language, but using the same letters as the English alphabet – no uppercase, only lowercase (example a, b, c ….). The book contains a brief index, but the order of the index words is different from the English alphabet. The treasure hunters attempted to use this index to determine the order of characters in the unknown language but failed. Write a program to help treasure hunters to determine the order of characters in the unknown language and display this order in a file. You must use topological sorting in graphs. Input data: index.in

In the file “index.in” there is at least 1 and at most 50 words followed by a line containing the character “.” (point). Each word has a maximum of 10 characters. The words of an index contain only the lowercase characters of the English alphabet and appear in ascending order of the unknown alphabet. Not necessarily all lowercase letters appear in the index, but an index will result in a unique sequence of characters that appear.

The output data: index.out

In the file “index.out” we write the unique sequence of characters that appear in “index.in”.




Useful references:

fclose: <u>http://www.cplusplus.com/reference/cstdio/fclose/</u> fopen: <u>http://www.cplusplus.com/reference/cstdio/fopen/</u> fprintf: <u>http://www.cplusplus.com/reference/cstdio/fprintf/</u> fscanf: <u>http://www.cplusplus.com/reference/cstdio/fscanf/</u> <u>http://www.cplusplus.com/doc/tutorial/files/</u>

<u>http://www.cs.washington.edu/education/courses/cse373/02au/lectures/lecture19l.pdf</u>





