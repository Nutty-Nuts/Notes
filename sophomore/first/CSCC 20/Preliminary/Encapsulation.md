#CSCC20 
# Encapsulation
---
#### What is **Encapsulation?**
- **Encapsulation** is an Object-Oriented Programming concept that refers to the bundling of data and methods that operate on that data within a single unit called a class.
- **Encapsulation** is a way of hiding implementation details of a class and only exposing a public interface that can be used to interact with the class

> [!info] Source or Reference
> *CSCC 20 Module 2, p.3*

# Getters and Setters
----
## Getters
#### What are **Getters?**
- **Getters** are methods that can be used to access or retrieve private data from a class or object

> [!success]+ Example
> ```java
> class Student {
> 	private String name;
> 	
> 	public Student(String name) {
> 		this.name = name;
> 	}
> 	public String getName() {
> 		return this.name;
> 	}
> }
> public class Main {
> 	public static void main(String[] args) {
> 		Student student = new Student("John")
> 		System.out.println(student.getName());
> 	}
> }
> ```

> [!info] Source or Reference
> *CSCC 20 Module 2, p.5-6*
## Setters
#### What are **Setters?**
- **Setter** are methods that can be used to access or modify private data stored within a class or object.

> [!success]+ Example
> ```java
> class Student {
> 	private String name;
> 	
> 	public Student(String name) {
> 		this.name = name;
> 	}
> 	public String getName() {
> 		return this.name;
> 	}
> 	public void setName(String name) {
> 		this.name = name;
> 	}
> }
> public class Main {
> 	public static void main(String[] args) {
> 		Student student = new Student("John")
> 		System.out.println(student.getName());
> 		  
> 		 student.setName("Johnny");
> 		 System.out.println(student.getName());
> 	}
> }
> ```

> [!info] Source or Reference
> *CSCC 20 Module 2, p.5-6*