#CC14 

# Three Basic Elements of ERD
---
#### What are the **Three Basic Elements of ERD?**
- The **Three Basic Elements of ERD** are:
	1. Entity
	2. Attributes
	3. Relationship
## Entity
#### What is an **Entity?**
- **Entity** is a person, place, object, event, or concept about which the organization wishes to maintain data
#### What is an **Entity Type?**
- **Entity Type** is a collection of all entities that share common properties or characteristics.
#### What is an **Entity Instance?**
- **Entity Instance** is a single occurrence of an entity type.
## Attributes
#### What are **Attributes?**
- Attributes are the properties or characteristics of an Entity
## Relationship
#### What are **Relationships?**
- **Relationships** is an association among one or more entities
#### What are **Relationship Types?**
- **Relationship Type** is a meaningful association between or among entities
#### What are **Relationship Instance?**
- **Relationship Instance** is the association between specific entity instances
# ERD Notations
---
#### What are the **Two ERD Notations?**
- The **Two ERD Notations** that this course will focus on are:
	1. Chen Notation
	2. Crow's Feet Notation

## Chen Notation
#### What is the **Chen Notation?**
- **Chen Notation** is used and considered to present a more detailed way of representing entities.
## Crow's Feet Notation
#### What is the **Crow's Feet Notation?**
- **Crow's Feet Notation** represents entities as boxes and relationships as lines between the boxes as wells as shapes at then of lines to represent the cardinality of the relationship.

# Entities
---
#### What are the different **Types of Entities in the Chen Notation?**
- The different **Types of Entities in the Chen Notation** are:
	1. Entity or Strong Entity
	2. Weak Entity
	3. Associative Entity
#### How are entities represented in the Crow's Foot Notation?
- Entities in the Crow's Foot Notation are represented by a rectangle with its name on the top.
## Types of Entities in Chen Notation
### Strong Entity
#### What is an **Entity** or **Strong Entity?**
- **Entity** or **Strong Entity** are entities that are considered strong entities unless specified weak.
### Weak Entity
#### What is a **Weak Entity?**
- **Weak Entity** is an entity that cannot be uniquely identified by its attributes alone and is dependent upon another strong entity called an owner entity.
### Associative Entity
#### What is a **Associative Entity?**
- **Associative Entity** is an entity used in many-to-many relationships.

# Attributes
---
## Types of Attributes
#### What are the **Types of Attributes in ERD?**
- The **Types of Attributes in ERD** are the following:
	1. Key Attribute
	2. Partial Key Attribute
	3. Multi-valued Attribute
	4. Derived Attribute
	5. Composite Attribute

### Key Attribute
#### What is a **Key Attribute?**
- **Key Attribute** is an attribute that uniquely identifies a particular entity
	- Key Attribute is underlined in Chen notation
	- Key Attribute is underlined with PK or FK indicators in Crow's Feet Notation
### Partial  Key Attribute
#### What is a **Partial Key Attribute?**
- **Partial Key Attribute** or **Discriminator** is an attribute of a weak entity that provides a unique identification for the week entity when combined with an attribute of a parent entity.
	- Partial Key or Discriminator is underlined with a dashed line in the Chen Notation
	- Partial Key or Discriminator becomes a composite key attribute which contains the key attribute of the parent and the child.
### Multi-valued Attribute
#### What is a **Multi-valued Attribute?**
- **Multi-valued Attribute** is an attribute that can have many actual values
	- Multi-valued Attribute is depicted by a dual oval
	- Multi-valued Attribute is to depict values as entities with with a one-to-many relationship with the original entity
	 - Multi-value Attribute is treated as a weak entity in Crow's Feet Notation
### Derived Attribute
#### What is a **Derived Attribute?**
- **Derived Attribute** is an attribute whose value is calculated or derived from other attributes.
	- Derived Attribute is represented by a dashed oval
	- Derived Attribute is enclosed by \[ \]
	- Derived Attribute may or may not be stored in the database
### Composite Attribute
#### What is a **Composite Attribute?**
- **Composite Attribute** is an attribute that can be further subdivided into smaller parts
#  Relationships
---
#### How are Relationships represented in Chen Notation?
- Relationships are represented by a diamond or rhombus containing that relationship's name
#### How are Relationships represented in Crow's Foot Notation?
- Relationships are represented by a straight line which has name that is usually a verb

## Types of Relationships
#### What are the **Types of Relationships?**
- The **Type of Relationships** are the following:
	1. Strong Relationships
	2. Weak or Identifying Relationships
### Strong Relationship
#### What is a **Strong Relationship?**
- **Strong Relationship** is where the entity is strong and independent of other entities
	- Strong Relationships are represented by a single rhombus
### Weak Relationship 
#### What is a  **Weak Relationship?**
- **Weak** or **Identifying Relationship** is a relationship where a child entity is existence-dependent on parent entity
	- Weak or Identifying Relationship is represented by a dual or double rhombus

## Types of Cardinal Relationship
#### What are the **Types of Cardinal Relationships?**
- The **Types of Cardinal Relationships** are the following:
	1. One-to-One Relationship
	2. One-to-Many Relationship
	3. Many-to-One Relationship
	4. Mane-to-Many Relationship
### One-to-One Relationship
#### What is a **One-to-One Relationship?**
- **One-to-One Relationship** is where there is only one entity on both sides of the relationship.
### One-to-Many Relationship
#### What is a **One-to-Many Relationship?**
- **One-to-Many Relationship** is where there is only one entity on one side of the relationship and many on the other.
### Many-to-One Relationship
#### What is a **Many-to-One Relationship?**
- **Many-to-One Relationship** is where there are many entities on one side of the relationship and and only one on the other.
### Many-to-Many Relationship
#### What is a **Many-to-Many Relationship?**
- **Many-to-Many Relationship** is where there are many entities on both sides of the relationship.

## Relationship Participation
### Optional Participation
#### What is **Optional Participation?**
- **Optional Participation** is where one entity occurrences does not require a relationship with another entity occurrence
### Mandatory Participation
#### What is **Mandatory Participation?**
- **Mandatory Participation** is where one entity occurrence requires a relationship to another entity occurrence

## Degree of Relationship
#### What are the **Degrees of Relationships?**
- The **Degrees of Relationships** are the following?
	1. Unary Relationship
	2. Binary Relationship
	3. Ternary Relationship

### Unary Relationship
#### What is a **Unary Relationship?**
- **Unary Relationship** or **Recursive Relationship** is where the same entity participates more than once in different roles
### Binary Relationship
#### What is a **Binary Relationship?**
- **Binary Relationship** is where two entities are associated in a relationship
	- Binary Relationship is the most common type of relationship
### Ternary Relationship
#### What is a **Ternary Relationship?**
- **Ternary Relationship** is where an entity is has an association among three entities
	- Ternary Relationships allows the designer some latitude or verticality regarding the semantics of a problem

# Steps to Create an ERD
---
#### What are the **Steps to Create an ERD?**
- The **Steps to Creating an ERD** are the following:
	1. Entity Identification
	2. Relationship Identification
	3. Cardinality Identification
	4. Attributes Identification
	5. Done