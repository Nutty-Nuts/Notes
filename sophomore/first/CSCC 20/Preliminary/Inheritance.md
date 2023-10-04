#CSCC20

# Inheritance
---
#### What is **Inheritance?**
- **Inheritance** allows a class to inherit methods and attributes from another class

> [!info] Source or Reference
> *CSCC 20 Module 1, p.3*
## Types of Inheritance
#### What are the different **Types of Inheritance?**
- The different **Types of Inheritance** are:
	- Single Inheritance
	- Multilevel Inheritance
	- Hierarchical Inheritance
 
> [!info] Source or Reference
> *CSCC 20 Module 1, pp.5-8*
### Single Inheritance
#### What is **Single Inheritance?**
- **Single Inheritance** is where a class inherits or extends from a parent class.

> [!success]+ Example
> 
> ```java
> class Animal {
> 	public void eat()
> 		System.out.println("Eating...");
> 	}
> }
> class Dog extends Animal {
> 	public void bark() {
> 		System.out.println("Barking...");
> 	}
> }
> class Main {
>	public static void main(String[] args) {
>		Dog dog = new Dog();
>		dog.bark();
>		dog.eat();
>	}
> }
> ```

> [!info] Source or Reference
> *CSCC 20 Module 1, p.6*
### Multilevel Inheritance
#### What is **Multilevel Inheritance**
- **Multilevel Inheritance** is where a class inherits from a subclass of another class.

> [!success]+ Example
> 
> ```java
> class Animal {
> 	public void eat()
> 		System.out.println("Eating...");
> 	}
> }
> class Dog extends Animal {
> 	public void bark() {
> 		System.out.println("Barking...");
> 	}
> }
> class Puppy extends Dog {
> 	public void weep() {
> 		System.out.println("Weeping...");
> 	}
> }
> class Main {
>	public static void main(String[] args) {
> 		Puppy puppy = new Puppy();
> 		puppy.weep();
> 		puppy.bark();
> 		puppy.eat();
>	}
> }
> ```

> [!info] Source or Reference
> *CSCC 20 Module 1, p.7*
### Hierarchical Inheritance
#### What is **Hierarchical Inheritance?**
- **Hierarchical Inheritance** is where multiple classes inherits or extends from a parent class

> [!success]+ Example
> 
> ```java
> class Animal {
> 	public void eat()
> 		System.out.println("Eating...");
> 	}
> }
> class Dog extends Animal {
> 	public void bark() {
> 		System.out.println("Barking...");
> 	}
> }
> class Cat extends Animal {
> 	public void meow() {
> 		System.out.println("Meowing...");
> 	}
> }
> class Main {
>	public static void main(String[] args) {
> 		Dog dog = new Dog();
> 		dog.eat();
> 		dog.bark();
> 		
> 		Cat cat = new Cat();
> 		cat.eat();
> 		cat.bark();
>	}
> }
> ```

> [!info] Source or Reference
> *CSCC 20 Module 1, p.8*
## Extends
#### What is the *`extends`* keyword?
- *`extends`* is the keyword used to inherit the properties of a class.

> [!success]+ Example
> ```java
> class Animal {
> }
> class Dog extends Animal {
> }
> ```

> [!info] Source or Reference
> *CSCC 20 Module 1, p.4*
## Super
#### What is the *`super`* keyword?
- *`super`* is the keyword used to invoke the superclass constructor from subclass.

> [!success]+ Example
> 
> ```java
> class Animal {
> 	public void eat()
> 		System.out.println("I can eat...");
> 	}
> }
> class Dog extends Animal {
> 	@Override
> 	public void eat() {
> 		super.eat();
> 		System.out.println("I eat dog food...");
> 	}
> 	public void bark() {
> 		System.out.println("Barking...");
> 	}
> }
> class Main {
>	public static void main(String[] args) {
>		Dog dog = new Dog();
>		dog.eat();
>		dog.bark();
>	}
> }
> ```

> [!info] Source or Reference
> *CSCC 20 Module 1, pp.9-11*