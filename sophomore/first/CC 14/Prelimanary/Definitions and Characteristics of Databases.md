#CC14
# Data and Information
## Data
#### What is **Data?**
- **Data** is raw and unorganized facts that needs to processed to be useful.  
> [!info] Source
> **Data** is raw, unorganized facts that need to be processed. Data can be something simple and seemingly random and useless until it is organized.
##  Information
#### What is **Information?**
- **Information** is data that is processed and organized in a given context to make it useful.
> [!info] Source
> When data is processed, organized, structured, or presented in a given context to make it useful, it is called **information**.

# Approaches for Storing Data
## Manual Filing System Approach
#### What is a **Manual Filing System Approach?**
- **Manual Filing System Approach** is a file organization systems that uses a paper-folder-cabinet approach.
#### When should a manual filing system approach be used?
- Manual Filing System is used when the number of items to be stored is small or when the number of items to be stored is large but operations are only limited to retrieval
#### When should a manual filing system be avoided?
- Manual Filing System should be avoided when cross-referencing or information processing is needed.
> [!info] Source
> The manual filing system is a file organization system wherein it uses a paper-folder-cabinet approach. This method works well while the number of items to be stored is small. It even works quite adequately when there are large numbers of items for storage and retrieval purposes only.  But, manual filing breaks down when cross-referencing or information processing is needed.


## File Processing System Approach
#### What is a **File Processing System Approach?**
- **File Processing System Approach** is where data is stored in one or more computer files defined and managed by different application programs.
> [!info] Source 
> **File processing system** Is an early attempt to computerize the manual filing system in response to the need for more efficient data access. It refers to the situation where data is stored in one or more separate computer files defined and managed by different application programs.  For example, the details of customers may be stored in one file, orders in another, etc. 
>> [!example]
>> For example, all of the programs associated with processing customers' orders are referred to as the order processing application. 

### Limitations and Disadvantages of File Processing System Approach
#### What are the **Limitations and Disadvantages** of file processing system approach?
- Data Duplication
- Data Inconsistency
- Difficult to Implement Data Security
#### What is **Data Duplication?** How does it occur in this approach?
1. **Data Duplication** is when multiple copies of the same data is stored in the system which unnecessarily takes up more space.
2. Data Duplication occurs in a File Processing System Approach since different programs needs to have their own copy of the same data.
> [!info] Source
>**Data Duplication**
> Each program stores its own separate files (see figure above). If the same data is to be accessed by different programs, then each program must store its own copy of the same data.

#### What is **Data Inconsistency?** How does it occur in this approach?
1. **Data Inconsistency** is when data inside of relevant or supposedly identical files are inconsistent with one another which could lead to errors.
2. Data Inconsistency occurs when the relevant files of the system are not properly updated.
> [!info] Source
> **Data Inconsistency**
> If the data is kept in different files, there could be problems when an item of data needs updating, as it will need to be updated in all the relevant files; if this is not done, the data will be inconsistent, and this could lead to errors.
#### Why is data security a limitation of a file processing system?
- **Difficult to Implement Data Security** since data is stored in different files by different programs making it difficult and expensive to implement security. 
> [!info] Source
> **Difficult to implement data security**
> Data is stored in different files by different application programs. This makes it difficult and expensive to implement organization-wide security procedures on the data.


## Shared File Approach
#### What is a **Shared File Approach?**
- **Shared File Approach** is where files are shared and embedded between applications. This alleviated the problem of Data Duplication and Data Inconsistency.
### Limitations and Disadvantages of Shared File Approach
#### What are the **Limitations and Disadvantage** of shared file approach?
- File Incompatibility
- Difficult to Control Access
- Physical Data Dependence
- Difficult to Implement Concurrency
#### What is **File Incompatibility?**
- **File Incompatibility** is when he format or structure of a file works on a specific applications but might not work with other applications.
> [!info] Source
> **File Incompatibility**
>When each department had its own version of a file for processing, each department could ensure that the structure of the file suited their specific application. If departments have to share files, the file structure that suits one department might not suit another.  
#### Why is controlling access a limitation of shared file approach?
- Controlling Access is a limitation of shared file approach since some application may require access to more data than others.
> [!info] Source
> **Difficult to Control Access**
> Some applications may require access to more data than others
#### What is **Physical Data Dependence?**
- **Physical Data Dependence** is when data within a file is changed and such change is reflected in all application programs that use that data.
> [!info] Source
> **Physical Data Dependence**
> If the structure of the data file needs to be changed in some way (for example, to reflect a change in currency), this alteration will need to be reflected in all application programs that use that data file. This problem is known as physical data dependence and will be examined in more detail later in the succeeding modules.


#### What is **Concurrency?** Why is it difficult to implement concurrency in a shared file approach? 
1. **Concurrency** is the ability to allows two or more applications to access or retrieve data from the same file.
2. Concurrency difficult to implement in a shared file approach since other applications cannot access or modify data when said data is being processed by one application.
> [!info] Source
> **Difficult to Implement Concurrency**
> While a data file is being processed by one application, the file will not be available for other applications or for ad hoc queries. This is because, if more than one application is allowed to alter data in a file at one time, serious problems can arise in ensuring that the updates made by each application do not clash with one another. The file processing system approach avoids these problems by not allowing more than one application to access a file at one time.


## Database Approach
#### What is a **Database Approach?**
- **Database Approach** is where a database management system or DBMS provides facilities for querying, data security and integrity, allows simultaneous access to data by several users, and stores data in a standardized and convenient format.
> [!info] Source
> The database approach is an improvement on the shared file solution as the use of a database management system (DBMS) provides facilities for querying, data security and integrity, and allows simultaneous access to data by several different users.
### Limitations  and Disadvantages of Database Approach
#### What are the **Limitations and Disadvantages** of database approach?
1. More Costly
2. High Complexity
3. Database Handling Personnel Required
4. Higher Impact of Failure
5. High Hardware Cost
6. Cost of Data Conversion
7. Huge Size

#### Why is database approach **More Costly?**
- Creating and managing a database is costly due to the expensive hardware and software needed for a database as well as trained staff to operate and perform maintenance on the database. 
> [!info] Source
> **More Costly**
> Creating and managing a database is quite costly. High-cost software and hardware is required for the database. Also, highly trained staff is required to handle the database and it also needs continuous maintenance. All of these end up making a database quite a costly venture.
#### Why is database approach **More Complex?**
- A Database Approach is more complex since it involves creating, modifying, and editing a database which requires skill to avoid data loss.
> [!info] Source
> **High Complexity**
> A Database Management System is quite complex as it involves creating, modifying, and editing a database. Consequently, the people who handle a database or work with it need to be quite skilled, or valuable data can be lost. 
#### Why does a database approach require **Skilled Personnel?**
- Skilled Personnel are required in a database approach to ensure that a database runs in optimum condition.
> [!info] Source
>**Database Handling Personnel Required**
> Skilled personnel is required to handle the database so that it works in optimum condition. This is a costly venture as these professionals need to be very well paid.
#### Why does a database approach have a **Higher Impact of Failure?**
- Database Approach has a higher impact of failure since when a database fails, loss or corruption of valuable data might occur
> [!info] Source
> **Higher Impact of Failure**
> All the relevant data for any company is stored in a database. So it is imperative that the database works in optimal condition and there are no failures. A database failure can be catastrophic and can lead to loss or corruption of very important data.
#### Why does a database approach have a **High Hardware Cost?**
- Database Approach has a high hardware cost since the hardware needed to contain large amount of data reliably is very expensive.
> [!info] Source
>**High Hardware Cost**
> A database contains a vast amount of data. So large disk storage is required to store all this data. Sometimes extra storage may even be needed. All this increases hardware costs by a lot and makes a database quite expensive.
#### Why is the **Cost of Data Conversion** a concern for database approach?
- When a database is modified, all of the data in the database must be converted into a new form that is compatible with the modified database which is very expensive process to perform.
> [!info] Source
>**Cost of Data Conversion**  
> If the database is changed or modified in some manner, all the data needs to be converted to the new form. This cost may even exceed the database creation and management costs sometimes. This is the reason most organizations prefer to work on their old databases rather than upgrade to new ones.
#### Why does a database approach have a **Huge Size?**
- Database Approach has databases that contains large amount of data and may even become larger overtime which increases the difficulty and complexity of maintaining a database.
> [!info] Source
>**Huge Size**
> A database contains a large amount of data, especially for bigger organizations. This data may even increase as more data is updated into the database. All of these leads to the large size of the database. The bigger the database is, the more difficult it is to handle and maintain. It is also more complex to ensure data consistency and user authentication across big databases. 

# Database
#### What is a **Database?**
- **Database** is a large collection of logically related data that allows users and applications to search and retrieve data or information in a convenient manner and is designed to meet the information needs of an organization.
> [!quote]
> A **database** is a collection of persistent data that is used by the application systems of a given enterprise. **- C.J. Date "An Introduction to Database Systems"**
> 
> A **database** is a system that converts a large collection of data into an abstract tool, allowing users to search for and extract pertinent items of information in a manner that is convenient to the user. **- Brookshear, 2012, p383**
## Properties of Database
#### 1. What is **Atomicity?**
- **Atomicity** is a property of database that ensures transactions are indivisible and irreducible where transactions either commit or abort.
> [!info] Source
> **Atomicity.**  in database atomicity ensures that the transactions are **indivisible** and **irreducible** where transactions either commit or abort. If a part of the transaction fails then the entire transaction fails.
#### 2. What is **Consistency?**
- **Consistency** is a property of a database where any changes done to the data stored within a database should be consistent with change to other data.
> [!info] Source
> **Consistency,** any change in the values of a database at a particular instance is consistent with changes to other values.
#### 3. What is **Isolation?**
- **Isolation** is a property of a database that ensures that a working transaction will not be affected nor changed by other transactions.
> [!info] Source
> **Isolation.** transaction in the database ensures that the working transaction will not be changed or affected by any other transaction. In other words, modifications or updates made on one transaction are not viewed or changed by any other transaction.
#### 4. What is **Durability?**
- **Durability** is a property of a database that ensures any transaction committed should remain in the same status regardless of failures.
> [!info] Source
> **Durability,** durability of the databases states that “once the transaction has been committed, should remain in the same status” even in the case of failures such as power loss, database crash, or the like.

## Characteristics and Benefits of a Database
#### What are the characteristics and benefits of a database?
##### 1. Self-Describing Nature of a Database System. **Why is a database self-describing?**
- Database is Self-Describing since it contains both data and metadata, data that defines and describes other data.
> [!info] Source
> A database system is referred to as self-describing because it not only contains the database itself, but also metadata which defines and describes the data and relationships between tables in the database. This separation of data and information about the data makes a database system totally different from the file processing systems in which the data definition is part of the application programs.k
##### 2. Insulation between Programs and Data. **How are programs and data insulated from each other in a database?**
- Programs and Data are insulated in a database since programs and data in a database are separate from one another (see [[#8. Data Independence]]), meaning changes to the structure of a file does not require the associated programs to be changed as well.
> [!info] Source 
> In the file processing systems, the structure of the data files is defined in the application programs so if a user wants to change the structure of a file, all the programs that access that file might need to be changed as well. On the other hand, in the database approach, the data structure is stored in the system catalog and not in the programs. Therefore, one change is all that is needed to change the structure of a file. This insulation between the programs and data is also called program-data independence.
##### 3. Support for Multiple Views of Data. **What are multiple views of data?**
- Databases can present data in different ways depending on what is relevant or important to a user or a group of users.
> [!info] Source 
> A database supports multiple views of data.  A view is a subset of the database, which is defined and dedicated to particular users of the system. Multiple users in the system might have different views of the system. Each view might contain only the data of interest to a user or group of users.
##### 4. Sharing of Data and Multi-User System. **What is a multi-user system? What is sharing of data?**
- Multi-User System is a characteristic of a database that allows multiple users to access the database and its data at the same time.
> [!info] Source 
> Current database systems are designed for multiple users. That is, they allow many users to access the same database at the same time. This access is achieved through features called concurrency control strategies. These strategies ensure that the data accessed are always correct and that data integrity is maintained**.**
##### 5. Control of Data Redundancy. **How can databases reduce redundancy?**
- Databases can minimize redundancy of data and can introduce redundancy only when it is needed.
> [!info] Source 
> In the database approach, ideally, each data item is stored in only one place in the database. In some cases, data redundancy still exists to improve system performance, but such redundancy is controlled by application programming and kept to a minimum by introducing as little redundancy as possible when designing the database.
##### 6. Enforcement of Integrity Constraints. **What is the Enforcement of Integrity Constraints in a database?**
- Databases can define and enforce constraints on the input to ensure the correctness of the information entered.
> [!info] Source 
> Database management systems must provide the ability to define and enforce certain constraints to ensure that users enter valid information and maintain data integrity. A database constraint is a restriction or rule that dictates what can be entered or edited in a table such as a postal code using a certain format or adding a valid city in the City field.
##### 7. Restriction of Unauthorized Access
- Databases can set different access levels to users ensuring that only authorized users are able to access a database.
> [!info] Source
> Not all users of a database system will have the same accessing privileges. For example, one user might have read-only access (i.e., the ability to read a file but not make changes), while another might have read and write privileges, which is the ability to both read and modify a file. For this reason, a database management system should provide a security subsystem to create and control different types of user accounts and restrict unauthorized access. 
##### 8. Data Independence
- Databases are able to keep data and metadata separate from applications programs.
> [!info] Source 
> Another advantage of a database management system is how it allows for data independence. In other words, the system data descriptions or data describing data (metadata) are separated from the application programs. This is possible because changes to the data structure are handled by the database management system and are not embedded in the program itself.
##### 9. Transaction Processing
- Databases are able to maintain consistent data even if multiple transaction made by multiple users are being processed or performed
> [!info] Source 
> A database management system must include concurrency control subsystems. This feature ensures that data remains consistent and valid during transaction processing even if several users update the same information.
##### 10. Backup and Recovery Facilities
- Databases have backups and recovery facilities which allows you to protect your data in case of failure.
> [!info] Source 
> Backup and recovery are methods that allow you to protect your data from loss.  The database system provides a separate process, from that of a network backup, for backing up and recovering data. If a hard drive fails and the database stored on the hard drive is not accessible, the only way to recover the database is from a backup. If a computer system fails in the middle of a complex update process, the recovery subsystem is responsible for making sure that the database is restored to its original state. These are two more benefits of a database management system.

# Centralized and Distributed Databases
## Centralized Databases
#### What are centralized databases?
- Centralized Databases are databases that holds all data on a central computer.
### Advantages
#### What are the advantages of a centralized database?
1. Data Integrity is Easy to Maximize
2. Easier Implementation
3. Decreased Risk
4. Single Point of Entry
5. Integration is Easy
6. Upgrades, Mirroring, and Backups are Easier
### Disadvantages
#### What are the disadvantages of a centralized database?
1. Single Point of Failure
2. Slower Response Time
## Distributed Databases
#### What are distributed databases?
- Distributed Databases are databases whose components are stored within multiple computers within a network.
### Advantages
#### What are the advantages of a distributed database?
1. Increased Reliability and Availability
2. Faster Response Time
3. Scalability
4. Robust
5. Data Protection
6. Modality
7. Localization
8. Lower Communication Costs
### Disadvantages
#### What are the disadvantages of a distributed database?
1. More Expensive to Implement
2. Operating System should Support a Distributed Environment
3. Complex Software Implementation
4. Increased Processing Overhead
5. Data Integrity
6. Security
7. Deadlock is Difficult to Handle
8. Handling Failures is a Difficult Task
