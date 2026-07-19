# Retail-billing-system

//Retail billing system
#include<stdio.h>
int main(){
int Amount,GST=18;
float total1,total2;

printf("Enter the Amount :");
scanf("%d",&Amount);

total1 = (Amount*GST)/100;


total2 = Amount+total1;
printf("The total Amount is %.2f\n",total2);
scanf("%.2f\n",&total2);
return 0;

 }
