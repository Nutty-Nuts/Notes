#CSCC20 

# Compile-Time Polymorphism
---
#### What is Compile-Time Polymorphism?
- **Compile-Time Polymorphism** or **Static Polymorphism** is a type of polymorphism that is achieved by method or function overloading or operator overloading
	- **Method** or **Function Overloading** is a type of Compile-Time Polymorphism where there are multiple functions or methods with the same name within the same class or scope but with different parameter lists

> [!success]+ Example
> ``` java
> class Math {
> 	static int Multiply(int a, int b) {
> 		return a * b;
> 	}
> 	static double Multiply(double a, double b) {
> 		return a * b;
> 	}
> }
> ```

# Runtime Polymorphism
---
#### What is Runtime Polymorphism?
- **Runtime Polymorphism** or **Dynamic Method Dispatch** is a type of polymorphism that is achieved by method overriding
	- **Method Overriding** is a type of Runtime Polymorphism where a subclass overrides the behavior of a method that is already defined by its superclass.
 
 > [!success]+ Example
> ``` java
> class Shapes {
> 	public void area() {
> 		System.out.println("The formula for the area of ");
> 	}
> }
> class Triangles extends Shapes {
> 	@Override
> 	public void area() {
> 		System.out.println("Circle is 0.5 * base * height");
> 	}
> }
> ```