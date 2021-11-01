# Question 1

### **Question:**

> ***Write a program to print Hello World!.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
System.out.println("Hello, World!");
}
}
```
----------------------------------------

# Question 2

### **Question:**

> ***Write a program to find the area of a circle.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main (String [] args) {
int r, area;
r = 2;
area = 3.14 * r * r;
System.out.println("The area of the circle = " + area);
}
}
```

```Java
import java.util.Scanner;
public class MyClass {
	public static void main(String[] args) {
         Scanner s= new Scanner(System.in);
        
         System.out.println("Enter the radius:");
         double r= s.nextDouble();
         double  area=3.14 * r * r;
         System.out.println("Area of Circle is: " + area);   
	}
}

```

----------------------------------------



# Question 3

### **Question:**

> ***Write a program to calculate the area of a triangle.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
	public static void main(String[] args) {
        Scanner s= new Scanner(System.in);
        
         System.out.println("Enter the base of the Triangle:");
         double b= s.nextDouble();
 
         System.out.println("Enter the height of the Triangle:");
          double h= s.nextDouble();
 
                
      double area=(b*h)/2;
      System.out.println("Area of Triangle is: " + area);  
	}
}

```
----------------------------------------




# Question 4

### **Question:**

> ***Write a program to calculate the area of a rectangle.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
	public static void main(String[] args) {
	Scanner s= new Scanner(System.in);
        
         System.out.println("Enter the length:");
         double l= s.nextDouble();
        System.out.println("Enter the breadth:");
         double b= s.nextDouble();
        
          
          double  area=l*b;
      System.out.println("Area of Rectangle is: " + area); 
	}
}
```
----------------------------------------

# Question 5

### **Question:**

> ***Write a program to find the sum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int a, b, sum;
a=1;
b=2;
sum = a + b;
System.out.println("The sum of a and b = " + sum);
}
}
```


```Java
import java.util.Scanner;
public class MyClass {

	public static void main(String[] args) {
	int num1, num2, sum;
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter First Number: ");
        num1 = sc.nextInt();
        
        System.out.println("Enter Second Number: ");
        num2 = sc.nextInt();
        
        sc.close();
        sum = num1 + num2;
        System.out.println("Sum of " + num1 + " and " + num2 +" is : "+sum);
	}
}

```
----------------------------------------



# Question 6

### **Question:**

> ***Write a program to calculate the area of a parallelogram.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {

	public static void main(String[] args) {
	Scanner s= new Scanner(System.in);
        
         System.out.println("Enter the base:");
         double b= s.nextDouble();
        System.out.println("Enter the height:");
         double h= s.nextDouble();
          
          double  area=(b*h) ;
      System.out.println("Area of Parallelogram is: " + area);  
	}
}

```
----------------------------------------
# Question 7

### **Question:**

> ***Write a program to calculate Perimeter Of Circle.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;

public class MyClass {

	public static void main(String[] args) {
	Scanner s= new Scanner(System.in);
        
    System.out.println("Enter the radius:");
         
	 double r= s.nextDouble();
         
	 double  c=2*3.14*r;
      
	 System.out.println("Perimeter of Circle is: " +c);    
	}
}

```
----------------------------------------


# Question 8

### **Question:**

> ***Write a program to calculate Volume of Cone.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;

public class MyClass {

	public static void main(String[] args) {
	Scanner s= new Scanner(System.in);
           System.out.println("Enter the radius of cone: ");
         	double r=s.nextDouble();
                System.out.println("Enter the height of cone: ");
         	double h=s.nextDouble();
	
       
            double  volume=(3.14*r*r*h)/3;
 
             System.out.println("Volume Of Cone is: " +volume);   
	}
}


```
----------------------------------------




# Question 9

### **Question:**

> ***Write a program to find the square of a number.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int a, b;
a=2;
b = a * a;
System.out.println("The square of a = " + b);
}
}
```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to find the greatest of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int a, b;
a=2;
b =3;
if(a>b)
{
System.out.println("a is greater than b");
}
else
{
System.out.println("b is greater than a");
}
}
}
```
----------------------------------------




# Question 11

### **Question:**

> ***Write a program to compute the difference between two numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;

public class MyClass {

	public static void main(String[] args) {
	int num1, num2, difference;
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter First Number: ");
        num1 = sc.nextInt();
        
        System.out.println("Enter Second Number: ");
        num2 = sc.nextInt();
        
        sc.close();
        difference = num1 - num2;
        System.out.println("Difference between " + num1 + " and " + num2 +" is : "+ difference); 
	}
}

```
----------------------------------------


# Question 12

### **Question:**

> ***Write a program to compute the product of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;

public class MyClass {

	public static void main(String[] args) {
	int num1, num2, product;
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter First Number: ");
        num1 = sc.nextInt();
        
        System.out.println("Enter Second Number: ");
        num2 = sc.nextInt();
        
        sc.close();
        product = num1 * num2;
        System.out.println("Product of " + num1 + " and " + num2 +" is : "+ product); 
	}
}


```
----------------------------------------

# Question 13

### **Question:**

> ***Write a program to print the average of the elements in the array.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String[] args) {
int i, avg, sum = 0;
int [] num = {16, 18, 20, 25, 36};
for(i=0; i<5; i++)
sum = sum + num[i];
avg = sum/5;
System.out.println("Sum of the Elements in the array = " + sum);
System.out.println("Average of the Elements in the array = " + avg);
}
}
```
----------------------------------------

