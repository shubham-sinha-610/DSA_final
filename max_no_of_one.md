
#include <iostream>

using namespace std;

int main()
{   int n=9;
    int min;
    int arr[n]={1,1,1,1,1,1,1,1};
    int count=0;
    int temp=0;
    for(int i=0;i<n;i++){
        if(arr[i]==1){
        temp++;
        }
        else{
          
            temp=0;
        }
         if(temp>count){
            count=temp;
           
            }
        
    }
    cout<<count;

    return 0;
}
