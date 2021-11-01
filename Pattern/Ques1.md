## Question 1

Find the given pattern, if number of rows are given.


### Input

N = 6

### Output
1  
11  
111  
1001  
11111  
100001

```
#include <iostream>
using namespace std;
int main(){
    int n;
    cin>>n;
    for(int i=1;i<=n;i++){
       if(i%2==1){
               for(int j=1;j<=i;j++){
                   cout<<"1";
            }
       }
         else{
                cout<<"1";
                for(int j=1;j<=i-2;j++)
                    cout<<"0";
                    cout<<"1";
                }
           cout<<"\n";
        
    }
}

```

