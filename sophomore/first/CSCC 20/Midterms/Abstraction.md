---

---
#CSCC20 
# Abstraction
---
#### What is Abstraction?
- **Abstraction** is the simplification of complex systems by exposing only the necessary characteristics and behavior of a system or object while hiding irrelevant details
	- An example is: a car is viewed as a car rather than its individual components
#### How is Abstraction different from Encapsulation?
- Abstraction focuses more on hiding the implementation, Encapsulation focuses more on hiding the information
## Abstract Keyword
#### What does the `abstract` keyword do?
- `abstract` can be used to create an **Abstract Class** which cannot be instantiated 
	- **Abstract Classes** are blueprints for other classes and can contain concrete or abstract methods
- `abstract` can also be used to create an **Abstract Method**
	- **Abstract Methods** are methods in an abstract class that do not have a body and have to be overridden in concrete sub-classes.

> [!success]+ Example
> ```java
> abstract class Shape {
> 	String color;
> 	
> 	abstract double area();
> 	public abstract String toString();
> 	
> 	public Shape(String color) {
> 		System.out.println("Shape constructor is called");
> 	}
> 	public String getColor() {
> 	}
> }
> class Circle extends Shape {
> 	double radius;
> 	
> 	public Circle(String color, double radius) {
> 		super(color);
> 		System.out.println("Circle constructor called");
> 		this.radius = radius;
> 	}
> 	@Override
> 	double area() {
> 		return Math.PI * Math.pow(radius, 2);
> 	}
> 	@Override 
> 	public String toString() {
> 		return "Circle color is " + super.color + "and area is: " + area();
> 	}
> }
> public class Main {
> 		public static void main(String[] args) {
> 			Shape circle = new Circle("Red", 2.2);
> 			System.out.println(circle.toString());
> 		}
> }
> ```


