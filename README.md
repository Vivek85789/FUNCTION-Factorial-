# FUNCTION-Factorial-

#include <iostream>
using namespace std;
int fact =1;
int factorialN(int n){
    for(int i=1;i<=n;i++){
      fact*=i;
    }
    return fact;
}


int main(){
    cout<<factorialN(5)<<endl;

    return 0;
}
