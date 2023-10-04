#CSCC20 
# Interface
---
#### What is an Interface?
- Interface is a contract that specifies a set of methods that a class must implement and serves a similar purpose to Abstraction
	- Interface cannot have a constructor
	- Class can implement more than interface and are separated with a comma

> [!success]+ Example
> ```java
> interface Animal {
> 	public void sound();
> 	public void sleep();
> }
> class Pig implements Animal {
> 	public void sound() {
> 		System.out.println("wee wee...")
> 	}
> 	public void sleep() {
> 		System.out.println("zzz...")
> 	}
> }
> ```

## Extending an Interface
#### Can an interface be extended?
- Interface can be extended or can inherit from another interface

> [!success]+ Example
> ```java
> interface A {
> 	void funcA();
> }
> interface B {
> 	void funcB();
> }
> class C implements B {
> 	void funcA() {
> 		System.out.println("This is funcA");
> 	}
> 	void funcB() {
> 		System.out.println("This is funcB");
> 	}
> }
> ```
