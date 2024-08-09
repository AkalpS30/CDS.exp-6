# CDS.exp-6
# EXP-6

## Aim:
**To study and implement C++ decision making statements.**

## Software:
`Microsoft VSCode`

## Theory:
Decision making statements in C++ are the conditional statements that are used to execute codes based on some given conditions. These are crucial for controlling the flow of a program and making it responsive to different inputs

**Types of Decision-Making Statements:**
`if Statement`: Executes a block of code if a specified condition is true.
`if-else Statement`: Provides an alternative block of code to execute if the condition is false.
`Switch Statement`: Allows a variable to be tested for equality against a list of values. Each value is called a "`case`," and the variable is compared with each case value.
`Nested if-else`: You can nest if-else statements within each other for more complex conditions.

## Code: 6A *(for loop)*
```
//AKALP SARKAR
//E&TC B2
//EXP 6A
//23070123116
#include<iostream>
using namespace std;
int main(){
    int i;
    for (i=0;i<10;i++) {
    cout<<"HELLO WORLD("<<i+1<<")"<<"\n";
    }
    return 0;
}
```
## Output 6a
![output6a](https://github.com/user-attachments/assets/25392532-8933-46b4-9fdb-cba13bca8dde)

## Code: 6B *(while loop)*
```
//AKALP SARKAR
//E&TC B2
//EXP 6B
//23070123116
#include<iostream>
using namespace std;

int main()
{
    int i;
    cout<<"Enter a number: "<<"\n";
    cin>>i;
    while(i<=10)
    {
        cout<<" "<<"\n"<<i++;
    
    }
    return 0;
}
```
## Output 6b
![output6b](https://github.com/user-attachments/assets/366b0ef9-f7d7-4bf6-9c6f-5b677faa1a16)
## Code: 6C *(do while loop)*
```
//AKALP SARKAR
//ENTC B2
//EXP 6C
//23070123116
#include<iostream> 
using namespace std;

int main() 
{
    int a=0;
    do {
        cout<< a << "\n";
        a=a+2;
    }
    while (a<=50); 
    return 0;
}
```
## Output 6c
![output6c](https://github.com/user-attachments/assets/000d70ab-5d01-44b1-9e62-c36fe0e413ea)
## Code: 6D *(for while loop)*
```
//AKALP SARKAR
//ENTC B2
//EXP 6D
//23070123116

#include<iostream>
using namespace std;
int main(){
    int i,j,k=0,n;
    cout<<"Enter number of rows:";
    cin>>n;
    for(i=1;i<=n;i++)
    {
        for (j=1;j<=(n-1);j++)
        {
            cout<<" ";
        }
        while(k!=(2*i-1))
        {
            cout<<"* ";
            k++;
        }
        k=0;
        }
        cout<<"end1";
    
} 
```
## Output 6d
![output6d](https://github.com/user-attachments/assets/d5ea4700-7537-4f23-9864-287b09eb7e8a)

## Code: 6E *(Nested For Loop)*
```
//AKALP SARKAR
//E&TC B2
//EXP 6E
//23070123116
#include<iostream>
using namespace std;

int main()
{
    int a[3][3],s=0,i,j;
    for(i=0;i<3;i++)
    {
        for(j=0;j<3;j++)
        {
            cout<<"Enter any number for index number: "<<i<<j;
            cin>>a[i][j];
            s=s+a[i][j];
        }
    }
    cout<<"The sum of elements of matrix is:"<<s;
    return 0;
}

```
## Output 6e
![output6e](https://github.com/user-attachments/assets/e28eb1ff-2ed9-4770-b8da-377a2abfeb54)
## Code: 6F *(Nested While Loop)*
```
//AKALP SARKAR
//E&TC B2
//EXP 6F
//23070123116
#include<iostream>
#include <iostream>
using namespace std;

int main() {
    int i = 1;
    while (i <= 5) {
        int j = 1;
        while (j <= 5) {
            cout << "* ";
            ++j;
        }
        cout << endl;
        ++i;
    }

    return 0;
}
```
## Output 6f
![output6f](https://github.com/user-attachments/assets/0387e6fe-6aba-4c10-a09d-01619c8c334e)
## Code: 6G *(Nested Do While Loop)*
```
//AKALP SARKAR
//E&TC B2
//EXP 6G
//23070123116
#include <iostream>
int main() {
    int i = 1; 
    do {
        int j = 1;  
        do {
            std::cout << i * j << "\t";  
            ++j;  
        } while (j <= 10);

        std::cout << std::endl;  
        ++i;  
    } while (i <= 10);

    return 0;
}
```
## Output 6g
![output6g](https://github.com/user-attachments/assets/784ff699-0b60-46e6-a13d-9d5527016f7e)

## Conclusion:
I learnt about the different decision making statements of C++ and performed tasks based on those conditions.



