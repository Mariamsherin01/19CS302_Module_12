# EX 58 C Function to display queue elements using Linked List.(use integer data in the queue)
## AIM:
To write a C Function to display queue elements using Linked List.

## Algorithm
1. Define a Node with float data and next pointer.
2. Initialize front and rear to NULL.
3. To enqueue: Create a new node. If the queue is empty, set both front and rear to it. Otherwise, add it after rear and update rear.
4. To display: Start from front and traverse through each node, printing its data.
5. Stop when you reach the end of the list (NULL).
  

## Program:
```
/*
C Function to display queue elements using Linked List.(use integer data in the queue)

Developed by: Mariam Sherin
RegisterNumber: 212222060143
struct Node
{
   float data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void display()
{
struct Node *ptr;
    ptr=front;
    if(ptr==NULL)
    {
        printf("queue is empty");
    }
    else
    {
        printf("queue elements:\n");
        while(ptr!=NULL)
        {
            printf("%.2f\n",ptr->data);
            ptr=ptr->next;
        }
    }
    

}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/b05148af-cd58-4950-945c-3252f87934d2)


## Result:
Thus the program was executed and the output was verified successfully.
