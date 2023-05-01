Download Link: https://assignmentchef.com/product/solved-cecs328-lab8
<br>
<strong>Programming assignment 8. </strong>

<strong>Note</strong>: you can have different names for vertices: {a b c d e ..} = {v1 v2 v3 v4 ..} = {1 2 3 4 ..}




In this program you are required to implement DFS.

First, you can create the below graphs and print the resulting adjacency matrices/lists. Or create a random graph.




<ol>

 <li>Run <em>DFS </em>function to check if the graph is a DAG (directed acyclic graph):</li>

 <li style="list-style-type: none;">

  <ul>

   <li>Search for backward edges. If there are any, print: “<u>Cycle detected, topological sort is impossible</u>”.</li>

  </ul></li>

 <li>If the graph is DAG, (while running DFS):

  <ul>

   <li>Insert the vertex into a linked list as it finishes.</li>

   <li>Using your linked list, print the topological order of the vertices along with their <em>start/finish time.</em></li>

  </ul></li>

</ol>