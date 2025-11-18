# Introduction To Programming

## Tally Mark System / Counting using stones.

Before 10,000 years ago , humans used to count using the tally mark system.For example , if a person had 5 cows than it used to move the cows one by one ahead and carry one stone after moving a single cow.At evening ,to check whether the cows are equal or not.The person used to move the cows one by one and remove one stone after moving a single cow.
If some stones were left than it meant some cows were missing.

## Egypt Number System (Base 60) + Decimal + Arithmetics

It was not much efficient.
In base 60 , 60 different/unique symbols were used to represent the numeric values.

## Decimal Number System

It uses base 10.
{0,1,2,3,4,5,6,7,8,9}

**Note :** The counting system was invented by India.The counting system that we
used today was developed by India.Decimal number system is of Base 10.The
decimal number system became famous because the arithmetic operations with
decimal number system was very easy.Today we use the Decimal (Base 10) number
system.

## Why Decimal Number System became famous ?

1. It was very familiar with us.
2. It was easy to do arithmetic operations with decimal number system.

## Evolution Of Computer

Earlier to calculate the taxes and profit efficiently , accurately and fast , the humans needed something which was fast and accurate as well.So from there the need of computer arise.

Note : When first computer was created , than during that time the meaning of
the computer was "To Calculate".

Note : Earlier the computer was very big , the size of a building.Such computers
were used to call as mechanical computer.

## Mechanical Computer

A computer jisko run ya jisko start krne ya jisko
continously run krne k liye ek human chahiye.The size of the mechanical
computer was very big.Although there accuracy was good.It means ki is mechanical
computer ko run krne k liye ek human ki physical power need hoti h.

Mechanical Computer : It is a computer that is very big in size and needs someone
to operate it physically.
It was accurate but was not fast.

## Transistor

A transistor is a device that stores a charge and is of size 1 bit.A transistor
stores either 0 or 1.
A transistor stores a charge.If it stores charge than it means that it stores 1
else it stores 0.

Transistor and binary number system decreased the size of the computer and the
computers that we use today is because of transistor and binary number system
only.

A RAM contains a lot of transisitors that stores charge.

## How the size of computers decreased ?

Binary number system and transistor decreased the size of the computer.
With the help of binary numbers we can store more data inside the transistors than
any other number system.

## Binary Number System

Binary number system uses base 2.
A Binary number is a number which can be 0 or 1.Binary means 0 or 1.

```cpp
    0 + 0 = 0
    1 + 0 = 1
    0 + 1 = 1
    1 + 1 = 10 (10 is equal to 2)
```

We express 2 in binary number as 10 because we directly can't write 2 in binary
number.

## Decimal To Binary Conversion

**First Example**

```Let x = 27
27%2 = 1
13%2 = 1
6%2 = 0
3%2 = 1
1%2 = 1
0
```

Go from bottom to start

**011011 is equal to 27.**

**Second Example**

```
Let x = 43

43%2 = 1
21%2 = 1
10%2 = 0
5%2 = 1
2%2 = 0
1%2 = 1
0
```

Go from bottom to start

**0101011 is equal to 43**

## Verifying the above method

let x = 278 (it is in decimal format)

Converting it from decimal to decimal only.

270%10 = 8
27%10 = 7
2%10 = 2

Go from bottom to start (write remainders from bottom to start) 278

Hence , proved

Similarly , convert 278 into decimal only.

2*10^2 + 7*10^1 + 8\*10^0 = 200 + 70 + 8 ==> 278

## Binary To Decimal Conversion

Let b = 101

Convert b in decimal number system.

1*2^2 + 0*2^1 + 1\*2^0 = 4 + 0 + 1 = 5

## Decimal To Decimal Number.

```
let x = 278

270%10 = 8
27%10 = 7
2%10 = 2

==> 278
```

**Note :** RAM , Hard disk size is always in 2's power.

## What is Octadecimal Nubmer System ?

It is a number system that uses base 8.
{0,1,2,3,4,5,6,7} (Base 8)

## Decimal To Octa Conversion

Convert 23 into Octa number system

```
Let x = 23

23%8 = 7
2%8 = 2
```

Write remainders from bottom to start.

23 is equal to 27.

## Octa To Decimal Conversion

```
Let x = 27

2*8^1 + 7*8^0 = 16 + 7 = 23
```

## What is Hexadecimal Number System

It is a number system that uses base 16.
{0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F} (Base 16)

Here we use characters after 9 , because we want 16 different unique characters/symbols.

In hexadeciaml number system we use A to F instead of 11 to 16 because suppose
in hexadecimal number system B is represented by 11.

Now , when we will try to convert B into decimal than we don't get the same answer.

```
let x = 11 ; // x is in hexadecimal form
```

We are trying to convert it into decimal number system.
Here we are treating 11 separately and not B.

1*16^1 + 1*16^0 = 17

Here we are getting wrong answer because we are treating digits in 11 as separetely.
Here 11 is in hexadecimal form and we are converting into decimal only so we
should get the answer as 11 but we are getting 17.This is because in 11 we have two digits and they are treated separately.

So to solve this problem , after 9 digit or symbol we use characters to treat the
two digits as single entity.

If we use B instead of 11 than

16^0 \* B(11) = 11

So that's why we use capital letters instead of decimal numbers from 11 to 16 in
hexadecimal number system.

Here in above we are converting hexadecimal number to hexadecimal only.

In IP address also the hexdecimal number system is used.

Note : Decimal ko kisi aur base m convert krna ho to jis base m convert krna h usse divide krte rho and remainder ko store krte rho.

Kisi aur base ko agar decimal m convert krna h to us base ki value ko 10 ki power se
multiple kro and add kro.

## Convert Decimal To Hexadecimal

```
Let x = 11

11%16 = 11

Since we know that in hexadecimal number system 11 is nothing but B.

So 11 is hexadecimal is B.
```

## Convert Hexadecimal To Decimal

```
Let x  = AC2

A*16^2 + C*16^1 + 2*16^0 = 10*16*16 + 12*16 + 2
```

Note : Computer stores everything in binary number system.
Computer understands only binary number system.

## What is the advantage of binary number system Or Why binary number system is used in computers ?

Binary number system and transistors decreased the size of the computers.With the help
of binary number system ,we can store a large amount of data inside the transistors than any other number system.

We can use other number system in computer to store the data but we will not be
able to store as much data that we store with the help of binary number system.

## Suppose we have 4 transistors

Total different numbers we can store inside it = 2<sup>4</sup>

Maximum number we can store = 2<sup>4</sup> -1 (we are including 0 that's why)

In computer we use binary number system and not other number system because with the help of binary number system we can store a large amount of data inside the transistors.

## Moore's Law ?

This law states that every two years , the capacity of the transistors will get
doubled.This was said by him around 1965.

Ex : suppose we have a RAM which have 1MB size.Than after two years the RAM
size will increase to 2MB , than next 2 years it will be 4MB and so on.
This thing is still true.

Every year the capacity of the transistors are increasing and this is because the
size of the transistors are going decreasing year by year.

## Why we need programming language ?

To interact with computer or to perform some task from computer , we need a way.
Computer only understands binary language and it is difficult to learn , understand and write the binary language.
To solve this problem we write code in high level language and convert this code to machine language using compiler.

The first language that came into picture was assembly level language.It was also
very difficult.Here , commands like ADD , SUB , MOV were used.Assembler was used
to convert the assembly level language into machine level language.
After assembly level language , the mid level and high level language came into the
picture.

## Speed Of Languages

Machine Language > Assembly Language > High Level Language

Assembly and high level languages are slow because they are first converted to machine code and than they are executed.

## High Level Language

It is more human redeable and easier to learn and understand.
Ex : JavaScript , Go

## Low Level Language

**Assembly language :** It is little bit difficult and uses commands like MOV , ADD , SUB etc.

Ex :

```
ADD 5
MOV A C
```

Ex : assembly level language.

## Machine Language

It is the language which is just 0 and 1.

## Compiler

A program that converts the high level language code into machine level language code.

## Assembler

A program that converts the assembly level language code into machine language code.

## Why we need DSA ?

1. To improve problem solving skills.
2. To store and fetch the data efficiently and fast.
