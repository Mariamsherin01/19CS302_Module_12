# EX 59 C functions to perform-enqueue, dequeue, peek, display in Queue using Linked List.(use character data in Queue).
## AIM:
To write a C functions to perform-enqueue, dequeue, peek, display in Queue using Linked List.

## Algorithm
1. Define a Node structure with integer data and a next pointer.
2. Initialize front and rear pointers to NULL.
3. For enqueue: Create a new node and add it at the rear.
4. For dequeue: Remove the node from the front and update pointers.
5. For peek: Display data at the front if queue is not empty.
6. For display: Traverse from front to rear, printing each node's data.
 

## Program:
```
/*
functions to perform-enqueue, dequeue, peek, display in Queue using Linked List.(use character data in Queue).

Developed by: Mariam Sherin
RegisterNumber: 212222060143
struct Node
{
   int data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void enqueue(int data)
{
struct Node *ptr=(struct Node*)malloc(sizeof(struct Node));
ptr->data=data;
ptr->next=NULL;
if(front==NULL)
{
front=rear=ptr;
}
else
{
rear->next=ptr;
rear=ptr;
}
}

void display()
{
    struct Node *ptr;
    ptr=front;
    if(front==NULL)
    {
        printf(" ");
        
    }
    else
    {
        printf("queue elements:\n");
        while(ptr!=NULL)
        {
            printf("%d\n",ptr->data);
            ptr=ptr->next;
        }
    }
}
void dequeue()
{
    struct Node *ptr;
    if(front==NULL)
    {
        printf("empty");
    }
    else
    {
        ptr=front;
        front=ptr->next;
        free(ptr);
    }
}
void peek()
{
    printf("peek:%d\n",front->data);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/5a5537f8-1f9e-4c80-bc1c-33c762538cb6)



## Result:
Thus the program was executed and the output was verified successfully.
