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

