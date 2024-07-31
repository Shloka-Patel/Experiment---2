# Experiment---2

Aim -> To study and implement C++ Program Structure (Data Types). <br> 

Software -> Visual Studio Code <br> 

Theory -> Data types tell the variables about the type of data that they can store. <br> 
          C++ supports many data types such as: <br> 
          1. Primary data types <br> 
          2. Derived data types<br> 
          3. User-defined data types <br> 
          To find the size of data type we use "sizeof" command. It tells about the number of bytes occupied by any variable in the memory of a computer. <br> 
          Storage class in C++ determines the characteristics of a variable. <br> 
          C++ has 5 types of storage classes: <br>
          1. Auto<br> 
          2. Extern<br> 
          3. Mutable<br> 
          4. Register<br> 
          5. Static<br> 

Code: <br> 

(A) 
```
#include<iostream>
using namespace std;
int main() {
    int intType;
    char charType;
    signed char signedcharType;  
    unsigned char unsignedcharType;
    float floatType;
    double doubleType;
    long double longdoubleType;
    bool boolType;
    long int longintType;
    short int shortintType; 
    cout<<"Size of int is:"<<sizeof(intType)<<"\n";          //Output - Size ofint is:4
    cout<<"Size of char is:"<<sizeof(charType)<<"\n";           //Size of char is:1
    cout<<"Size of signed char is:"<<sizeof(signedcharType)<<"\n";  //Size of signed char is:1
    cout<<"Size of unsigned char is:"<<sizeof(unsignedcharType)<<"\n";     //Size ofunsigned char is:1
    cout<<"Size of float is:"<<sizeof(floatType)<<"\n";                 //Size of float is:4
    cout<<"Size of double is:"<<sizeof(doubleType)<<"\n";              //Size of double is:8 
    cout<<"Size of long double is:"<<sizeof(longdoubleType)<<"\n";        //Size of long double is:12
    cout<<"Size of bool is:"<<sizeof(boolType)<<"\n";                    //Size of bool is:1
    cout<<"Size of long int is:"<<sizeof(longintType)<<"\n";                //Size of long int is:4
    cout<<"Size of short int is:"<<sizeof(shortintType)<<"\n";          //Size of short int is:2 
return 0;
}
```
(B) <br> 
```

Output<br> 

(A) <br> 
![exp2A](https://github.com/Shloka-Patel/Experiment---2/blob/main/Output_2A.png) <br>

(B) <br> 
![exp2B](https://github.com/Shloka-Patel/Experiment---2/blob/main/Output_2B.png) <br> 

(C) <br> 
![exp2C](https://github.com/Shloka-Patel/Experiment---2/blob/main/Output_2C.png) <br> 

COnclusion -> I learnt about different data types and storage classes of C++. 

          
          
