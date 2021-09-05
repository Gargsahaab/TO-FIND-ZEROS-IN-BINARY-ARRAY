
Simple c++ program
program to find no of zeroes in a array containing 0 or 1



#include<bits/stdc++.h>
using namespace std;
int main()
{
    int i,n;
    int a[1000];
    cin>>n;
    int sum=0;
    for(i=0;i<n;i++)
    {

        cin>>a[i];
        sum+=a[i];
    }
    int y=n-sum;
    cout<<"no of zeros are: "<<y;

    return 0;

}
