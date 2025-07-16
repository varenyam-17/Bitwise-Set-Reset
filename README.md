# shift
or
#include <iostream>
using namespace std;
int main()
{
    int set;
    int a;
    cout<<"Enter a number"<<endl;
    cin>>a;
    cout<<"Enter a bit to be set"<<endl;
    cin>>set;
    int var1=1<<set;
    int final=a|var1;
    cout<<final<<endl;
    
    
}
and
#include <iostream>
using namespace std;
int main()
{
    int reset;
    int a;
    cout<<"Enter a number"<<endl;
    cin>>a;
    
    cout<<"Enter a bit to be reset"<<endl;
    cin>>reset;
    int var1=1<<reset;
    int final=a&~(var1);
    cout<<final<<endl;
    
    
}
