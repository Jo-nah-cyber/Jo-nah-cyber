#include<stdio.h>
main()
{
     int day;
     printf("enter day of the week ");
     scanf("%d",&day);
     switch(day)
     {
         case 1: printf("monday");
                 break;
        case 2: printf("Tuesday");
                break;
        case 3: printf("Wednesday");
                break;
        case 4: printf("thursday");
                break;
        case 5: printf("Friday");
                break;
        case 6: printf("Saturday");
                break;
        case 7: printf("sunday");
                break;
        default:printf("Invalid input");
                break;
      }
}
