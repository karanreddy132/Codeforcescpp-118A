# Codeforcescpp-118A
#include<bits/stdc++.h> 
 
using namespace std;
 
int main(){
    string s;
    cin >> s;
    int len = s.length();
    for(int j=0;j<len;j++){
        if((s[j]=='A') || (s[j]=='a') || (s[j]=='E') || (s[j]=='e') || (s[j]=='O') || (s[j]=='o') || (s[j]=='I') || (s[j]=='i') || (s[j]=='U') || (s[j]=='u') || (s[j]=='Y') || (s[j]=='y')){
            cout << "";
        }
        else{
            cout << "." << char(tolower(s[j]));
        }
    }
    return 0;
}
