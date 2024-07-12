# c-intro
intro,syntax, varaible ,identifiers, constants , user input

 1st ) **MY FIRST PROGRAM**
 
#include <iostream> //header file library that lets us work with input and output objects
using namespace std; //use names for objects and variables from the standard library.
int main(){ //function inside curly bracket
cout<<hello world;//cout for print output
return 0;
}
 2) **VARIABLES**: different types of variable 

.int - stores integers (whole numbers), without decimals, such as 123 or -123
.double - stores floating point numbers, with decimals, such as 19.99 or -19.99
.char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
.string - stores text, such as "Hello World". String values are surrounded by double quotes
.bool - stores values with two states: true or false

 **To create a variable, specify the type and assign it a value:**
 
 type variableName = value;

 int myNum = 15 ;
 cout<< myNum;

  .declare multiple variable
  int x= 5,y = 6,z= 50;
  cout<<x + y + z;

  3)**IDENTIFIERS**  (These unique names are called identifiers.)

 int minutesperHour = 60;
  int m= 60; 

The general rules for naming variables are:

. Names can contain letters, digits and underscores
. Names must begin with a letter or an underscore (_)
. Names are case-sensitive (myVar and myvar are different variables)
. Names cannot contain whitespaces or special characters like !, #, %, etc.
. Reserved words (like C++ keywords, such as int) cannot be used as names

4) **CONSTANT**: unchangeable read only 

const int myNum = 15;
myNum = 10;

**You should always declare the variable as constant when you have values that are unlikely to change:
const int minutesPerHour = 60;  
const float PI = 3.14;
 
 5)**USER INPUT**  
 
 int x;
 cout<<" type a number :";        // type a number and press enter 
 cin>> x;                        // get user input from the keyboard
 cout<<"your number is: "<<x ;  //display the input values

  **CREATING A SIMPLE CALCULATOR**
          (the user must input two numbers. Then we print the sum by calculating (adding) the 
                                        two numbers:)
           
  #include<iostram>
  using namespace std;
  int main(){
  int x, y;
  int sum;
  cout<<"type a number: ";
  cin>>x;
  cout<<"type a number : ";
  cin>>y;
  sum = x + y ;
  cout<<"sum is : "<<sum ;
  return 0;
  }
  
 
