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

