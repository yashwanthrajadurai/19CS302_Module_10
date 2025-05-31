# EX 50 C function to delete a node from a Doubly Linked List at the beginning of the list.

## AIM:

To write a C function to delete a node from a Doubly Linked List at the beginning of the list.

## Algorithm

Start.

Define a variables.

Write a function to perform delete operation.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End.

## Program:

void delete()

{

struct Node *p;

p=head; 

if(p==NULL)

{

printf("UNDERFLOW \n");

}

else if(head->next==NULL)

{

head=NULL; 

free(head);

printf("Node deleted\n");


}

else

{

p=head; head=head->next;

head->prev=NULL; 

printf("Node deleted\n");

}

}



## Output:

![Screenshot 2025-05-26 171809](https://github.com/user-attachments/assets/d5ed8ce8-91e2-4cb1-bd90-5ba311cb7777)



## Result:

Thus the program was executed and the output was verified successfully.
