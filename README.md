# Error-Handling-In-String-Parsing
#include <map>
#include <set>
#include <list>
#include <cmath>
#include <ctime>
#include <deque>
#include <queue>
#include <stack>
#include <string>
#include <bitset>
#include <cstdio>
#include <limits>
#include <vector>
#include <climits>
#include <cstring>
#include <cstdlib>
#include <fstream>
#include <numeric>
#include <sstream>
#include <iostream>
#include <algorithm>
#include <unordered_map>

using namespace std;


int main(){
    string S;
    cin >> S;
    try{
        int z=stoi(S);   //stoi function is inbuilt in c++ for string parsing
        cout<<z;
    }
    catch(exception e){
        cout<<"Bad String";
    }
    

    return 0;
}
