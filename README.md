# Quiz 1
***
###### Questions 1-20 = 4 points each
###### Question 21 = 20 points
***

#### Question 1    Answer : d
Which are the keywords not in use?
> a) transient and volatile

> b) instanceof and assert

> c) strictfp and synchronized

> d) const and goto

***
#### Question 2.   Answer : false
Keywords are non-reserved word in java

> true

> false

***
#### Question 3    Answer : b
Which method is the entry point for Java programs?

> a) void main (String [] args){} 

> b) public static void main (String [] args){} 

> c) static void main (String [] args){} 

> d) public void main (String [] args){}

***
#### Question 4.    Answer : c
Data is stored in ............

> a) Space in memory

> b) Data

> c) Variable

> d) Data Type

***
#### Question 5.    Answer : True
Datatypes impacts on memory allocation

> True

> False

***
#### Question 6.    Answer : a
Identify correct Output:
```
public class Test_Variable {
    public static void main(String[] args){
        int value = 10;
        int value1=”java”;
        System.out.println(value);
        System.out.println(value1);
    }
}
```

> a) Type Mismatch

> b) Runtime Error

> c) 10

> d) 10 and java

***
#### Question 7.    Answer : True
Variable name is case-sensitive.

> True

> False

***
#### Question 8.  Answer : False
Space is permitted in variable name.

> True

> False

***
#### Question 9    Answer : d
What is the range of short?

> a) -32768 to 32768

> b) -32769 to 32767

> c) -32769 to 32768

> d) -32768 to 32767

***
#### Question 10. Answer : c
Which suffix is used while declaring a long data type?

> a) S

> b) B

> c) L

> d) l

***
#### Question 11    Answer : d
Identify correct Output:
```
public class TestIntDataType{
public static void main(String[] args){
    byte value = -128;
    System.out.println(value);
    }
}
```

> a) Compile time error

> b) Run time error

> c) Type Mismatch error

> d) -128

***
#### Question 12.  Answer : a    
Identify correct Output:
```
public class TestFloat{
public static void main(String[] args){
    int number1= 10.128952248;
    float number2 = 10.128952248f;
    double number3 = 10.128952248d;
 
    System.out.println(number1);
    System.out.println(number2);
    System.out.println(number3);
    }
}
```

> a) Compile time error

> b) 
> 10.128952248
> 10.128952248
> 10.128952248

> c)
> 10
> 10.12895224
> 10.128952248

> d)
> 10
> 10.1289522
> 10.128952248

***
#### Question 13. Answer : d
What is Precision of float type variable?

> a) 8 decimals

> b) 32 decimals

> c) 16 decimals

> d) 7 decimals

***
#### Question 14. Answer : a
Identify the data type with the following sentences:

1. The length should be one

2. Enclosed between quotes

3. Any character on the keyboard is allowed

> a) char

> b) boolean

> c) int

> d) String

***
#### Question 15.   Answer : False
In Java, boolean datatype can be represented by 1 or 0.

> True

> False

***
#### Question 16.   Answer : b
How to cast 64-bit datatype into 32-bit datatype?

> a) Implicit Typecasting

> b) Explicit Typecasting

> c) Widening Typecasting

***
#### Question 17. Answer : d
In implicit Typecasting, what is the correct sequence of data type compatibility?

> a) double -> float->long->int->short->byte

> b) byte->int->short->long->float->double

> c) byte-> long >int->short-> float->double

> d) byte->short->int>long->float->double

***
#### Question 18. Answer : e
In Java, we can create BigDecimal objects of which of the following types?

> a) int

> b) long

> c) character array

> d) String

> e) double

> f) All of the above

***
#### Question 19.  Answer : False
The floating-point data types are used for calculating accurate precise values in a financial calculation.

> True

> False

***
#### Question 20.   Answer : c
BigDecimal is a part of which Java package?

> a) java.util

> b) java.lang

> c) java.math

> d) java.io

***
#### Question 21. 
Solve an equation:

a² + 2ab + b²

Create 3 variables whereby...
```
variable a --> int a = any integer number
variable b --> float b = any decimal number
variable value --> datatype?? = a² + 2ab + b²
```


Answer : 


public class hello {
	public static void main(String[] args) {
		int a = 3;
		float b = 5.5f;
		double value = a*a + 2*a*b + b*b ;
		System.out.println(value);
        }
       }
