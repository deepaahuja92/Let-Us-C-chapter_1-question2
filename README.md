# Let-Us-C-chapter_1-question2
#include<stdio.h>
int main()
{
int distance;
printf("Enter the distance between two cities in km");
scanf("%d",&distance);
printf("Distance in meters: %f",distance*1000);
printf("Distance in meters: %f",distance*1000*100);
printf("Distance in feet : %f",distance*1000*39.3701);
printf("Distance in inches: %f"distance*1000*39.3701*12);
return 0;
}
