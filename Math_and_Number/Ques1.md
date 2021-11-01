## Question
Given a list of number, stop processing input after the cumulative sum of input become negative.

### Input
 
 1  
 2  
 88  
-100
 
 

 ### Output

 1  
 2  
 88


## Code
 ```
#include<iostream>
using namespace std;
int main()
{
int n;
cin>>n;
int cs;
cs=n;
if(n>=0)
cout<<n<<endl;
while(cs>=0)
{
int t;
cin>>t;

    cs=cs+t;
    if(cs>=0)
    cout<<t<<endl;
}
return 0;
}
 ```
