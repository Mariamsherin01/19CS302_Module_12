# EX 56 C function to display stack elements using Linked List.(store integer data in stack) .
## AIM:
To write a C function to display stack elements using Linked List.

## Algorithm
1. Define a linked list node to hold string data.
2. In the push function, create a new node, copy the string, and add it to the top of the stack.
3. Update the head pointer to point to the new node.
4. In the display function, traverse the stack from top to bottom.
5. Print each node's data until the end is reached.
  

## Program:
```
/*
C function to display stack elements using Linked List.(store integer data in stack) .

Developed by: Mariam Sherin
RegisterNumber: 212222060143
struct Node   
{  
char data[50];  
struct Node *next;  
}*head,*top;  
void display()  
{ 
    top=head;
    if(top==NULL)
    {
        printf("stack is empty");
    }
    while(top!=NULL)
    {
        printf("%s\n",top->data);
        top=top->next;
    }
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/92028abe-772f-4471-9334-a0d68a0edce4)


## Result:
Thus the program was executed and the output was verified successfully.
