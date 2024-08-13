# Experiment---2

### Aim
To study and implement C++ Program Structure (Data Types). <br> 

# Software 
Visual Studio Code <br> 

# Theory
Data types tell the variables about the type of data that they can store. <br> 
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

# Code: <br> 

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
    cout<<"Size of int is:"<<sizeof(intType)<<"\n";          
    cout<<"Size of char is:"<<sizeof(charType)<<"\n";          
    cout<<"Size of signed char is:"<<sizeof(signedcharType)<<"\n";  
    cout<<"Size of unsigned char is:"<<sizeof(unsignedcharType)<<"\n";     
    cout<<"Size of float is:"<<sizeof(floatType)<<"\n";                
    cout<<"Size of double is:"<<sizeof(doubleType)<<"\n";             
    cout<<"Size of long double is:"<<sizeof(longdoubleType)<<"\n";       
    cout<<"Size of bool is:"<<sizeof(boolType)<<"\n";                   
    cout<<"Size of long int is:"<<sizeof(longintType)<<"\n";               
    cout<<"Size of short int is:"<<sizeof(shortintType)<<"\n";         
return 0;
}
```
(B) <br> 
```

#include<iostream>
using namespace std;
int main() {
    int a;
    char b;
    signed char c;
    unsigned char d;
    float e;
    double f;
    long double g;
    bool h;
    cout<<"Enter an integer: ";                     
    cin>>a;
    cout<<"Size of int is:"<<sizeof(a)<<"\n";        

    cout<<"Enter a character: ";                   
    cin>>b;
    cout<<"Size of char is:"<<sizeof(b)<<"\n";        

    cout<<"Enter a character: ";                    
    cin>>c;
    cout<<"Size of signed char is:"<<sizeof(c)<<"\n";     

    cout<<"Enter a character: ";                        
    cin>>d;
    cout<<"Size of unsigned char is:"<<sizeof(d)<<"\n";  

    cout<<"Enter a number: ";                             
    cin>>e;
    cout<<"Size of float is:"<<sizeof(e)<<"\n";           
    

    cout<<"Enter a number: ";                            
    cin>>f;
    cout<<"Size of double is:"<<sizeof(f)<<"\n";         

    cout<<"Enter a number: ";                           
    cin>>g;
    cout<<"Size of long double is:"<<sizeof(g)<<"\n";   

    cout<<"Enter a bool value: ";                      
    cin>>h;
    cout<<"Size of bool is:"<<sizeof(h)<<"\n";            
return 0;
}
```

(C)<br>
```
#include<iostream>
using namespace std;

int main() {
    int a;
    cout<<"Enter a number: ";                       
    cin>>a;
    cout<<"\nInteger= "<<a<<" and size is "<<sizeof(a)<<" bytes.";  

    register int b;
    cout<<"\nEnter a number: ";                                     
    cin>>b;
    cout<<"\nRegister= "<<b<<" and size is "<<sizeof(b)<<" bytes.";   

    static int d;
    cout<<"\nEnter any number: ";                                      
    cin>>d;
    cout<<"\nStatic= "<<d<<" and size is "<<sizeof(d)<<" bytes.";      

    return 0;
}
``` 

# Output<br> 

(A) <br> 
![exp2A](https://github.com/Shloka-Patel/Experiment---2/blob/main/Output_2A.png) <br>

(B) <br> 
![exp2B](https://github.com/Shloka-Patel/Experiment---2/blob/main/Output_2B.png) <br> 

(C) <br> 
![exp2C](https://github.com/Shloka-Patel/Experiment---2/blob/main/Output_2C.png) <br> 

# Conclusion 
I learnt about different data types and storage classes of C++. 

          
          
