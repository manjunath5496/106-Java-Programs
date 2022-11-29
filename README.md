# Question 1

### **Question:**

> ***Write a program to print Hello World!.***

---------------------------------------

<strong>Solution: </strong>

```java language
public class MyClass {
public static void main(String[] args) {
System.out.print("Hello,world!");
}
}
```
----------------------------------------


# Question 2

### **Question:**

> ***Write a program to compute the perimeter and area of a rectangle.***

---------------------------------------

<strong>Solution: </strong>

```java language
public class MyClass {
public static void main(String[] args) {
int height = 8;
int width = 5;
int perimeter = 2 * (height + width);
System.out.println("Perimeter of the rectangle is: " + perimeter + " cm");
int area = height * width;
System.out.println("Area of the rectangle is: " + area + " square cm");
}
}
```
----------------------------------------


# Question 3

### **Question:**

> ***Write a program to compute the perimeter and area of a circle.***

---------------------------------------

<strong>Solution: </strong>

```java language
public class MyClass {
public static void main(String[] args) {
int radius = 4;
float perimeter = (float)(2 * 3.14 * radius);
System.out.printf("Perimeter of the circle is: %f cm\n", perimeter);
float area = (float)(3.14 * radius * radius);
System.out.printf("Area of the circle is: %f square cm\n", area);
}
}
```
----------------------------------------


# Question 4

### **Question:**

> ***Write a program that accepts two numbers from the user and calculate the sum of the two numbers.***

---------------------------------------

<strong>Solution: </strong>

```java language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b, sum;
System.out.print("\nEnter the first number: ");
a = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
b = STDIN_SCANNER.nextInt();
sum = a + b;
System.out.print("\nSum of the above two numbers is: " + sum);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 5

### **Question:**

> ***Write a program that accepts two numbers from the user and calculate the product of the two numbers.***

---------------------------------------

<strong>Solution: </strong>

```java language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b, mult;
System.out.print("\nEnter the first number: ");
a = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
b = STDIN_SCANNER.nextInt();
mult = a * b;
System.out.print("\nProduct of the above two numbers is: " + mult);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 6

### **Question:**

> ***Write a program that accepts three numbers and find the largest of three.***

---------------------------------------

<strong>Solution: </strong>

```java language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y, z;
System.out.print("\nEnter the first number: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
y = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the third number: ");
z = STDIN_SCANNER.nextInt();

// if x is greater than both y and z, x is the largest
if(x >= y && x >= z) {
System.out.print("\n" + x + " is the largest number.");
}

// if y is greater than both x and z, y is the largest
if(y >= x && y >= z) {
System.out.print("\n" + y + " is the largest number.");
}

// if z is greater than both x and y, z is the largest
if(z >= x && z >= y) {
System.out.print("\n" + z + " is the largest number.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------

# Question 7

### **Question:**

> ***Write a program that reads three floating values and check if it is possible to make a triangle with them. Also calculate the perimeter of the triangle if the entered values are valid.***

---------------------------------------

<strong>Solution: </strong>

```java language

import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
float x, y, z;
System.out.print("\nEnter the first number: ");
x = STDIN_SCANNER.nextFloat();
System.out.print("\nEnter the second number: ");
y = STDIN_SCANNER.nextFloat();
System.out.print("\nEnter the third number: ");
z = STDIN_SCANNER.nextFloat();

if(x < y + z && y < x + z && z < y + x) {
System.out.printf("\nPerimeter of the triangle is: %f\n", x + y + z);
} else {
System.out.print("\nIt is impossible to form a triangle.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------

# Question 8

### **Question:**

> ***Write a program that reads an integer between 1 and 7 and print the day of the week in English.***

---------------------------------------

<strong>Solution: </strong>

```java language

import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int day;
System.out.print("\nEnter a number between 1 to 7 to get the day name: ");
day = STDIN_SCANNER.nextInt();
switch(day) {
case 1:
	System.out.println("Monday");
	break;
case 2:
	System.out.println("Tuesday");
	break;
case 3:
	System.out.println("Wednesday");
	break;
case 4:
	System.out.println("Thursday");
	break;
case 5:
	System.out.println("Friday");
	break;
case 6:
	System.out.println("Saturday");
	break;
case 7:
	System.out.println("Sunday");
	break;
default:
	System.out.print("Enter a number between 1 to 7.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 9

### **Question:**

> ***Write a program to find the sum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```java language
public class MyClass {
public static void main(String[] args) {
int a, b, sum;
a = 1;
b = 2;
sum = a + b;
System.out.print("The sum of a and b = " + sum);
}
}
```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to find the square of a number.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int a, b;
a = 2;
b = (int)Math.pow(a, 2);
System.out.print("The square of a = " + b);
}
}
```
----------------------------------------

# Question 11

### **Question:**

> ***Write a program to find the greatest of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int a, b;
a = 2;
b = 3;
if(a > b) {
System.out.print("a is greater than b");
} else {
System.out.print("b is greater than a");
}
}
}
```
----------------------------------------

# Question 12

### **Question:**

> ***Write a program to print the average of the elements in the array.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int avg = 0, sum = 0;
int[] num = {16, 18, 20, 25, 36};
for(int i = 0; i < 5; i++) {
sum = sum + num[i];
avg = sum / 5;
}
System.out.println("Sum of the Elements in the array is: " + sum);
System.out.println("Average of the elements in the array is: " + avg);
}
}
```
----------------------------------------

# Question 13

### **Question:**

> ***Write a program that prints all even numbers between 1 and 25.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.println("Even numbers between 1 to 25:");
for(int i = 1; i <= 25; i++) {
if(i % 2 == 0) {
System.out.print(i + " ");
}
}
}
}
```
----------------------------------------


# Question 14

### **Question:**

> ***Write a program that prints all odd numbers between 1 and 50.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.println("Odd numbers between 1 to 50:");
for(int i = 1; i <= 50; i++) {
if(i % 2 != 0) {
System.out.print(i + " ");
}
}
}
}
```
----------------------------------------


# Question 15

### **Question:**

> ***Write a program to print the first 10 numbers starting from one together with their squares and cubes.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
for(int i = 1; i <= 10; i++) {
System.out.println("Number = " + i + " its square = " + (i * i) + " its cube = " + (i * i * i));
}
}
}
```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program:</br>
If you enter a character M</br>
Output must be: ch = M.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) throws Exception {
char c;
System.out.print("Enter a character: ");
c = (char)System.in.read();
System.out.println("ch = " + c);
}
}
```
----------------------------------------

# Question 17

### **Question:**

> ***Write a program to print the multiplication table of a number entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int n;
System.out.print("Enter any number: ");
n = STDIN_SCANNER.nextInt();
for(int i = 1; i <= 5; i++) {
System.out.println(n + " * " + i + " = " + (n * i));
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 18

### **Question:**

> ***Write a program to print the product of the first 10 digits.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int product = 1;
for(int i = 1; i <= 10; i++) {
product = product * i;
}
System.out.print("The product of the first 10 digits is: " + product);
}
}
```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to print whether the given number is positive or negative.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int a;
a = -35;
if(a > 0) {
System.out.print("Number is positive");
} else {
System.out.print("Number is negative");
}
}
}
```
----------------------------------------

# Question 20

### **Question:**

> ***Write a program to check the equivalence of two numbers entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y;
System.out.print("\nEnter the first number: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
y = STDIN_SCANNER.nextInt();
if(x - y == 0) {
System.out.print("\nThe two numbers are equivalent");
} else {
System.out.print("\nThe two numbers are not equivalent");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to print the remainder of two numbers entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b, c;
System.out.print("\nEnter the first number: ");
a = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
b = STDIN_SCANNER.nextInt();
c = a % b;
System.out.print("\n The remainder of " + a + " and " + b + " is: " + c);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to print the characters from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
for(byte i = 'A'; i <= 'Z'; i++) {
System.out.println((char)Byte.toUnsignedInt(i));
}
}
}
```
----------------------------------------


# Question 23

### **Question:**

> ***Write a program to print the length of the entered string.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;
public class MyClass {
public static void main(String[] args) {
String a;
Scanner scan = new Scanner(System.in);
System.out.print("Enter Your Name : ");
a = scan.nextLine();
System.out.println("The length of the String is: " + a.length());
}
}
```
----------------------------------------


# Question 24

### **Question:**

> ***Write a program to check whether the given character is a lower case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
char ch = 'a';
if(Character.isLowerCase(ch)) {
System.out.println("The given character is a lower case letter");
}
else {
System.out.println("The given character is a upper case letter");
}
}
}
```
----------------------------------------


# Question 25

### **Question:**

> ***Write a program to check whether the given character is a upper case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
char ch = 'A';
if(Character.isUpperCase(ch)) {
System.out.println("The given character is a upper case letter");
}
else {
System.out.println("The given character is a lower case letter");
}
}
}

```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to convert the lower case string to upper case string.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String a = "albert einstein";
System.out.println(a.toUpperCase());
}
}
```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program that takes a distance in centimeters and outputs the corresponding value in inches.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public final static double X = 2.54;
public static void main(String[] args) {
double inch, cm;
System.out.print("Enter the distance in cm: ");
cm = STDIN_SCANNER.nextDouble();
inch = cm / X;
System.out.printf("\nDistance of %.2f cms is equal to %.2f inches", cm, inch);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 28

### **Question:**

> ***Write a program to print the output:</br>
Einstein [0] = E</br>
Einstein [1] = I</br>
Einstein [2] = N</br>
Einstein [3] = S</br>
Einstein [4] = T</br>
Einstein [5] = E</br>
Einstein [6] = I</br>
Einstein [7] = N</br>***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) throws Exception{
int i;
char [] num = {'E' , 'I', 'N', 'S', 'T', 'E', 'I', 'N'};
for(i=0; i<8; i++)
System.out.println("Einstein [" + i + " ] = " + num[i]);
}
}
```
----------------------------------------


# Question 29

### **Question:**

> ***Write a program to print "Hello World" 10 times.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
for(int i = 1; i <= 10; i++) {
System.out.println("Hello World ");
}
}
}
```
----------------------------------------


# Question 30

### **Question:**

> ***Write a program to print first 5 numbers using do while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int i = 1;
do {
System.out.println(i++);
} while(i <= 5);
}
}
```
----------------------------------------



# Question 31

### **Question:**

> ***Write a program to check whether a character is an alphabet or not.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class Main {
public static void main(String[] args) {
Scanner scanner = new Scanner(System.in);
System.out.println("Enter any caracter: ");
char c = scanner.next().charAt(0);
if((c >= 'a' && c <= 'z') || (c >= 'A' && c <= 'Z')) {
System.out.println(c + " is a Alphabet.");
} else {
System.out.println(c + " is not a Alphabet.");
}
}
}
```
----------------------------------------


# Question 32

### **Question:**

> ***Write a program to check whether a entered number is even or odd.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a;
System.out.print("Enter any number: ");
a = STDIN_SCANNER.nextInt();
if(a % 2 == 0) {
System.out.print("The entered number is even");
} else {
System.out.print("The entered number is odd");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 33

### **Question:**

> ***Write a program to print the ASCII value of the given character.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
byte ch = 'A';
System.out.print("The ASCII value of " + ((char)Byte.toUnsignedInt(ch)) + " is: " + ch);
}
}
```
----------------------------------------


# Question 34

### **Question:**

> ***Write a program that will print all numbers between 1 to 50 which divided by a specified number and the remainder will be 2.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("Enter a number: ");
x = STDIN_SCANNER.nextInt();
for(int i = 1; i <= 50; i++) {
if(i % x == 2) {
System.out.println(i);
}
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 35

### **Question:**

> ***Write a program to determine whether two numbers in a pair are in ascending or descending order.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b;
System.out.print("\nEnter a pair of numbers (for example 22,12 | 12,22): ");
System.out.print("\nEnter the first number: ");
a = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
b = STDIN_SCANNER.nextInt();
if(a > b) {
System.out.print("\nThe two numbers in a pair are in descending order.");
} else {
System.out.print("\nThe two numbers in a pair are in ascending order.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------



# Question 36

### **Question:**

> ***Write a program that reads two numbers and divides one by the other. Specify "Division not possible" if that is not possible.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b;
float c;
System.out.print("\nEnter the first number: ");
a = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
b = STDIN_SCANNER.nextInt();
if(b != 0) {
c = (float)a / (float)b;
System.out.printf("\n%d/%d = %.1f", a, b, c);
} else {
System.out.println("\nDivision not possible.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 37

### **Question:**

> ***Write a program that will print all numbers between 1 to 50 which divided by a specified number and the remainder is equal to 2 or 3.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("Enter a number: ");
x = STDIN_SCANNER.nextInt();
for(int i = 1; i <= 50; i++) {
if(i % x == 2 || i % x == 3) {
System.out.println(i);
}
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------



# Question 38

### **Question:**

> ***Write a program that adds up all numbers between 1 and 100 that are not divisible by 12.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int x = 12, sum = 0;
for(int i = 1; i <= 100; i++) {
if(i % x != 0) {
sum += i;
}
}
System.out.println("\nSum: " + sum);
}
}
```
----------------------------------------


# Question 39

### **Question:**

> ***Write a program to calculate the value of x where x = 1 + 1/2 + 1/3 + … + 1/50.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
float x = 0;
for(int i = 1; i <= 50; i++) {
x += (float)1 / i;
}
System.out.printf("Value of x: %.2f\n", x);
}
}
```
----------------------------------------


# Question 40

### **Question:**

> ***Write a program that reads a number and find all its divisor.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("\nEnter a number: ");
x = STDIN_SCANNER.nextInt();
System.out.print("All the divisor of " + x + " are: ");
for(int i = 1; i <= x; i++) {
if(x % i == 0) {
System.out.print("\n" + i);
}
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 41

### **Question:**

> ***Write a program to find the incremented and decremented values of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int a, b, c, d, e, f;
a = 10;
b = 12;
c = a + 1;
d = b + 1;
e = a - 1;
f = b - 1;
System.out.print("\nThe incremented value of a =" + c);
System.out.print("\nThe incremented value of b =" + d);
System.out.print("\nThe decremented value of a =" + e);
System.out.print("\nThe decremented value of b =" + f);
}
}
```
----------------------------------------


# Question 42

### **Question:**

> ***Write a program to find square of a entered number using functions.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int answer;
answer = square();
System.out.print("The square of the entered number is: " + answer);
}

public static int square() {
int x;
System.out.print("Enter any number: ");
x = STDIN_SCANNER.nextInt();
return x * x;
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 43

### **Question:**

> ***Write a program that accepts principal amount, rate of interest, time and compute the simple interest.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int p, r, t, SI;
System.out.print("\nEnter the principal amount: ");
p = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the rate of interest: ");
r = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the time: ");
t = STDIN_SCANNER.nextInt();
SI = (p * r * t) / 100;
System.out.print("\nSimple interest is: " + SI);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 44

### **Question:**

> ***Write a program that swaps two numbers without using third variable.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b;
System.out.print("\nEnter the value for a: ");
a = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the value for b: ");
b = STDIN_SCANNER.nextInt();
System.out.print("\nBefore swapping: " + a + " " + b);
a = a + b;
b = a - b;
a = a - b;
System.out.print("\nAfter swapping: " + a + " " + b);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 45

### **Question:**

> ***Write a program to compute the area of a hexagon.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;
public class MyClass {
public static void main(String[] args) {
Scanner input = new Scanner(System.in);
System.out.print("Enter the length of a side of the hexagon: ");
double s = input.nextDouble();
double area = (6*(s*s))/(4*Math.tan(Math.PI/6));
System.out.print("The area of the hexagon is: " + area);
}
}

```
----------------------------------------

# Question 46

### **Question:**

> ***Write a program to print the output:</br>
body [b] = b</br>
body [o] = o</br>
body [d] = d</br>
body [y] = y</br>***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) throws Exception{
int i;
char [] body = {'b', 'o', 'd', 'y'};
for(i=0; i<4; i++) {
System.out.println("body [" + body [i] + " ] = " + body [i]);
}
}
}
```
----------------------------------------

# Question 47

### **Question:**

> ***Write a program to calculate the discounted price and the total price after discount</br>
Given:</br>
If purchase value is greater than 1000, 10% discount</br>
If purchase value is greater than 5000, 20% discount</br>
If purchase value is greater than 10000, 30% discount.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;
public class MyClass {
public static void main(String[] args) {
double pv;
System.out.print("Enter purchased value: ");
pv = STDIN_SCANNER.nextDouble();
if(pv > 1000) {
System.out.printf("\n Discount = %f", pv * 0.1);
System.out.printf("\n Total = %f", pv - pv * 0.1);
} else if(pv > 5000) {
System.out.printf("\n Discount = %f", pv * 0.2);
System.out.printf("\n Total = %f", pv - pv * 0.2);
} else {
System.out.printf("\n Discount = %f", pv * 0.3);
System.out.printf("\n Total = %f", pv - pv * 0.3);
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 48

### **Question:**

> ***Write a program to print the first ten natural numbers using while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int i = 1;
while(i <= 10) {
System.out.println(i++);
}
}
}
```
----------------------------------------


# Question 49

### **Question:**

> ***Write a program to shift inputted data by two bits to the left.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("Enter the integer from keyboard: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEntered value: " + x + " ");
System.out.print("\nThe left shifted data is: " + (x <<= 2) + " ");
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 50

### **Question:**

> ***Write a program to shift inputted data by two bits to the Right.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("Enter the integer from keyboard: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEntered value: " + x + " ");
System.out.print("\nThe right shifted data is: " + (x >>= 2) + " ");
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------



# Question 51

### **Question:**

> ***Write a program to calculate the exact difference between x and 21. Return three times the absolute difference if x is greater than 21.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("Enter the value for x: ");
x = STDIN_SCANNER.nextInt();
if(x <= 21) {
System.out.print(Math.abs(x - 21));
} else if(x >= 21) {
System.out.print(Math.abs(x - 21) * 3);
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 52

### **Question:**

> ***Write a program that reads in two numbers and determine whether the first number is a multiple of the second number.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y;
System.out.print("\nEnter the first number: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
y = STDIN_SCANNER.nextInt();
if(x % y == 0) {
System.out.println("\n" + x + " is a multiple of " + y + ".");
} else {
System.out.println("\n" + x + " is not a multiple of " + y + ".");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 53

### **Question:**

> ***Write a program to display the system time.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.format("\nCurrent Date time: %tc%n\n", System.currentTimeMillis());
}
}
```
----------------------------------------


# Question 54

### **Question:**

> ***Write a program to convert Celsius into Fahrenheit.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
float fahrenheit, celsius;
celsius = 36;
fahrenheit = (celsius * 9) / 5 + 32;
System.out.printf("\nTemperature in fahrenheit is:  %f", fahrenheit);
}
} 
```
----------------------------------------


# Question 55

### **Question:**

> ***Write a program that will examine two inputted integers and return true if either of them is 50 or if their sum is 50.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y;
System.out.print("\nEnter the value for x: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the value for y: ");
y = STDIN_SCANNER.nextInt();
if(x == 50 || y == 50 || x + y == 50) {
System.out.print("\nTrue");
} else {
System.out.print("\nFalse");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 56

### **Question:**

> ***Write a program that counts the even, odd, positive, and negative values among eighteen integer inputs.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, even = 0, odd = 0, positive = 0, negative = 0;
System.out.println("\nPlease enter 18 numbers:");
for(int i = 0; i < 18; i++) {
x = STDIN_SCANNER.nextInt();
if(x > 0) {
    positive++;
}
if(x < 0) {
	negative++;
}
if(x % 2 == 0) {
	even++;
}
if(x % 2 != 0) {
	odd++;
}
}
System.out.print("\nNumber of even values: " + even);
System.out.print("\nNumber of odd values: " + odd);
System.out.print("\nNumber of positive values: " + positive);
System.out.print("\nNumber of negative values: " + negative);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 57

### **Question:**

> ***Write a program to check whether the person is a senior citizen or not.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int age;
System.out.print("Enter age: ");
age = STDIN_SCANNER.nextInt();
if(age >= 60) {
System.out.print("Senior citizen");
} else {
System.out.print("Not a senior citizen");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 58

### **Question:**

> ***Write a program that reads a student's three subject scores (0-100) and computes the average of those scores.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
float score, totalScore = 0;
int subject = 0;
System.out.println("Enter three subject scores (0-100):");
while(subject != 3) {
score = STDIN_SCANNER.nextFloat();
if(score < 0 || score > 100) {
System.out.println("Please enter a valid score.");
} else {
totalScore += score;
subject++;
}
}
System.out.printf("Average score = %.2f\n", totalScore / 3);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 59

### **Question:**

> ***What results would the following programs produce?***

----------------------------------------

```java  language
public class MyClass {
public static void main(String[] args) {
for(int i = 1; i <= 5; i++) {
	if(i == 3) {
		break;
	}
System.out.println(i);
}
}
}
```
----------------------------------------

<strong>Solution: </strong>

```java  language
1
2
```
----------------------------------------

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.println(-7 + 9 * 5);
System.out.println((68+7) % 8);
System.out.println(50 + -6*5 / 5);
System.out.println(6 + 25 / 3 * 6 - 8 % 2);
}
}

```
----------------------------------------

<strong>Solution: </strong>

```java  language
38
3
44
54
```
----------------------------------------

```java  language
public class MyClass {
public static void main(String[] args) {
for(;;) {
System.out.println("This loop will run forever.");
}
}
}
```
----------------------------------------

<strong>Solution: </strong>

```java  language
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever. ......... 
```
----------------------------------------


```java  language
public class MyClass {
public static void main(String[] args) {
System.out.println((35.5 * 3.7 - 3.6 * 7.5) / (60.8 - 8.9));
}
}
```
----------------------------------------

<strong>Solution: </strong>

```java  language
2.010597302504817
```
----------------------------------------

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.println("linux");
System.exit(0);
System.out.println("php");
}
}
```
----------------------------------------

<strong>Solution: </strong>

```java  language
linux
```
----------------------------------------

```java  language
public class MyClass {
public static void main(String[] args) {
for(int i = 1; i <= 5; i++) {
	if(i == 3) {
		continue;
	}
System.out.print(i + "\n ");
}
}
}
```
----------------------------------------

<strong>Solution: </strong>

```java  language
1
2
4
5
```
----------------------------------------

```java  language
public class MyClass {
public static void main(String[] args) {
int a = 10, b = 20, c;
c = a < b ? a : b;
System.out.print(c);
}
}

```
----------------------------------------

<strong>Solution: </strong>

```java  language
10

```

----------------------------------------

```java  language
public class MyClass {
public final static int A = 15;
public static void main(String[] args) {
int x;
x = A;
System.out.print(x);
}
}

```
----------------------------------------

<strong>Solution: </strong>

```java  language
15

```

----------------------------------------


```java  language
public class MyClass {
public static void main(String[] args) {
for(int i = 1; i <= 3; i++) {
System.out.print((i & 1) != 0 ? "odd\n" : "even\n");
}
System.exit(0);
}
}

```
----------------------------------------

<strong>Solution: </strong>

```java  language
odd
even
odd

```

----------------------------------------


```java  language
public class MyClass {
public static void main(String[] args) {
double a, b;
a = -2.5;
b = Math.abs(a);
System.out.printf("|%.2f| = %.2f\n", a, b);
}
}

```
----------------------------------------

<strong>Solution: </strong>

```java  language
|-2.50| = 2.50

```

----------------------------------------

```java  language
public class MyClass {
public static void main(String[] args) {
int x = 12, y = 3;
System.out.println(Math.abs(-x - y));
}
}

```
----------------------------------------

<strong>Solution: </strong>

```java  language
15

```

----------------------------------------

```java  language
public class MyClass {
public static void main(String[] args) {
int x = 12, y = 3;
System.out.println(-(-x - y));
}
}
```
----------------------------------------

<strong>Solution: </strong>

```java  language
15

```

----------------------------------------

```java  language
public class MyClass {
public static void main(String[] args) {
int x = 12, y = 3;
System.out.println(x - -y);
}
}
```
----------------------------------------

<strong>Solution: </strong>

```java  language
15

```

----------------------------------------

```java  language
public class MyClass {
  static void myMethod() {
    System.out.println("Anyone who has never made a mistake has never tried anything new.");
  }

public static void main(String[] args) {
    myMethod();
    myMethod();
    myMethod();
}
}

```
----------------------------------------

<strong>Solution: </strong>

```java  language
Anyone who has never made a mistake has never tried anything new.
Anyone who has never made a mistake has never tried anything new.
Anyone who has never made a mistake has never tried anything new.

```

----------------------------------------


# Question 60

### **Question:**

> ***Write a program to find the size of an array.***

----------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int[] num = {11, 22, 33, 44, 55, 66};
int n = (int)num.length;
System.out.println("Size of the array is: " + n);
}
}
```
----------------------------------------

# Question 61

### **Question:**

> ***Write a program that prints a sequence from 1 to a given integer, inserts a plus sign between these numbers, and then removes the plus sign at the end of the sequence.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, i;
System.out.println("\nEnter a integer: ");
x = STDIN_SCANNER.nextInt();
if(x > 0) {
System.out.println("Sequence from 1 to " + x + ":");
	for(i = 1; i < x; i++) {
		System.out.print(i + "+");
		}
System.out.println(i);
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 62

### **Question:**

> ***Write a program to verify whether a triangle's three sides form a right angled triangle or not.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b, c;
System.out.println("Enter the three sides of a triangle: ");
a = STDIN_SCANNER.nextInt();
b = STDIN_SCANNER.nextInt();
c = STDIN_SCANNER.nextInt();
if(a * a + b * b == c * c || a * a + c * c == b * b || b * b + c * c == a * a) {
	System.out.println("Triangle's three sides form a right angled triangle.");
} else {
	System.out.println("Triangle's three sides does not form a right angled triangle.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 63

### **Question:**

> ***Write a program that will find the second-largest number among the user's input of three numbers.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b, c;
System.out.print("\nEnter the first number: ");
a = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
b = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the third number: ");
c = STDIN_SCANNER.nextInt();
if(a > b && a > c) {
	if(b > c) {
		System.out.print("\n" + b + " is second largest number among three numbers");
	} else {
		System.out.print("\n" + c + " is second largest number among three numbers");
	}
} else if(b > c && b > a) {
	if(c > a) {
		System.out.print("\n" + c + " is second largest number among three numbers");
	} else {
				System.out.print("\n" + a + " is second largest number among three numbers");
}
} else if(a > b) {
	   System.out.print("\n" + a + " is second largest number among three numbers");
	} else {
		System.out.print("\n" + b + " is second largest number among three numbers");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 64

### **Question:**

> ***Write a program to calculate the sum of the two given integer values. Return three times the sum of the two values if they are equal.***

----------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.print(myfunc(3, 5));
System.out.print("\n" + myfunc(6, 6));
}
public static int myfunc(int a, int b) {
return a == b ? (a + b) * 3 : a + b;
}
}
```
----------------------------------------

# Question 65

### **Question:**

> ***Write a program that accepts minutes as input, and display the total number of hours and minutes.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int mins, hrs;
System.out.print("Input minutes: ");
mins = STDIN_SCANNER.nextInt();
hrs = mins / 60;
mins = mins % 60;
System.out.println("\n" + hrs + " Hours, " + mins + " Minutes.");
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 66

### **Question:**

> ***Write a program to determine whether a positive number entered by the user is a multiple of three or five.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("\nEnter a number: ");
x = STDIN_SCANNER.nextInt();
if(x % 3 == 0 || x % 5 == 0) {
	System.out.print("True");
} else {
	System.out.print("False");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
    
```
----------------------------------------


# Question 67

### **Question:**

> ***Write a program to verify whether one of the two entered integers falls within the range of 100 to 200 included.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y;
System.out.print("\nEnter the value for x: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the value for y: ");
y = STDIN_SCANNER.nextInt();
if(x >= 100 && x <= 200 || y >= 100 && y <= 200) {
	System.out.print("True");
} else {
	System.out.print("False");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
    
```
----------------------------------------

# Question 68

### **Question:**

> ***Write a program to determine which of the two given integers is closest to the value 100. If the two numbers are equal, return 0.***

----------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.print(myfunc(86, 99));
System.out.print("\n" + myfunc(55, 55));
System.out.print("\n" + myfunc(65, 80));
}

public static int myfunc(int a, int b) {
int x = Math.abs(a - 100);
int y = Math.abs(b - 100);
return x == y ? 0 : (x < y ? a : b);
}
}
```
----------------------------------------

# Question 69

### **Question:**

> ***Write a program to determine whether a positive number entered by the user is a multiple of three or five, but not both.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;
public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("\nEnter a number: ");
x = STDIN_SCANNER.nextInt();
if(x % 3 == 0 ^ x % 5 == 0) {
	System.out.print("True");
} else {
	System.out.print("False");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
    
```
----------------------------------------


# Question 70

### **Question:**

> ***Write a program to determine whether two entered non-negative numbers have the same last digit.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y;
System.out.print("\nEnter the value for x: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the value for y: ");
y = STDIN_SCANNER.nextInt();
if(Math.abs(x % 10) == Math.abs(y % 10)) {
	System.out.print("True");
} else {
	System.out.print("False");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
    
```
----------------------------------------

# Question 71

### **Question:**

> ***Write a program to determine whether a given non-negative number is a multiple of 12 or it is one more than a multiple of 12.***

----------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int x = 43;
if(x % 12 == 0 || x % 12 == 1) {
	System.out.print("True");
} else {
	System.out.print("False");
}
}
}  
```
----------------------------------------


# Question 72

### **Question:**

> ***Write a program that accepts two integers and returns true when one of them equals 6, or when their sum or difference equals 6.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y;
System.out.print("\nEnter the value for x: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the value for y: ");
y = STDIN_SCANNER.nextInt();
if(x == 6 || y == 6 || x + y == 6 || Math.abs(x - y) == 6) {
	System.out.print("True");
} else {
	System.out.print("False");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
} 
```
----------------------------------------


# Question 73

### **Question:**

> ***Write a program to check whether it is possible to add two integers to get the third integer from three entered integers.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y, z;
System.out.print("\nEnter the value for x: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the value for y: ");
y = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the value for z: ");
z = STDIN_SCANNER.nextInt();
if(x == y + z || y == x + z || z == x + y) {
	System.out.print("True");
} else {
	System.out.print("False");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
    
```
----------------------------------------

# Question 74

### **Question:**

> ***Write a program that converts kilometers per hour to miles per hour.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
float kmph;
System.out.print("Enter kilometers per hour: ");
kmph = STDIN_SCANNER.nextFloat();
System.out.printf("\n%f miles per hour", kmph * 0.6213712);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 75

### **Question:**

> ***Write a program to calculate area of an ellipse.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public final static double PI = 3.141592;
public static void main(String[] args) {
float major, minor;
System.out.print("\nEnter length of major axis: ");
major = STDIN_SCANNER.nextFloat();
System.out.print("\nEnter length of minor axis: ");
minor = STDIN_SCANNER.nextFloat();
System.out.printf("\nArea of an ellipse = %.4f", PI * major * minor);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 76

### **Question:**

> ***Write a program to calculate the sum of three given integers. Return the third value if the first two values are equal.***

----------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.print("\n" + myfunc(11, 11, 11));
System.out.print("\n" + myfunc(11, 11, 16));
System.out.print("\n" + myfunc(18, 15, 10));
}

public static int myfunc(int a, int b, int c) {
if(a == b && b == c) {
	return 0;
}
if(a == b) {
	return c;
}
if(a == c) {
	return b;
}
if(b == c) {
	return a;
} else {
	return a + b + c;
}
}
}
```
----------------------------------------


# Question 77

### **Question:**

> ***Write a program to convert bytes to kilobytes.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
double bytes;
System.out.print("\nEnter number of bytes: ");
bytes = STDIN_SCANNER.nextDouble();
System.out.printf("\nKilobytes: %.2f", bytes / 1024);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 78

### **Question:**

> ***Write a program to convert megabytes to kilobytes.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
double megabytes, kilobytes;
System.out.print("\nInput the amount of megabytes to convert: ");
megabytes = STDIN_SCANNER.nextDouble();
kilobytes = megabytes * 1_024;
System.out.printf("\nThere are %f kilobytes in %f megabytes.", kilobytes, megabytes);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 79

### **Question:**

> ***Write a program to count the number of even elements in an integer array.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int[] array = new int[1000];
int arrSize, even = 0;
System.out.print("Input the size of the array: ");
arrSize = STDIN_SCANNER.nextInt();
System.out.println("Enter the elements in array: ");
for(int i = 0; i < arrSize; i++) {
	array[i] = STDIN_SCANNER.nextInt();
}

for(int i = 0; i < arrSize; i++) {
	if(array[i] % 2 == 0) {
		even++;
}
}
System.out.print("Number of even elements: " + even);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 80

### **Question:**

> ***Write a program to count the number of odd elements in an integer array.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int[] array = new int[1000];
int arrSize, odd = 0;
System.out.print("Input the size of the array: ");
arrSize = STDIN_SCANNER.nextInt();
System.out.println("Enter the elements in array: ");
for(int i = 0; i < arrSize; i++) {
	array[i] = STDIN_SCANNER.nextInt();
}

for(int i = 0; i < arrSize; i++) {
	if(array[i] % 2 != 0) {
		odd++;
}
}
System.out.print("Number of odd elements: " + odd);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 81

### **Question:**

> ***Write a program that will accept two integers and determine whether or not they are equal.***

----------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y;
System.out.println("Input the values for x and y: ");
x = STDIN_SCANNER.nextInt();
y = STDIN_SCANNER.nextInt();
if(x == y) {
	System.out.println("x and y are equal");
} else {
	System.out.println("x and y are not equal");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 82

### **Question:**

> ***Write a program to find the third angle of a triangle if two angles are given.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int angle1, angle2;
System.out.print("\nEnter the first angle of the triangle: ");
angle1 = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second angle of the triangle: ");
angle2 = STDIN_SCANNER.nextInt();
System.out.print("\nThird angle of the triangle is:  " + (180 - (angle1 + angle2)));
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 83

### **Question:**

> ***Write a program to determine whether a particular year is a leap year or not.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int year;
System.out.print("Enter the year: ");
year = STDIN_SCANNER.nextInt();
if(year % 400 == 0) {
	System.out.print("\n" + year + " is a leap year.");
} else if(year % 100 == 0) {
	System.out.print("\n" + year + " is a not leap year.");
} else if(year % 4 == 0) {
	System.out.print("\n" + year + " is a leap year.");
} else {
	System.out.print("\n" + year + " is not a leap year.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 84

### **Question:**

> ***Write a program that reads the candidate's age and determine a candidate's eligibility to cast his own vote.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int age;
System.out.print("\nEnter the age of the candidate: ");
age = STDIN_SCANNER.nextInt();
if(age < 18) {
	System.out.print("\nWe apologize, but the candidate is not able to cast his vote.");
	System.out.print("\nAfter " + (18 - age) + " year, the candidate would be able to cast his vote.");
} else {
	System.out.println("Congratulation! the candidate is qualified to cast his vote.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 85

### **Question:**

> ***Write a program to Convert Yard to Foot.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
float yard;
System.out.print("\nEnter the Length in Yard : ");
yard = STDIN_SCANNER.nextFloat();
System.out.printf("\n%f Yard in Foot is: %f", yard, 3 * yard);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 86

### **Question:**

> ***Write a program to convert gigabytes to megabytes.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
double gigabytes, megabytes;
System.out.print("\nInput the amount of gigabytes to convert: ");
gigabytes = STDIN_SCANNER.nextDouble();
megabytes = gigabytes * 1_024;
System.out.printf("\nThere are %f megabytes in %f gigabytes.", megabytes, gigabytes);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------

# Question 87

### **Question:**

> ***Write a program to Convert Kilogram to Pounds.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
float kg, lbs;
System.out.print("\nEnter Weight in Kilogram: ");
kg = STDIN_SCANNER.nextFloat();
lbs = (float)(kg * 2.20462);
System.out.printf("\n%f Kg = %f Pounds", kg, lbs);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 88

### **Question:**

> ***Write a program to Convert Kilogram to Ounce.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
float kg, ounce;
System.out.print("\nEnter Weight in Kilogram: ");
kg = STDIN_SCANNER.nextFloat();
ounce = (float)(kg * 35.274);
System.out.printf("\n%f Kg = %f Ounce", kg, ounce);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------

# Question 89

### **Question:**

> ***Write a program to Convert Pounds to Grams.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
float pound, gram;
System.out.print("\nEnter Weight in Pounds: ");
pound = STDIN_SCANNER.nextFloat();
gram = (float)(pound * 453.592);
System.out.printf("\n%f Pound = %f Grams", pound, gram);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 90

### **Question:**

> ***Write a program  to verify whether a triangle is valid or not using angles.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int angle1, angle2, angle3, sum;
System.out.print("\nEnter the first angle of the triangle: ");
angle1 = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second angle of the triangle: ");
angle2 = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the third angle of the triangle: ");
angle3 = STDIN_SCANNER.nextInt();
sum = angle1 + angle2 + angle3;
if(sum == 180) {
	System.out.print("\nThe triangle is valid.");
} else {
	System.out.print("\nThe triangle is not valid.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
} 
```
----------------------------------------

# Question 91

### **Question:**

> ***Write a program to add the digits of a two-digit number that is entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y, sum = 0;
System.out.print("\nEnter a two-digit number: ");
x = STDIN_SCANNER.nextInt();
y = x;
while(y != 0) {
	sum = sum + y % 10;
	y = y / 10;
}
System.out.print("\nSum of digits of " + x + " is: " + sum);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 92

### **Question:**

> ***Write a program to verify if a character you entered is a vowel or a consonant.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
Scanner scanner = new Scanner(System.in);
System.out.println("Enter a alphabet: ");
char ch = scanner.next().charAt(0);
if(ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u' ||
ch == 'A' || ch == 'E' || ch == 'I' || ch == 'O' || ch == 'U' ) {
System.out.println(ch + " is vowel");
}
else {
System.out.println(ch + " is consonant");
}
}
}


```
----------------------------------------


# Question 93

### **Question:**

> ***Write a program to find factorial of a number.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int fact = 1, num;
System.out.print("\nEnter a number: ");
num = STDIN_SCANNER.nextInt();
for(int i = 1; i <= num; i++) {
	fact = fact * i;
}
System.out.print("\nFactorial of " + num + " is: " + fact);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
} 
```
----------------------------------------

# Question 94

### **Question:**

> ***Write a program to print number of days in a month.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int[] x = {31, 28, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31};
int m;
System.out.print("\nEnter the month number: ");
m = STDIN_SCANNER.nextInt();
if(m > 12 || m < 1) {
	System.out.print("Invalid input");
} else if(m == 2) {
	System.out.print("\nNumber of days in month 2 is either 29 or 28");
} else {
	System.out.print("\nNumber of days in month " + m + " is " + x[m - 1]);
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 95

### **Question:**

> ***Write a program to concatenate multiple strings.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String x = "Stephen";  
String y = "-William";  
String z = "-Hawking";  
String c = x.concat(y).concat(z);  
System.out.println(c);  
}
}
```
----------------------------------------


# Question 96

### **Question:**

> ***Write a program to find maximum between two numbers.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b;
System.out.println("Enter two numbers: ");
a = STDIN_SCANNER.nextInt();
b = STDIN_SCANNER.nextInt();
if(a > b) {
	System.out.print("\n" + a + " is a maximum number");
} else {
	System.out.print("\n" + b + " is a maximum number");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```


```java  language
public class MyClass {
public static void main(String args[]) {
double a = 15.143;
double b = 15.656;
System.out.println(Math.max(a, b));
}
}
       
```

----------------------------------------



# Question 97

### **Question:**

> ***Write a program to compare two strings.***

---------------------------------------

<strong>Solution: </strong>

```java  language

public class MyClass {
public static void main(String[] args) {
String x = "Albert";
String y = "Albert";
if(x == y) {
    System.out.println("The 2 strings are equal.");
}
else {
    System.out.println("The 2 strings are not equal.");
}
}
}
```
----------------------------------------


```java  language

public class MyClass {
public static void main(String[] args) {
String x = "Albert";
String y = "Albert";
if(x.equals(y)) {
    System.out.println("The 2 strings are equal.");
}
else {
    System.out.println("The 2 strings are not equal.");
}
}
}
```
----------------------------------------

# Question 98

### **Question:**

> ***Write a program to convert the upper case string to lower case string.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String args[]) {
String x = new String("ALBERT EINSTEIN");
System.out.println(x.toLowerCase());
}
}

```
----------------------------------------


# Question 99

### **Question:**

> ***Write a program to find the quotient and remainder of a entered dividend and divisor.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int dividend, divisor;
System.out.print("\nEnter dividend: ");
dividend = STDIN_SCANNER.nextInt();
System.out.print("\nEnter divisor: ");
divisor = STDIN_SCANNER.nextInt();
System.out.println("\nQuotient = " + (dividend / divisor));
System.out.print("\nRemainder = " + (dividend % divisor));
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 100

### **Question:**

> ***Write a program to determine the Size of int, float, double and char.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main (String[] args) {
System.out.println("Size of int is: " + (Integer.SIZE/8) + " bytes.");
System.out.println("Size of char is: " + (Character.SIZE/8) + " bytes.");
System.out.println("Size of float is: " + (Float.SIZE/8) + " bytes.");
System.out.println("Size of double is: " + (Double.SIZE/8) + " bytes.");
}
}
```
----------------------------------------


# Question 101

### **Question:**

> ***Write a program to promt user for 4 times password check.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
String password = "123";
String inputPass;
Scanner input = new Scanner(System.in);
System.out.println("Enter Your Password: ");
inputPass = input.nextLine();
if (inputPass.equals(password)) {
System.out.println("Welcome User!");
}
else {
for(int i = 0; i < 3; i++) {
System.out.println("Enter Your Password:");
inputPass = input.nextLine();
}
System.out.println("Access Denied! Try again");
}
}
}

```
----------------------------------------


# Question 102

### **Question:**

> ***Write a program to find absolute value of a number.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int num;
System.out.println("Input a positive or negative number: ");
num = STDIN_SCANNER.nextInt();
System.out.println("\nAbsolute value of |" + num + "| is " + Math.abs(num));
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```


```java  language
public class MyClass {
public static void main(String args[]) {
int x = 820;
int y = -985;
float z = -8.1f;
System.out.printf( "Absolute Value of x: %d \n", Math.abs(x) );
System.out.printf( "Absolute Value of y: %d \n", Math.abs(y) );
System.out.printf( "Absolute Value of z: %f \n", Math.abs(z) );
}
}
```
----------------------------------------


# Question 103

### **Question:**

> ***Write a program that will accept a person's height in cm and classify the person based on it.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
float ht;
System.out.print("\nEnter the height (in cm): ");
ht = STDIN_SCANNER.nextFloat();
if(ht < 150.0) {
	System.out.println("Dwarf.");
} else if(ht >= 150.0 && ht < 165.0) {
	System.out.println("Average Height.");
} else if(ht >= 165.0 && ht <= 195.0) {
	System.out.println("Taller.");
} else {
	System.out.println("Abnormal height.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 104

### **Question:**

> ***Write a program to calculate the area of different geometric shapes using switch statements.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int choice;
float r, l, w, b, h;
System.out.print("\nEnter 1 for area of circle: ");
System.out.print("\nEnter 2 for area of rectangle: ");
System.out.print("\nEnter 3 for area of triangle: ");
System.out.print("\nEnter your choice : ");
choice = STDIN_SCANNER.nextInt();

switch(choice) {
case 1:
System.out.print("Enter the radius of the circle: ");
r = STDIN_SCANNER.nextFloat();
System.out.printf("\nArea of a circle is: %f", 3.14 * r * r);
break;
case 2:
System.out.println("Enter the length and width of the rectangle: ");
l = STDIN_SCANNER.nextFloat();
w = STDIN_SCANNER.nextFloat();
System.out.printf("\nArea of a rectangle is: %f", l * w);
break;
case 3:
System.out.println("Enter the base and height of the triangle: ");
b = STDIN_SCANNER.nextFloat();
h = STDIN_SCANNER.nextFloat();
System.out.printf("\nArea of a triangle is: %f", 0.5 * b * h);
break;
default:
System.out.print("\nPlease enter a number from 1 to 3.");
break;
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 105

### **Question:**

> ***Write a program to accept a character from the keyboard and print "Yes" if it is equal to y. Otherwise print "No".***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) throws Exception {
char ch;
System.out.println("Enter a character: ");
ch = (char)System.in.read();
if(ch == 'y' || ch == 'Y') {
System.out.println("Yes\n");
}
else {
System.out.println("No\n");
}	    
}
}

```
----------------------------------------

# Question 106

### **Question:**

> ***Write a program that uses bitwise operators to multiply an entered value by four.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
long x, y;
System.out.print("Enter a integer: ");
x = STDIN_SCANNER.nextLong();
y = x;
x = x << 2;
System.out.println(y + " x 4 = " + x);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 107

### **Question:**

> ***Write a program to check whether a number entered by the user is power of 2 or not.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("Enter a number: ");
x = STDIN_SCANNER.nextInt();
if(x != 0 && (x & x - 1) == 0) {
	System.out.print("\n" + x + " is a power of 2");
} else {
	System.out.print("\n" + x + " is not a power of 2");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 108

### **Question:**

> ***Write a program to determine whether a triangle is scalene, isosceles, or equilateral.***

---------------------------------------

<strong>Solution: </strong>

```java  language

import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int side1, side2, side3;
System.out.print("\nEnter the first side of the triangle: ");
side1 = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second side of the triangle: ");
side2 = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the third side of the triangle: ");
side3 = STDIN_SCANNER.nextInt();
if(side1 == side2 && side2 == side3) {
	System.out.print("\nThe given Triangle is equilateral.");
} else if(side1 == side2 || side2 == side3 || side3 == side1) {
	System.out.print("\nThe given Triangle is isosceles.");
} else {
	System.out.print("\nThe given Triangle is scalene.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 109

### **Question:**

> ***Write a program to print ASCII values of all the letters of the English alphabet from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
for(int i = 'A'; i <= 'Z'; i++) {
System.out.println("ASCII value of " + ((char)Byte.toUnsignedInt((byte)i)) + " = " + i);
}
}
}
```
----------------------------------------


# Question 110

### **Question:**

> ***Write a program to find sum of even numbers between 1 to n.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int num, sum = 0;
System.out.print("Enter a number: ");
num = STDIN_SCANNER.nextInt();
for(int i = 2; i <= num; i = i + 2) {
sum = sum + i;
}
System.out.print("\nSum of all even number between 1 to " + num + " is: " + sum);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 111

### **Question:**

> ***Write a program to find sum of odd numbers between 1 to n.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int num, sum = 0;
System.out.print("Enter a number: ");
num = STDIN_SCANNER.nextInt();
for(int i = 1; i <= num; i = i + 2) {
	sum = sum + i;
}
System.out.print("\nSum of all odd number between 1 to " + num + " is: " + sum);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 112

### **Question:**

> ***Write a program that accepts an integer (x) and computes the value of x+xx+xxx.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;
public class MyClass {
public static void main(String[] args) {
int x;
Scanner in = new Scanner(System.in);
System.out.print("Enter a number: ");
x = in .nextInt();
System.out.printf("%d + %d%d  + %d%d%d\n", x, x, x, x, x, x);
}
}

```
----------------------------------------

# Question 113

### **Question:**

> ***Write a program that allows you to enter the cost price and the selling price of a product and calculate profit or loss.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int cp, sp;
System.out.print("\nInput Cost Price: ");
cp = STDIN_SCANNER.nextInt();
System.out.print("\nInput Selling Price: ");
sp = STDIN_SCANNER.nextInt();
if(sp > cp) {
System.out.print("Profit = " + (sp - cp));
} else if(cp > sp) {
System.out.print("Loss = " + (cp - sp));
} else {
System.out.print("No Profit No Loss.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 114

### **Question:**

> ***Write a program that display the pattern like a right angle triangle using an asterisk.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int rows;
System.out.print("Input the number of rows: ");
rows = STDIN_SCANNER.nextInt();
for(int x = 1; x <= rows; x++) {
for(int y = 1; y <= x; y++) {
System.out.print("*");
}
System.out.println();
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 115

### **Question:**

> ***Write a program that display the pattern like a right angle triangle using a number.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int rows;
System.out.print("Input the number of rows: ");
rows = STDIN_SCANNER.nextInt();
for(int x = 1; x <= rows; x++) {
for(int y = 1; y <= x; y++) {
System.out.print(y);
}
System.out.println();
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 116

### **Question:**

> ***Write a program to determine the number and sum of all integers between 50 and 100 which are divisible by 2.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int sum = 0;
System.out.println("Numbers between 50 and 100, divisible by 2: ");
for(int x = 51; x < 100; x++) {
if(x % 2 == 0) {
	System.out.printf("%5d", x);
		sum += x;
}
}
System.out.print("\nThe sum: " + sum);
}
}
```
----------------------------------------

# Question 117

### **Question:**

> ***Write a program that uses the function to determine whether a entered number is even or odd.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static int myfunc(int x) {
	return x & 1;
}

public static void main(String[] args) {
int x;
System.out.print("Enter any number: ");
x = STDIN_SCANNER.nextInt();
if(myfunc(x) != 0) {
	System.out.print("\nThe number you entered is odd.");
} else {
	System.out.print("\nThe number you entered is even.");
}
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}

```
----------------------------------------


# Question 118

### **Question:**

> ***Write a program to find square root of a entered number.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x;
System.out.print("Enter any number: ");
x = STDIN_SCANNER.nextInt();
System.out.printf("Square root of %d is %.2f", x, Math.sqrt(x));
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 119

### **Question:**

> ***Write a program to find power of a entered number using library function.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y;
System.out.print("\nEnter the value for x: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the value for y: ");
y = STDIN_SCANNER.nextInt();
System.out.print("\n" + x + "^" + y + " = " + ((long)Math.pow(x, y)));
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 120

### **Question:**

> ***Write a program to read 10 numbers from the keyboard and find their sum and average.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;
public class MyClass {
public static void main(String [] args) {
int N1, N2, N3, N4, N5, N6, N7, N8, N9, N10, sum;
float X;
Scanner scan = new Scanner(System.in);
System.out.println("Enter any ten Numbers: ");
N1 = scan.nextInt();
N2 = scan.nextInt();
N3 = scan.nextInt();
N4 = scan.nextInt();
N5 = scan.nextInt();
N6 = scan.nextInt();
N7 = scan.nextInt();
N8 = scan.nextInt();
N9 = scan.nextInt();
N10 = scan.nextInt();
sum = N1 + N2 + N3 + N4 + N5 + N6 + N7 + N8 + N9 + N10;
X = sum /10;
System.out.println("The sum of 10 numbers = " + sum);
System.out.println("The average of 10 numbers = " + X);
}
}

```
----------------------------------------


# Question 121

### **Question:**

> ***Write a program to determine whether the given character is an alphanumeric character or not.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String x="abc123", y="abc.com";
System.out.println(x.matches("[a-zA-Z0-9]+"));
System.out.println(y.matches("[a-zA-Z0-9]+"));
}
}
	

```
----------------------------------------

# Question 122

### **Question:**

> ***Write a program to illustrate try-catch statement.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
try {
    int[] num = {1, 2, 3};
    System.out.println(num[3]);
  } catch (Exception e) {
    System.out.println("Something went wrong.");
}
}
}
```
----------------------------------------


# Question 123

### **Question:**

> ***Write a program to remove all whitespaces from a given string.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String x = "T    his is b  ett     er.";
x = x.replaceAll("\\s", "");
System.out.println(x);
}
}
```
----------------------------------------


# Question 124

### **Question:**

> ***Write a program to get current working directory.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String path = System.getProperty("user.dir");
System.out.println("Current Working Directory: " + path);
}
}

```
----------------------------------------


# Question 125

### **Question:**

> ***Write a program to split a sentence into words.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String x = "Hai this is Alan";
String [] y = x. split(" ", 3);
for(String i : y)
System. out. println(i);
}
}

```
----------------------------------------

# Question 126

### **Question:**

> ***Write a program to replace all occurrences of 'a' to 'e' in a string.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {  
public static void main(String args[]){  
String x="Java is a powerful general-purpose programming language.";  
String replaceString=x.replace('a','e'); 
System.out.println(replaceString);      
}   
}  

```
----------------------------------------

# Question 127

### **Question:**

> ***Write a program to check if the given string is empty or not.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String a="";  
String b="Java";  
System.out.println(a.isEmpty());  
System.out.println(b.isEmpty());  
}
}
```
----------------------------------------


# Question 128

### **Question:**

> ***Write a program to illustrate .join() method.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String a=String.join("-","Java","Programming");  
System.out.println(a);  
}
}
```
----------------------------------------



# Question 129

### **Question:**

> ***Write a program to calculate surface area of cube.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int side;
long area;
System.out.print("\nEnter the side of cube: ");
side = STDIN_SCANNER.nextInt();
area = 6 * side * side;
System.out.print("\nThe surface area of cube is: " + area);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 130

### **Question:**

> ***Write a program to subtract 2 numbers without using subtraction operator.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int x = 6, y = 3;
System.out.print(x + ~y + 1);
}
}
```
----------------------------------------


# Question 131

### **Question:**

> ***Write a program to add 2 numbers without using addition operator.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int x = 6, y = 3;
System.out.print(x - ~y - 1);
}
}
```
----------------------------------------

# Question 132

### **Question:**

> ***Write a program to multiply a number by 2 without using multiplication operator.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int x = 2;
System.out.print(x << 1);
}
}
```
----------------------------------------

# Question 134

### **Question:**

> ***Write a program to divide a number by 2 without using division operator.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
int x = 12;
System.out.print(x >> 1);
}
}
```
----------------------------------------

# Question 135

### **Question:**

> ***Write a program to calculate volume of sphere.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int radius;
float PI = 3.141592f;
System.out.print("\nEnter the radius of sphere: ");
radius = STDIN_SCANNER.nextInt();
float volume = (4 / 3) * (PI * radius * radius * radius);
System.out.printf("\nThe volume of sphere is: %f", volume);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 136

### **Question:**

> ***Write a program to calculate volume of ellipsoid.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int r1, r2, r3;
float PI = 3.141592f;
System.out.print("\nEnter the radius of the ellipsoid of axis 1: ");
r1 = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the radius of the ellipsoid of axis 2: ");
r2 = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the radius of the ellipsoid of axis 3: ");
r3 = STDIN_SCANNER.nextInt();
float volume = (4 / 3) * (PI * r1 * r2 * r3);
System.out.printf("\nThe volume of ellipsoid is: %f", volume);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------

# Question 137

### **Question:**

> ***Write a program that uses a for loop to determine power of a number entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int x, y;
long power = 1;
System.out.print("\nEnter the value for x: ");
x = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the value for y: ");
y = STDIN_SCANNER.nextInt();
for(int i = 1; i <= y; i++) {
	power = power * x;
}
System.out.print(x + " ^ " + y + " = " + power);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 138

### **Question:**

> ***Write a program to read three numbers and find average of numbers.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int a, b, c;
float avg;
System.out.print("\nEnter the first number: ");
a = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the second number: ");
b = STDIN_SCANNER.nextInt();
System.out.print("\nEnter the third number: ");
c = STDIN_SCANNER.nextInt();
avg = (float)(a + b + c / 3.0);
System.out.printf("\nAverage of three numbers is: %f", avg);
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------


# Question 139

### **Question:**

> ***Write a program to read integer "n" and print first three powers (n<sup>1</sup>, n<sup>2</sup>, n<sup>3</sup>).***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {
int n;
System.out.print("\nEnter a number: ");
n = STDIN_SCANNER.nextInt();
System.out.printf("%f, %f, %f", Math.pow(n, 1), Math.pow(n, 2), Math.pow(n, 3));
}
public final static Scanner STDIN_SCANNER = new Scanner(System.in);
}
```
----------------------------------------



# Question 140

### **Question:**

> ***Write a program to search the substring in a given string.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String name="Java is a powerful general-purpose programming language";  
System.out.println(name.contains("Java"));  
System.out.println(name.contains("programming"));  
System.out.println(name.contains("language"));  
}
}
```
----------------------------------------


# Question 141

### **Question:**

> ***Write a program to check if the string ends with a given suffix.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String a="Java Programming";  
System.out.println(a.endsWith("g"));  
}
}
```
----------------------------------------


# Question 142

### **Question:**

> ***Write a program to check if the string starts with the given prefix.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
String a="Java Programming";    
System.out.println(a.startsWith("j"));    
System.out.println(a.startsWith("J"));    
}
}
```
----------------------------------------


# Question 143

### **Question:**

> ***Write a program to check whether a character is alphabet, digit or special character.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.util.Scanner;
public class MyClass {
public static void main(String[] args) {
char ch;
Scanner x=new Scanner(System.in);
System.out.print("Enter a character: ");
ch=x.next().charAt(0);
if((ch>='a'&&ch<='z')||(ch>='A'&&ch<='Z')) {
System.out.println(ch+" is Alphabet.");
}
else if(ch>='0'&&ch<='9') {
System.out.println(ch+" is Digit.");
}
else {
System.out.println(ch+" is Special Character.");
}
}
}
```
----------------------------------------


# Question 144

### **Question:**

> ***Write a program to Check whether Java is installed on your computer.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.println("\nJava Version: "+System.getProperty("java.version"));
System.out.println("Java Runtime Version: "+System.getProperty("java.runtime.version"));
System.out.println("Java Home: "+System.getProperty("java.home"));
System.out.println("Java Vendor: "+System.getProperty("java.vendor"));
System.out.println("Java Vendor URL: "+System.getProperty("java.vendor.url"));
System.out.println("Java Class Path: "+System.getProperty("java.class.path")+"\n");
}
}
```
----------------------------------------



# Question 145

### **Question:**

> ***Write a program to Check whether Java is installed on your computer.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {
public static void main(String[] args) {
System.out.println("\nJava Version: "+System.getProperty("java.version"));
System.out.println("Java Runtime Version: "+System.getProperty("java.runtime.version"));
System.out.println("Java Home: "+System.getProperty("java.home"));
System.out.println("Java Vendor: "+System.getProperty("java.vendor"));
System.out.println("Java Vendor URL: "+System.getProperty("java.vendor.url"));
System.out.println("Java Class Path: "+System.getProperty("java.class.path")+"\n");
}
}
```
----------------------------------------


# Question 146

### **Question:**

> ***Write a program to get the current system environment and system properties.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.lang.*;
public class Main {
public static void main(String[] args) {
System.out.println("\nCurrent system environment:");
System.out.println(System.getenv());	 
System.out.println("\n\nCurrent system properties:");
System.out.println(System.getProperties());	
}
}
```
----------------------------------------


# Question 147

### **Question:**

> ***Write a program to measure how long code takes to execute in nanoseconds.***

---------------------------------------

<strong>Solution: </strong>

```java  language
import java.lang.*;
public class Main {
public static void main(String[] args) {    
long startTime = System.nanoTime(); 
int i;
System.out.println ("The first 5 natural numbers are:\n");
for (i=1;i<=5;i++) {      
	System.out.println(i);
}
long estimatedTime = System.nanoTime() - startTime;
System.out.println("Estimated time (in nanoseconds) to get the first 5 natural numbers: "+estimatedTime);
}
}
```
----------------------------------------


# Question 148

### **Question:**

> ***Write a program to replace the spaces of a string with a specific character.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class MyClass {    
public static void main(String[] args) {    
String a = "Java Programming";    
char ch = '-';    
a = a.replace(' ', ch);    
System.out.println("String after replacing spaces with the character '-': ");    
System.out.println(a);    
}    
}     
```
----------------------------------------



# Question 149

### **Question:**

> ***Write a program to count the total number of punctuations in a given string.***

---------------------------------------

<strong>Solution: </strong>

```java  language
public class Main {    
public static void main (String args[]) {    
int count = 0;    
String str = "Logic will get you from A to Z; imagination will get you everywhere.";    
for(int i = 0; i < str.length(); i++) {    
if(str.charAt(i) == '!' || str.charAt(i) == ',' || str.charAt(i) == ';' 
|| str.charAt(i) == '.' ||  str.charAt(i) == '?' || str.charAt(i) == '-' 
|| str.charAt(i) == '\'' || str.charAt(i) == '\"' || str.charAt(i) == ':') {    
count++;    
}    
}    
System.out.println("The total number of punctuations in a given string is: " +count);    
}    
}       
```
----------------------------------------


# Question 150

### **Question:**

> ***Write a program to convert Decimal to Hexadecimal.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {  
public static void main(String args[]){  
System.out.println(Integer.toHexString(10));  
System.out.println(Integer.toHexString(15));  
System.out.println(Integer.toHexString(289));  
}
}        
```
----------------------------------------

# Question 151

### **Question:**

> ***Write a program to convert Decimal to Octal.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {  
public static void main(String args[]){  
  
System.out.println(Integer.toOctalString(8));  
System.out.println(Integer.toOctalString(19));  
System.out.println(Integer.toOctalString(81));

}
    
}         
```
----------------------------------------

# Question 152

### **Question:**

> ***Write a program to convert Decimal to Binary.***

---------------------------------------

<strong>Solution: </strong>

```Java

public class MyClass {  
public static void main(String args[]){  
System.out.println(Integer.toBinaryString(10));  
System.out.println(Integer.toBinaryString(21));  
System.out.println(Integer.toBinaryString(31));  
}
    
}          
```
----------------------------------------

# Question 153

### **Question:**

> ***Write a program to convert Binary to Decimal.***

---------------------------------------

<strong>Solution: </strong>

```Java

public class MyClass {  
public static void main(String args[]){  
String a="1010";  
int decimal=Integer.parseInt(a,2);  
System.out.println(decimal);  
}
}           
```
----------------------------------------
# Question 154

### **Question:**

> ***Write a program to convert Hexadecimal to Decimal.***

---------------------------------------

<strong>Solution: </strong>

```Java

public class MyClass {  
public static void main(String args[]){  
String hex="a";  
int decimal=Integer.parseInt(hex,16);  
System.out.println(decimal);  
}
    
}            
```
----------------------------------------


# Question 155

### **Question:**

> ***Write a program to determine whether one string is a rotation of another.***

---------------------------------------

<strong>Solution: </strong>

```Java

public class MyClass {    
public static void main(String[] args) {    
String x = "abcde", y = "deabc";    
if(x.length() != y.length()){    
   System.out.println("Second string is not a rotation of first string");    
}    
else {    
    x = x.concat(x);    
            
        if(x.indexOf(y) != -1)    
            System.out.println("Second string is a rotation of first string");    
        else    
            System.out.println("Second string is not a rotation of first string");    
}    
}    
}                 
```
----------------------------------------


# Question 156

### **Question:**

> ***Write a program to illustrate the isNaN method.***

---------------------------------------

<strong>Solution: </strong>

```Java

public class MyClass {
public static void main(String args[]) {
        
/* The isNaN method returns true if the value is NaN. */
        
Float a = Float.NaN;
Float b = 6.0f;
System.out.println(a +" - " + a.isNaN()); 
System.out.println(a +" - " + Float.isNaN(a)); 
System.out.println(b +" - " + Float.isNaN(b));
}
}               
```
----------------------------------------

# Question 157

### **Question:**

> ***Write a program to illustrate the isNaN method.***

---------------------------------------

<strong>Solution: </strong>

```Java

public class MyClass {
public static void main(String args[]) {
        
/* The isNaN method returns true if the value is NaN. */
        
Float a = Float.NaN;
Float b = 6.0f;
System.out.println(a +" - " + a.isNaN()); 
System.out.println(a +" - " + Float.isNaN(a)); 
System.out.println(b +" - " + Float.isNaN(b));
}
}               
```
----------------------------------------

# Question 158

### **Question:**

> ***Write a program to Design Simple Calculator.***

---------------------------------------

<strong>Solution: </strong>

```Java

import java.util.Scanner;

public class MyClass {
public static void main(String[] args) {

char operator;
Double number1, number2, result;
Scanner input = new Scanner(System.in);
System.out.println("Choose an operator: +, -, *, or /");
operator = input.next().charAt(0);

System.out.println("Enter first number:");
number1 = input.nextDouble();

System.out.println("Enter second number:");
number2 = input.nextDouble();

switch (operator) {

      case '+':
        result = number1 + number2;
        System.out.println(number1 + " + " + number2 + " = " + result);
        break;

      case '-':
        result = number1 - number2;
        System.out.println(number1 + " - " + number2 + " = " + result);
        break;
  
      case '*':
        result = number1 * number2;
        System.out.println(number1 + " * " + number2 + " = " + result);
        break;
   
      case '/':
        result = number1 / number2;
        System.out.println(number1 + " / " + number2 + " = " + result);
        break;

      default:
        System.out.println("Invalid operator!");
        break;
    }

    input.close();
  }
}
  
            
```
----------------------------------------


# Question 159

### **Question:**

> ***Write a program to print Invert Triangle.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String args[]) {
int x = 9;
while(x > 0) {
    for(int i=1; i<=x; i++) {
        System.out.print(" "+x+" ");
    }
System.out.print("\n");
x--;
}
}
}

```
----------------------------------------










