Author: Soumik Roy<br>
<b>**Hint</b>: This is a bfs problem. In order to keep the path lexicographically smallest,you have to take the smaller node first while traversing.<br>

<b>Detailed tutorial:</b> This is simple bfs. There are only two extra stuffs to do. Printing the path and keeping the path lexicographically smallest.<br>
In order to keep the path lexicographically smallest,we can just sort the child nodes of every node we visit and run a bfs.<br><br>
In order to trace the path,
we can have an array/vector which will store the previous/parent node of current index. Before pushing a node to the queue,we can set it's parent node. Finally,we can trace the
path by tracking the previous node starting from the ending node until we find the starting node. <br><br>
[Solution Link](https://github.com/soumik9876/Lightoj-solutions/blob/master/Lightoj%201271%20-%20Better%20Tour.cpp)
