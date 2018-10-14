#include <iostream>
#include <stdio.h>
#include <string.h>

using namespace std;

int main()
{
  char a[100],b[100],temp;
  int i,j,len;
  cin>>a;
  len=strlen(a);
 for(i=len-1,j=0;i>=0;i--,j++){
    b[j]=a[i];
 }
 for(i=0;i<j;i++)
    cout<<b[i];
    return 0;
}
