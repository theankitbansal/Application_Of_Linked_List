# Application_Of_Linked_List
Detailed application of linked list


Introduction

In the field of software development, when it comes to managing data, multiple tools could accomplish the job. The idea is to understand which tool is the suitable one to utilize for our given purpose. As a reminder, despite which language we begin coding, one of the first things that we come across are data structures, which, by now we should be acquainted with.

The objects that make use of various ways to shape and structure the data are termed Data Structures. Usually, they are made up of primitives such as hashes, objects, variables, or arrays. Nevertheless, these are just the start when it comes to the potential. There are numerous others that may start to sound complex as you understand more about their properties. A linked list is one of the data structures that may sound complex at first but the more you learn about linked lists, the more interesting they can get. Linked lists are very easy to comprehend, but they tend to have this reputation of being complicated. The more you know about them, the more you understand that it is not the structure of linked lists that will baffle you. Instead, it takes some time to fully understand the logic to decide when and how to use them.

What are Linked lists?

To comprehend what is a linked list, it’s necessary to talk about the kind of data structure they are. A significant aspect of linked lists is that they are linear data structures, which suggests that there exists order and a sequence to how they can be built and traversed. We can picture a linear data structure like the chalk lines in a game of hopscotch. To get to the end of the list we have to go through all the items sequentially.

A linked list can be regarded as both linear data structure and dynamic data structure.The linked list includes a series of continuous nodes. A single node is only the object which includes things such as, “next” and “data” pointer which indicates to the next node in the event of a circular and singly linked list, and also “previous” pointer which will indicate the earlier node in case of a doubly linked list. In this manner, it creates a chain-like structure. It can efficiently accomplish operations such as insertion, append, deletion without reorganization of the whole list since memory allocation is accomplished during run-time but if we want the same operations on an array that ought to allot fixed memory, its run time will get more costly. Hence, this is the most crucial aspect for utilizing linked lists when it comes to memory and storage than arrays. A linked list can execute operations from basics to a more elevated level. Since it is dynamic, a growth or drop in size/length can be accomplished as per need. It is amply utilized in real-life applications as it functions and has numerous benefits to memory.

The second most-utilized data structure after the array is the Linked list. Let us look at some of the essential terms to comprehend the idea of Linked List.

1. Link − Every link of a linked list stores a data named an element.
2. Next − Every link of a linked list includes a link to the subsequent link named Next.
3. LinkedList − A Linked List includes the connection link to the foremost link named First.
4. A data structure is a compilation of data that can be incorporated in any programming language.
5. A pointer piles the address of a value in memory. They can also indicate nothing (NULL). A reference is extremely alike, though they cannot indicate nothing.


A linked list can be huge or small, regardless of the size, the components that make it up are just nodes. Linked lists are merely a sequence of nodes, which are the elements of the list.

![image](https://user-images.githubusercontent.com/81725794/179711473-e8ca2518-1198-4b8d-ba92-2175ddbf08cd.png)


This depiction of a linked list shows that every node includes two fields. The start is a special pointer that points to the first node of the linked list The first field comprises data, and the subsequent field includes pointers that point to a different node. Here, the start pointer saves the address of the first node, then we can see a null pointer, and at the end, that declares the end of the Linked List.

Properties of Linked List

1. It can be pictured as a sequence of nodes where every node includes the location of the following node. You can notice this in the diagram given below:

![image](https://user-images.githubusercontent.com/81725794/179711594-286652a3-caf7-4739-a722-4b20ae666706.png)

2. The structure of the node is
![image](https://user-images.githubusercontent.com/81725794/179711672-fea09470-3d51-4860-90c0-0626fee0782d.png)
![image](https://user-images.githubusercontent.com/81725794/179711689-b2b061ba-a830-45b8-b16b-206af59e447c.png)

3. The head of the linked list is the first node and via the head, we can perform distinct operations on the linked list. In each linked list question, the reference of the head node of the linked list will be given.
4. The final node of the linked list implies NULL(None) which suggests that it is the last node.
5. Unlike arrays, linked list elements are not stowed at adjacent memory locations.
6. Linked Lists manages a few of the shortcomings of arrays of owning a fixed size as Linked Lists are dynamic.


Time and Space Complexity

Time

Most of the benefits of linked lists can be seen when it comes to the deletion and insertion of nodes in the list. Unlike the dynamic array, deletion and insertion at any point on the list require constant time. Nevertheless, accessing the data in these nodes need linear time owing to the necessity to look through the entire list via pointers. It’s also essential to state that there is no method of optimizing search in linked lists. In the array, at least we could keep the array sorted. Nonetheless, as we don’t have any idea how long the linked list is, there is no way of accomplishing a binary search:

![image](https://user-images.githubusercontent.com/81725794/179712174-33a6f683-d38a-4b0d-9b89-e7de348c0630.png)

Space

Linked lists carry two major chunks of data, namely, the value and the pointer per node. This indicates that the amount of data stowed grows linearly with the number of nodes in the list. Thus, the space complexity of the linked list is linear:

![image](https://user-images.githubusercontent.com/81725794/179712220-37e0f6ff-05d6-49ec-b317-77433589c5f6.png)

Variations

There are primarily three kinds of linked lists: singly, circular, doubly-linked lists.

Singly Linked List

A singly linked list is a kind of linked list that is unidirectional, meaning, it can be traversed in just one direction from the head to the last node, called the tail.

![image](https://user-images.githubusercontent.com/81725794/179712376-bee4b1fa-fd4f-415f-b312-df1d1ac3f410.png)

Every element in a linked list is regarded as a node. A single node includes data and a pointer to the next node which supports retaining the structure of the list.

The foremost node is termed the head; it directs to the first node of the list and allows us access to each other elements in the list. The final node, also occasionally termed the tail, directs to NULL which assists us in deciding when the list ends. Operations that can be executed on singly-linked lists include insertion, deletion, and traversal.

Doubly Linked List

Doubly linked lists include nodes that have a data field, “next” field, and another link field “prev” pointing to the last node in the sequence.

![image](https://user-images.githubusercontent.com/81725794/179712426-e1fc4bc5-a504-49d3-8b4b-0e7f81fa0adb.png)

The browser cache allows you to hit the FORWARD and BACK buttons. Here we ought to maintain a doubly linked list, with URLs as a data field, to permit access in both directions. To go to the earlier URL we will make use of the “prev” field and to go to the subsequent page we will make use of the “next” field.

Circular Linked List

Circular linked lists is singly linked list where the last node, the “next” field implies the first node in the sequence.

![image](https://user-images.githubusercontent.com/81725794/179712546-65b08701-7c34-4ff6-9a8d-a6bce11acb44.png)

Timesharing issues are resolved by the operating system.

In a timesharing environment, the operating system must keep a list of current users and must alternately let every user use a small amount of CPU time, a single user at a time. The operating system will choose a user, allow him/her to use a small amount of CPU time, and then shift to the next user. For this application, there shouldn’t be any NULL pointers unless there is no one demanding CPU time, i.e list is empty.

Applications of Linked List

Implementing Stacks

A stack data structure can be accomplished by utilizing a linked list data structure. The stack incorporated with the help of a linked list can function for an infinite number of values. That indicates, the stack incorporated utilizing linked list functions for the variable size of data. Hence, there is no requirement to correct the size at the start of the implementation. The Stack implemented with the help of a linked list can arrange as many data values as we want.

In linked list incorporation of a stack, each new element is put in as a ‘top’ element, which indicates each newly incorporated element is pointed by ‘top’. Whenever we wish to delete an element from the stack, just remove the node which is pointed by ‘top’ by moving ‘top’ to its earlier node in the list. The next field of the first element has to be NULL always.

![image](https://user-images.githubusercontent.com/81725794/179825561-ad29ac25-97e8-4316-a9b2-a3eff2d6bf00.png)

Queues using Linked List

The data structure ‘queue’ can be implemented with the help of a linked list data structure. The queue which is enforced utilizing a linked list can function for an infinite number of values. That implies that a queue employing a linked list can function for the variable size of data. There is no necessity to revise the size at the start of the implementation. The Queue executed with the help of a linked list can arrange as many data values as we want.

In linked list execution of a queue, the node inserted last is pointed always by ‘rear’ and the node inserted first is always indicated by ‘front’.

![image](https://user-images.githubusercontent.com/81725794/179825606-718a9b19-ee8c-4530-88b6-6beb9199fc38.png)

In the above example, the node last inserted is 50 and it is directed by ‘rear’ and the node first inserted is 10 and it is directed by ‘front’. The sequence of elements inserted is 10, 15, 22, and 50.

Implementation of Graphs

Processes with a graph depicted by an adjacency matrix are quicker. But if a graph is big we can’t make use of such an enormous matrix to depict a graph, hence we should make use of a cluster of adjacency lists, which is tighter. Utilizing adjacency lists is the most preferred option when a graph is sparse. Talking about the representation of graphs. Let’s look at the easiest implementation to depict a graph by an array of adjacency lists. The primary idea of this method is stowing a linked list of adjacent vertices for every vertex. We substitute the single integer value head by once more array (call it heads), which includes the head of the list of contiguous vertices for every vertex. Other arrays like data and next stay common for all other vertices. And another point about utilizing arrays rather than class: we ought to know what cells in arrays are free and what is employed, in our execution we describe the variable used, which includes a number of used cells and when we have to acquire a free cell we will take (used + 1). Therefore, we acquire an implementation of a data structure for depicting graphs (call it MultiList – list having multiple heads). Java code for the defined implementation:

![image](https://user-images.githubusercontent.com/81725794/179825695-01e1ad22-ad8a-493e-800e-3cd275d64233.png)

![image](https://user-images.githubusercontent.com/81725794/179825707-57bee5e4-815a-4718-873e-06b830fae95a.png)

Implementing Hash Tables

Hash Tables give a subset of the dynamic set operations. Generally, a collection of keys are mapped with some values on the basis of specific relations. Nevertheless, situations can arise when various keys map to the exact position provided by the Hash function, causing a collision. This situation can be solved by Hash Table Chaining. The chaining approach solves collisions by moving ahead and putting all the keys that map to a slot in that slot but depicting them as a linked list. Hash Table chaining in Java is achievable with both, Doubly Linked List and Singly Linked List. Though the execution is the same, the only distinction is that Doubly Linked List permits two-way traversal meaning, the node includes a pointer to the next along with the previous node. Therefore, the complexity of deletion and insertion at a known position lowers to O(1) as compared to the Singly Linked List (O(n)).

Example:

![image](https://user-images.githubusercontent.com/81725794/179825761-90f2e28a-c683-4679-b5c9-d6ea402a53be.png)

Approach :

1. Insertion: To insert, a key is merely hashed to acquire the position in the table (the list where this new key has to be inserted), and then at the head of the doubly linked list, insert the key, utilizing the standard linked list procedures.
2. Deletion: Go through the list that the key maps to via the hash function and delete the key from that list with the help of the usual linked list procedures.

Portray a Polynomial with a Linked List

We can make use of a linked list to portray a polynomial. In the linked list, every node contains two data fields, namely coefficient, and power. Thus, every node denotes a term of a polynomial. For instance, we can depict the polynomial with a linked list:

![image](https://user-images.githubusercontent.com/81725794/179825896-57726efe-b572-4f64-aa86-cbd1dc995cfc.png)

We can sort a linked list in O(n log n) time, where n is the total number of the linked list nodes.

If two polynomials are added, we can add the coefficients of like terms and develop a new linked list for the consequent polynomial. For instance, we can utilize two linked lists to portray polynomials.

![image](https://user-images.githubusercontent.com/81725794/179825949-7f82da5e-e810-4e7c-bcc4-462d608b9959.png)

When we add them jointly, we can group the like terms and render the result

As both linked lists are ordered by the power, we can make use of a two-pointer technique to combine the two sorted linked list.

![image](https://user-images.githubusercontent.com/81725794/179826020-507c86e8-26df-4f10-9975-0d2ce8e3305d.png)

Large-Number-Arithmetic

Large number arithmetic utilizing doubly linked list – the incorporation of the class LargeInt, which makes use of a dynamic physical structure to stow every digit of extremely large integers (for instance, prime numbers that are 70-digits long), and offer arithmetic operations that can be executed on them. Huge integers can be negative or positive(or zero).

In particular, the class contains:

1. A default constructor
2. Operator functions to overload operators +, -, *, /, %
3. Operator functions to overload operators ==, <, <=, >, >=
4. An operator function to overload the operator <<
5. An operator function to overload the operator >>

Linked allocation of files

A file of enormous size may not be stowed in one place on a disk. Hence, there have to be some means to connect all the scattered pieces of the file together. The application of a linked list lets an effective file allocation procedure in which every block of a file includes a pointer to the file’s text block. The file blocks can be distributed anywhere in the disk space. This suggests that we can evade fragmentation within our disk, as in the case of adjacent allocation.

![image](https://user-images.githubusercontent.com/81725794/179826255-5b3e4812-404e-4164-b75d-d0ee01e3e4ce.png)

This is a much more effective approach, and it averts the unnecessary wastage of space. Also, linked list allocation causes less load on the directory since it just needs to include the starting and finishing pointers of the file.

Memory Management with Linked List

Another method that can be used to keep a track of memory is to own a linked list of free memory segments and allocated memory segments, where a segment can be a process or a hole between the two processes.

When holes and processes are maintained on a list that is sorted by address, numerous algorithms can be utilized to allot memory for a recently built process or a current process being exchanged in from the disk. We consider here that memory knows how much memory to allocate. There are various kinds of algorithms to accomplish this.

The table mentioned below explains those various types of algorithms:

First fit:  Here, the memory manager inspects along with the list of segments till it locates a hole big enough. The hole is split into two parts, for process, and for unused memory. This algorithm is fast as it searches as little as possible.
Next fit: This algorithm operates in an exact manner as the first-fit algorithm, except that it keeps track of whenever it locates a suitable hole. The next time it is called to find a hole, it begins scouring the list from the exact place it left off last time.
Best fit: Best fit algorithm looks for the whole list and takes the tiniest hole that is adequate. Instead of splitting up a big hole that might be required later, this algorithm attempts to look for a hole that is close to the actual size that is required.
Worst fit: This algorithm always takes the biggest available hole, so that the hole when broken off will be large enough to be useful.
Quick fit: This algorithm keeps different lists for some of the more common sizes requested.

Real world applications of linked list

1. Image viewer – Next and Previous images are linked, so can be accessed by the “next” and “previous” buttons.
2. Next and Previous page in a web browser – We can access the previous and next “url” searched in a web browser by pressing the “back” and “next” buttons as they are connected as a linked list.
3. Music Player – Songs in the music player are connected to the previous and next song. You can listen to the songs either from the beginning or end of the list.
4. Mailing lists: Linked lists have their benefit in email applications as well. Since it is challenging to anticipate numerous lists, maybe a mailer creates a linked list of email addresses before sending a message.

