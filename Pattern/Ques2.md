## Question 2
Find the given pattern, if number of rows are given.
### Input
N = 4
### Output
1     1
12   21
123 321
1234321

`
#include<iostream>
using namespace std;
int main(){
    int n;

    cin>>n;

    
   for(int i=1; i<=n; i++){
       for(int j=1;j<=i;j++){
           cout<<j;
       }
      
       for(int space=((n-i)*2)-1); space>0; space--){
           cout<<" ";
       }
       
       for(int j=i; j>=1;j--){
           if(j!=n){
               cout<<j;
           }
       }
   }
}


`
