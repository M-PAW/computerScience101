
# Depth First Search and Breadth First Search


## Depth First Search, Starting at the deepest point
 - A way to find vertices within a graph, able to avoid cycles.
 - Can find the exit to a puzzle dungeon when used.
 - When you visit a node, you record it as a 1 for visited. Which prevents
   you from visiting the same node twice.
 - You need to check for unvisited nodes, step back, and visit them.
 - This uses a stack.
 - This picks an unvisited child and keeps moving forward, until it 
   can't


## Breadth First Search, Starting at the beginning and going deep
 - At the starting node we grab the children, and mark the parent as 
   visited.
 - This uses a queue.
 - This takes all children at once, making it almost exponential.


## Run-times

 - o(v+e), o of vertex plus edge