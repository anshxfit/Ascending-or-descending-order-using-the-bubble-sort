# Ascending-or-descending-order-using-the-bubble-sort
#include<iostream.h>
#include<conio.h>
void main()
{
clrscr();
int arr[10]=(45,12,89,33,2,77,50,10,5,70);
int i,j,temp,choice;
cout<<"original array:\n";
for(i=0;i<10;i++){
cout<<arr[i]<<" ";
}
cout<<"inter 1 for ascending or & fue Metending to her
cin>>choice:
for(i=0;i<9;i++)
{
for(j=0;j<9; j++);
if (choice == 1 && arr[j]>arr[j+i])
(choice == 2 && arr[j]<arr[j+i])
temp=arr[j];
arr[j]=arr[j+i];
arr[j+i]=temp;
}
cout<<"\n sorted array:\n";
for(i=0;i<10;i++)
{
cout<<arr[i]<<"";
}
getch();
}
