#include<stdio.h>
//#include<conio.h>  // Not needed in modern compilers
#include<stdlib.h>  // Needed for exit() function

#define MAX_SIZE 5  // Define maximum size of the queue

void main()
{
    int queue[MAX_SIZE], ch=1, front=0, rear=0, i, j=1;
    //clrscr();  // Not needed in modern compilers
    
    printf("Queue using Array");
    printf("\n1.Insertion \n2.Deletion \n3.Display \n4.Exit");
    
    while(ch)
    {
        printf("\nEnter the Choice:");
        scanf("%d", &ch);
        
        switch(ch)
        {
            case 1:
                if(rear == MAX_SIZE)
                    printf("\nQueue is Full");
                else
                {
                    printf("\nEnter element %d:", j++);
                    scanf("%d", &queue[rear++]);
                }
                break;
                
            case 2:
                if(front == rear)
                    printf("\nQueue is empty");
                else
                { 
                    printf("\nDeleted Element is %d", queue[front++]);
                }
                break;
                
            case 3:
                printf("\nQueue Elements are:\n");
                if(front == rear)
                    printf("\nQueue is Empty");
                else
                {
                    for(i = front; i < rear; i++)
                    {
                        printf("%d\n", queue[i]);
                    }
                }
                break;
                
            case 4:
                exit(0);
                
            default:
                printf("Wrong Choice: please see the options");
        }
    }
    //getch();  // Not needed in modern compilers
}