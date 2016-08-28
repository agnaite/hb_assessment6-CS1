# hb_assessment6-CS1

##Runtime

####When calculating the Big O notation for a particular algorithm, it’s necessary to consider the length of time it takes for the algorithm to run as the algorithm’s workload approaches infinity. You can think of the workload as the number of tasks required to complete a job. What determines the workload of figuring out whether your box of animal crackers contains an elephant?



####Order the following runtimes in ascending order by efficiency as n approaches infinity:
1. O(1)
2. O(log n)
3. O(n log n)
4. O(n)
5. O(2n)
6. O(n2)



##Stacks and Queues

####In the following cases, would a stack or queue be a more appropriate data structure?
####1. The process of loading and unloading pallets onto a flatbed truck
Stack.
####2. Putting bottle caps on bottles of beer as they roll down an assembly line
Queue.
####3. Calculating the solution to this mathematical expression: 2 + (7 * 4) - (3 / 2)
Stack.

####Describe two more situations where a queue would be an appropriate data structure.
1. Sending out scheduled notifications.
2. A customer service hotline.

####Describe two more situations where a stack would be an appropriate data structure.
1. Washing a stack of plates.
2. Reversing a word.

##Linked Lists

####Given the linked list below, which are the nodes?
Apple + next, Berry + next, and Cherry + next are the nodes.

####What is the data for each node? 
The data for each node is "Apple", "Berry", and "Cherry".

####Where is the head? Where is the tail? 
The head is the Apple node. The tail is the Cherry node pointing to None.

![Image of Linked List](http://fellowship.hackbrightacademy.com/materials/skills/cs-data-struct-1/_images/graphviz-9d1bfe45f44c3720814826a4b6a956a85f2802e6.svg)

####What’s the difference between doubly- and singly-linked lists?
A singly-linked list references the next node only.
A doubly-linked list references both the next and the previous node.

####Why is it faster to append to a linked list if we keep track of the tail as an attribute?
Instead of having to iterate over each node until you hit None, you can simply reference the tail node to your new node, and reference your node to None.

##Trees
![Image of Linked List](http://fellowship.hackbrightacademy.com/materials/skills/cs-data-struct-1/_images/graphviz-e013ff86fe5c8eeebf4b3b0ae8bf151ce3262e54.svg)

####Given the tree above, in what order would a Breadth First Search (BFS) algorithm visit each node until finding burrito (starting at food)? Just list the order of nodes visited; no need to recreate the state of the algorithm data in your answer.
Italian -> Indian -> Mexican -> lasagna -> pizza -> tikka masala -> saag -> burrito

####Given the tree above, in what order would a Depth First Search (DFS) algorithm visit each node until finding Chicago-style (starting at food)? Just list the order of nodes visited; no need to recreate the state of the algorithm data in your answer.
Italian -> lasagna -> pizza -> thin crust -> Chicago-style

####How is a binary search tree different from other trees?
A binary tree is sorted based on a rule. E.g. The node on the left is always bigger and the node on the right always smaller. 
