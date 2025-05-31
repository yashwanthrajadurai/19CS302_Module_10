# EX 46 C function to traverse the linked list and display it in the following format.

## AIM:

To write a C function to traverse the linked list and display it in the following format.

## Algorithm

Start.

Define a variables.

Write a functions to traverse the linked list and display it in the following format.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End  

## Program:

struct Node{ 

char data;

struct Node *next;

}*head;

void display()

{

struct Node *temp; 

temp=head; 

while(temp!=NULL)

{

printf("%c\n",temp->data); 

temp=temp->next;

}

}


## Output:

![Screenshot 2025-05-26 170846](https://github.com/user-attachments/assets/ec3609f6-a27a-49c1-9c83-13694c0de5d5)


## Result:

Thus the program was executed and the output was verified successfully.
