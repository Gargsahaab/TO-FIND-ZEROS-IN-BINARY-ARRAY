# hello-world12
Simple c++ program. find no of zeroes in the array containing 0 and 1 


#include<bits/stdc++.h>
using namespace std;

int main ()
{
int a[1000];
int x;
cin>>x;
int sum=0;
for(int i=0;i<x;i++)
{
sum=sum+a[i];
}
int y=x-sum;
cout<<y;

}
