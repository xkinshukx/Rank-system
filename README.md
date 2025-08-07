# Rank-system
Rank system Like games
#include<stdio.h>

int main(){
int points;
printf("enter your points ");
scanf("%d",&points");

switch(points){
case(points<100):printf("venguard")
     break;
case(points>100;points<200):printf("exceed")
     break;
case(points>200;points<400):printf("supreme");
     break;
case(points>400;points<600):printf("pareless");
     break;
default:printf("legend");     
}
return 0;
}
