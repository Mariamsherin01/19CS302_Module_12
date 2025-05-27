# EX 60 C function to find the peek element of the queue using linked list.
## AIM:
To write a C function to find the peek element of the queue using linked list.

## Algorithm
1. Define a Node structure with a float data field and a pointer to the next node.
2. Maintain two pointers: `front` and `rear` to track the start and end of the queue.
3. To peek, check if the queue is empty (i.e., front == NULL).
4. If not empty, print or return the value stored at the front node.


## Program:
```
/*
C function to find the peek element of the queue using linked list.

Developed by:  Mariam Sherin
RegisterNumber: 212222060143
struct Node
{
   float data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void peek()
{
    struct Node *ptr=front;
    printf("%.2f",ptr->data);
    
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/db94c65c-3f92-41fa-8348-ea42a9d8c775)


## Result:
Thus the program was executed and the output was verified successfully.
