**Introduction:**</br>
In the assignment i used the A* function and the UCS function to generate the path from the starting state to the destination state and added some new features to calculate the number of battery charges it needed to go to the final destination </br>
**Changes:**</br>
In the code i added a new variable charge int the node class to calculate what amount of charge is has in the moment. and the charge changes accordingly as described. </br>
**Changes:**</br>
We used both the A* search and UCS algorithm. In both the algorithm priority queue is used to generate the optimal path and charges. All the things remain same but in every state we just kept track of the charge of the previous state and calculate the new state charge and also save it for further calculation. And continue doing the same process untill the goal is reached   

