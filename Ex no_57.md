# EX 57 C function to perfom push,pop and peek functions in Stack using Linked List.( store float data in stack)
## AIM:
To write a C function to perfom push,pop and peek functions in Stack using Linked List.

## Algorithm
1. Define a Node structure with a character data field and a pointer to the next node.
2. Initialize a global pointer `head` (or `top`) to NULL to represent the stack.
3. To push: Create a new node, assign the character, point it to head, and update head.
4. To pop: If head is not NULL, delete the top node and update head to the next node.
5. To peek: If head is not NULL, print the data at the head.
6. To display: Traverse from head to NULL and print each node’s data.
 

## Program:
```
/*
function to perfom push,pop and peek functions in Stack using Linked List.( store float data in stack)

Developed by: Mariam Sherin
RegisterNumber: 212222060143
struct Node   
{  
int data;  
struct Node *next;  
}*head;
void push(int data)  
{  
    struct Node *top=(struct Node*)malloc(sizeof(struct Node));
    if(head==NULL)
    {
        top->data=data;
        top->next=NULL;
        head=top;
    }
    else
    {
        top->data=data;
        top->next=head;
        head=top;
    }
}  
void pop()  
{  
    struct Node *top;
    if(head==NULL)
    {
        printf("stack is empty");
    }
    else
    {
        top=head;
        head=head->next;
        free(top);
    }
    
}  
void display()  
{ 
    struct Node *top;
    top=head;
    if(head==NULL)
    {
        printf("Stack Underflow");
        return;
    }
    printf("stack:");
    while(top!=NULL)
    {
        printf("%c ",top->data);
        top=top->next;
    }
}  
void peek()
{
     printf("\nstack top:%c\n",head->data);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/a19592e4-a8d0-41eb-8e85-25f258924a84)


## Result:
Thus the program was executed and the output was verified successfully.
