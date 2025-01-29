# Method 1: Brute Force  
```cpp
#include <iostream>
using namespace std;


void NOP(){
    int num;
    cout <<"Enter the number: ";
    cin >> num;

    if(num>0){
        cout <<num <<" is positive number" <<endl;
    }else if(num<0){
        cout <<num <<" is negative number" <<endl;
    }else{
        cout <<num <<" is Zero number" <<endl;
    }
}


int main(){
    NOP();
  return 0;
}
```  
### Output:  
```  
Enter the number: 20
20 is positive number
```  