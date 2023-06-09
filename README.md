# Recurssion-using-back-tracking-
#include <iostream>
using namespace std;
int i = 0;
void Name(int i, int N)
{
    
    if (i < N) {
        return;
    }
     Name(i - 1, N);
    
    cout << i << endl;
      
    
}
int main()
{ 
    
    Name(35,1);
    return 0;
}
