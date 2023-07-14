
#include <iostream>

using namespace std;

int main()
{
    printf("Hello World");
    int n=6;
    int arr[n]={1,1,2,2,3,4};
    int count=0;
    for(int i=0;i<n;i++){
        count++;
        if(arr[i]!=arr[i+1]){
            cout<<arr[i]<<"  "<<count<<endl;
            count=0;
        }
    }
    return 0;
}
