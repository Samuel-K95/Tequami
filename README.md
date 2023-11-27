# Tekuami Travel Planning System

## This is my sophomore year first semester Datastructure and ALgorithm Project. 

The system has user and admin panel. On the Admin Panel, the admin can log in and create source and destination that the system provides for its users.
through each sub destination it asks the admin to insert min and max values that they charge to get to that destination. the system then saves the minumum amount they are charging, the maximum amount, the name of the destination and a pointer to the next destination if any as a node. finally it connects each node and creates a tree data structure. the left most node containing the cheapest path and the right most containing the most expensive amount they are charging to get to the destination. This is a good example of how we can represent real world entities as node.
 The admin can also sort and search through the users that are on the system. the sorting uses two methods, bubble sort and heap sort algorithm. depending on the preference of the admin. The admin can also search users by their name, the searching algorithm is implemented using Linear search algorithm.

 on the user panel, users can sign in by their name. and either select built in destinations or new destination, if the admin has set new destinations, and choose their plan. finally their choice is written insed a file, which they can use as a receipt.
