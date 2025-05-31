# EX 48 C functions to perform all basic operations in Doubly Linked List.

## AIM:

To write a C functions to perform all basic operations in Doubly Linked List.

## Algorithm

Start.

Define a variables.

Write a function to search an element in the double linked list..

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End

## Program:

struct Node

{

struct Node *prev; 

struct Node *next; 

int data;

}*head;

void search(int data)

{

struct Node *temp;

int item=data,i=0,flag; 

temp=head; 

if(temp==NULL)

{

printf("Empty list\n");

}

else{

while(temp!=NULL)

{

if(temp->data == item)

{

printf("item %d found at location %d",item,i+1); 

flag=0;

}

i++;

temp=temp->next;

}


if(flag!=0)

{

printf("Item not found\n");

}

}

}


## Output:

![Screenshot 2025-05-26 171252](https://github.com/user-attachments/assets/a153b014-edbc-43fc-b6ae-e31d3ede1434)


## Result:

Thus the program was executed and the output was verified successfully.
