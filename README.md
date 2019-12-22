# AtCoder Beginner contest  148


1. Round one


```c++
#include<bits/stdc++.h>
using namespace std;
 
int main(){
    int a,b;
    cin>>a;
    cin>>b;
 
    if(a==1 && b==2){
        cout<<3;
    }
    else if(a==2 &&b==1){
        cout<<3;
    }
    else if(a==3 && b==1){
        cout<<2;
    }
    else if(a==1 && b==3){
        cout<<2;
    }
    else if(a==2 && b==3){
        cout<<1;
    }
    else if(a==3 && b==2){
        cout<<1;
    }
    else{
 
    }
 
 
 
 
}
```






2. Strings with same length

```c++
#include<bits/stdc++.h>

#define REP(i,a,b) for(int i=a;i<b;i++)

using namespace std;
int main(){

    int total;
    cin>>total;


    string first,second;
    cin>>first>>second;
//    getline(cin,first);


//    getline(cin,second);


    string answer;




    REP(i,0,total)
     {
          answer=answer+first.at(i);
          answer=answer+second.at(i);
     }
     cout<<answer;

}
```