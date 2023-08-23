//344. Reverse String
#include <iostream>

using namespace std;

int main()
{
    string s;
    cin>>s;
    int quq=0,q=0,a=0;
    for(int i=0;i<s.size();i++){
            if(s[i] =='Q'){q++; quq+=a;}
            else if(s[i] =='A'){a+=q;}
    }

    cout<<quq;
    return 0;
}
