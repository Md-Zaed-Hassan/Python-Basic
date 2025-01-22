# Linked List

## Linked List Task 1:
i) Create a Node class which will hold two fields i.e an integer element and a reference to the next Node. 

ii) Create a Linked list Abstract Data Type (ADT)named MyList.The elements in the list are Nodes consisting of an integer type key (all keys are unique) and a reference to the next node. 
[You are not allowed to use any global variable other than head]

## Linked List Task 2:
a. MyList (int [] a) or def init (self, a)

Pre-condition: Array cannot be empty. Post-condition:This is the default constructor of MyList class. This constructor creates a list from an array.

void showList ( ) or def showList(self)

Precondition: None. Postcondition: Outputs the keys of the elements of the order list. If the list is empty, outputs “Empty list”. boolean isEmpty ( ) or def isEmpty(self)

Pre-condition: None. Post-condition: Returns true if a list is empty. Otherwise, returns false. void clear ( ) or def clear(self)

Pre-condition: The list is not empty. Post-condition: Removes all the elements from a list.

void insert (Node newElement) or def insert(self, newElement) 

Pre-condition: None. 

Post-condition: This method inserts newElement at the tail of the list. 

If an element with the same key as newElement already exists in the list, then it concludes the key already exists and does not insert the key.

void insert (int newElement, int index) or def insert(self, newElement, index)

Pre-condition: The list is not empty. 

Post-condition: This method inserts newElement at the given index of the list. 

If an element with the same key as newElement value already exists in the list, then it concludes the key already exists and does not insert the key. [You must also check the validity of the index]. Node remove (int deleteKey) or def remove(self, deletekey) (4) Pre-condition: List is not empty. Post-condition: Removes the element from a list that contains the deleteKey and returns the deleted key value.

## Linked List Task 3
Write a function to find out the even numbers that are present in the list and output another list with those numbers.

Sample Input Sample Output 1 -> 2 -> 5 -> 3 -> 8 2 -> 8 101 -> 120 -> 25 -> 91-> 87 -> 1 120

Write a function to find out if the element is in the list or not.

Sample Input Sample Output 1 -> 2 -> 5 -> 3-> 8 and 7 False 101 -> 120 -> 25 -> 91-> 87 -> 1 and 87 True

Write a function to reverse the list. [You are not allowed to create any other list] 

Sample Input Sample Output 1 -> 2 -> 5 -> 3-> 8 8 -> 3 -> 5 -> 2 -> 1

Write a function to sort the list. [You are not allowed to create any other list] 

Sample Input Sample Output 1 -> 2 -> 5 -> 3-> 8 1 -> 2 -> 3 -> 5 -> 8

Write a function that prints the sum of the values in the list. 

Sample Input Sample Output 1 -> 2 -> 5 -> 3-> 8 19

Write a function that rotates the elements of the list k times. [You are not allowed to create any other list].  

Sample Input Sample Output 3 -> 2 -> 5 -> 1-> 8, left, 2 5 -> 1 -> 8 -> 3 -> 2 3 -> 2 -> 5 -> 1-> 8, right, 2 1 -> 8 -> 3 -> 2 -> 5


# Doubly Linked List

## Task 1

 Create a Node class which will hold three fields i.e an integer element and a reference to the next Node along with a reference to the previous Node. ii) Create a Dummy Headed Doubly Circular Linked list Abstract Data Type (ADT)named DoublyList.The elements in the list are Nodes consisting of an integer type key (all keys are unique) and a reference to the next node and a reference to the previous Node. [You are not allowed to use any global variable other than head.]

 ## Task 2

 Constructors: a. DoublyList (int [] a) or def intit(self,a)

Pre-condition: Array cannot be empty. Post-condition:This is the default constructor of MyList class. This constructor creates a Dummy Headed Doubly Circular Linked list list from an array.

void showList ( ) or def showList(self)

Precondition: None. Postcondition: Outputs the keys of the elements of the order list. If the list is empty, outputs “Empty list”.

void insert (Node newElement ) or def insert(self, newElement) Pre-condition: None. Post-condition: This method inserts newElement at the tail of the list. If an element with the same key as newElement already exists in the list, then it concludes the key already exists and does not insert the key.

void insert (int newElement, int index) or def insert(self, newElement, index)

Pre-condition: The list is not empty. 

Post-condition: This method inserts newElement at the given index of the list. If an element with the same key as newElement value already exists in the list, then it concludes the key already exists and does not insert the key. [You must also check the validity of the index].

void remove (int index) or def remove(self, index)

Pre-condition: The list is not empty. 

Post-condition: This method removes the Node at the given index of the list.[You must also check the validity of the index]. 
int removeKey(int deleteKey) or def removeKey(self, deletekey) Pre-condition: List is not empty. Post-condition: Removes the element from a list that contains the deleteKey and returns the deleted key value.
