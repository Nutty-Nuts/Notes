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
> class Pu
> class Main {
>	public static void main(String[] args) {
>		Dog dog = new Dog();
>		dog.bark();
>		dog.eat();
>	}
> }
> ```
```java
class Animal {
	public void eat() {
		System.out.println("Eating...");
	}
}

// Dog inherits its methods and attributes to a single class, Animal;
class Dog extends Animal {
	public void bark() {
		System.out.println("Barking...");
	}
}

// Puppy inherits from Dog which inherits from Animal
class Puppy extends Dog {
	public void weep() {
		System.out.println("Weeping...");
	}
}

class Main {
	public static void main(String[] args) {
		Puppy puppy = new Puppy();
		puppy.weep(); // prints "Weeping..."
		puppy.bark(); // print "Barking..."
		puppy.eat();  // prints "Eating..."
	}
}
```

> [!info] Source or Reference
> *CSCC 20 Module 1, p.7*
### Hierarchical Inheritance
#### What is **Hierarchical Inheritance?**
- **Hierarchical Inheritance** is where multiple classes inherits or extends from a parent class

```java
class Animal {
	public void eat() {
		System.out.println("Eating...");
	}
}

// Dog inherits its methods and attributes to a single class, Animal;
class Dog extends Animal {
	public void bark() {
		System.out.println("Barking...");
	}
}

// Cat inherits its methods and attributes to a single class, Animal;
class Cat extends Animal {
	public void meow() {
		System.out.println("Meowing...");
	}
}

class Main {
	public static void main(String[] args) {
		Cat cat = new Cat();
		cat.meow(); // prints "Meowing..."
		cat.eat();  // prints "Eating..."

		Dog dog = new Dog();
		dog.bark(); // prints "Barking..."
		dog.eat();  // prints "Eating..."
	}
}
```

> [!info] Source or Reference
> *CSCC 20 Module 1, p.8*
## Extends
#### What is the *`extends`* keyword?
- *`extends`* is the keyword used to inherit the properties of a class.

```java
class Animal {
	// class methods and attributes here
}

// class Dog will inherit the methods and attributes of class Animal
class Dog extends Animal {
	// methods and attributes of the class Animal
	// methods and attributes of the class Dog
}
```

> [!info] Source or Reference
> *CSCC 20 Module 1, p.4*
## Super
#### What is the *`super`* keyword?
- *`super`* is the keyword used to invoke the superclass constructor from subclass.

```java
class Animal {
	public void eat() {
		System.out.println("I can eat...");
	}
}

class Dog extends Animal {
	@Override
	public void eat() {

		// calls the method eat() from the super class
		super.eat(); // prints "I can eat..."
		System.out.println("I eat dog food...");
	}

	public void bark() {
		System.out.println("I can bark...");
	}
}

public class Main {
	public static void main(String[] args ) {
		Dog dog = new Dog();

		dog.eat(); // prints "I can eat..."
				   // prints "I eat dog food..."
		dog.barl();// prints "I can bark..."
	}
}
```

> [!info] Source or Reference
> *CSCC 20 Module 1, pp.9-11*