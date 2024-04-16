#CC14 

# Rationale
---
#### Why convert ER Model to Relational Model?
- ER Models are converted to Relational Model so that it can be implemented into a Relational Database Management System or RDBMS

# Mapping
---
## Mapping Entities
### Strong Entity
#### How is a Strong Entity mapped?
1. Create a Relation or Table for each Entity
2. Convert Attributes to Fields
3. Declare Primary Key via underline
![[Pasted image 20230928145704.png]]
### Weak Entity
#### How is a Weak Entity mapped?
1. Create a Relation or Table for each Weak Entity
2. Convert Attributes to Fields
3. Declare Primary Key which is a combination of the Primary Key and the Partial Key
4. Use an arrow to link the Weak Entity to its Parent Entity; from Foreign Key to Primary Key
![[Pasted image 20230928145712.png]]
## Mapping Attributes
### Composite Attributes
#### How are Composite Attributes mapped?
1. Create a Relation or Table for each Entity
2. Convert each component of the Composite Attribute to Fields
3. Declare Primary Key by underlining the set of simple attributes that form the Primary Key
![[Pasted image 20230928145722.png]]
### Multivalued Attributes 
#### How are Multivalued Attributes mapped?
1. Create a Relation or Table for each Entity
2. Convert Attributes to Fields except the Multivalued Attribute
3. Create a separate table for the Multivalued Attribute
4. Declare a Primary Key of Multivalued Attribute by combining the Primary Key of the Entity and the Attribute Name.
5. Use an arrow to link the Multivalued Attribute to the Parent Entity; from Foreign Key to Primary Key
![[Pasted image 20230928145727.png]]
### Derived Attributes
#### How are Derived Attributes mapped?
- Derived attributes are not mapped
![[Pasted image 20230928145733.png]]
## Mapping Unary Relationships
![[Pasted image 20230928142906.png]]
![[Pasted image 20230928142929.png]]
![[Pasted image 20230928142938.png]]
## Mapping Binary Relationships
![[Pasted image 20230928143339.png]]
![[Pasted image 20230928143329.png]]
![[Pasted image 20230928143354.png]]
![[Pasted image 20230928143358.png]]

## Mapping N-ary Relations
![[Pasted image 20230928144022.png]]
## Mapping Associative Entity w/ Identifier 
![[Pasted image 20230928144014.png]]
## Mapping Supertype and Subtype
![[Pasted image 20230928144006.png]]
