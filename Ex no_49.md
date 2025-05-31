# EX 49 C function to search an element in the doubly linked list.

## AIM:

To write a C function to search an element in the doubly linked list.

## Algorithm

Start.

Define a variables.

Write a function to perform all basic operations.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End. 

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
    
    temp=head;
    
    int i=1;
    
    while(temp!=NULL)
    
    {
    
        if(data==temp->data)
        
        {
        
            printf("item %d found at location %d",data,i);
            
            return;
        
        }

        
        i++;
        
        temp=temp->next;
    
    }
    
    printf("Item not found");

}


## Output:

![Screenshot 2025-05-26 171526](https://github.com/user-attachments/assets/0fded8b2-4e57-4263-babe-ec5c9126742c)


## Result:

Thus the program was executed and the output was verified successfully.
