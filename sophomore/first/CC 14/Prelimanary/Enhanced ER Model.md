#CC14 
# Associative Entities
---
#### What is an **Associative Entity?**
- **Associative Entity** or Composite Entity or Bridge Entity represent an association between one or more entity types and contain attributes that are peculiar to both entity types.
	- **Associative Entity** or Composite Entity or Bridge Entity has a key attribute that is composed of all of the key attributes connected to it

#### What is the purpose of an **Associative Entity?** 
- **Associative Entity** or Composite Entity or Bridge Entity purpose is to provide an indirect link between two entities in a many-to-many relationship
# Inheritance, Subtypes, and Supertypes
---
## Inheritance
#### What is Inheritance?
- Inheritance is the transfer of properties of one entity to some derived entities.
## Supertype
#### What is a Supertype?
- Supertype is a generic entity that has a relationship with its subtype
## Subtype
#### What is a Subtype?
- Subtype is the grouping of entities into types that are meaningful to the organization
	- Subtypes inherit that values of all attributes of the supertype entity
## Constraints of Inheritance
#### What are the Two Constraints of Inheritance?
- The Two Constraints of Inheritance are:
	1. Completeness Constraint
	2. Disjointness Constraint

### Completeness Constraint
#### What is the Completeness Constraint?
- Completeness Constraint describes whether an instance of the supertype must also be a member of at least one subtype.

##### What is Total Specialization Rule?
- Total Specialization Rule specifies that each instance of the supertype entity must be a member of some subtype in the relationship.
	- Total Specialization Rule is represented as a double line connecting the supertype to the circle
 
##### What is Partial Specialization Rule?
- Partial Specialization Rule specifies that an instance of the supertype entity is allowed not to belong to any subtype

### Disjointness Constraint
#### What is Disjointness Constraint?
- Disjointness Constraint addresses the question of whether an instance of a supertype may simultaneously be a member of two or more subtypes

##### What is the Disjoint Rule?
- Disjoint Rule specifies that if an entity instance is a member of one subtype then it cannot be a member of any other subtype.
	- Disjoint Rule is indicated by a "d" in the circle
##### What is the Overlap Rule?
- Overlap Rule specifies that a supertype entity instance can simultaneously be a member of two or more subtypes.
	- Overlap Rule is indicated by a "o" in the circle

# Entity Clustering
---
#### What is Entity Clustering?
- Entity Clustering is the process of grouping several entity types into a single abstract entity type.
	- Entity Clustering is often used as a way of partitioning designer responsibility for a larger complex database