# John's review on UML Diagrams


## 2 Types of UML Diagrams
 - Structural
 - Behavioral
 
![image](https://user-images.githubusercontent.com/22464805/198877113-dda5c3db-4f94-4ae8-9bda-ef5a4c0e9d7c.png)

### Class Diagram
> Diagrams of classes/Tables in a Database, this si object diagram
![image](https://user-images.githubusercontent.com/22464805/198877180-beea3743-8f6a-4665-af50-b6e77d754ea1.png)

### Component Diagram
> Relationship betweeen components of a system, including the  components and their sub-components. It also includes the dependencys between each of the systems.
![image](https://user-images.githubusercontent.com/22464805/198877219-ff884e60-1c19-4a21-ae46-ba7b0df0cd69.png)

### Object Diagram
> A more simplified view of the class diagram, in a specific moment. However,  It is more a high level view, during a business transaction. This one is hardly used.
![image](https://user-images.githubusercontent.com/22464805/198877293-3500b762-706d-45ff-bdb4-07a10783c9ae.png)

### Package Diagram
> Shows what packages/depedencies are in different layers of a system.
![image](https://user-images.githubusercontent.com/22464805/198877425-3ecd506d-6879-4224-b1ad-6cee346409d8.png)


## More important ones we'd probably are goin to use

### System Level Data Flow Diagram
> A high level example of how information flows through a system, Only describing possible objects/information going through different business transactions. This can be more easily described in later diagrams.
![image](https://user-images.githubusercontent.com/22464805/198877597-5e800234-59ad-44f1-997f-4cbf486f6e95.png)

### Use Cade Diagrams
> Another High level daigrams, that display what processes which actors are going to do. An "actor" can be described how a potential individual will interact withen in a ssytem. In the example below, someone who is a pateint can only request an appointment in the system. However, a clerk can create pateint profiles, reieve orders, and book appointments.
![image](https://user-images.githubusercontent.com/22464805/198877947-6812c17f-cff4-4f87-b819-3d7dcac2cb27.png)

### Activity Diagram.
> Represents what "activities" a user be doing in a specific order. Example: A user logins, Correct login goes to user settings page. 
![image](https://user-images.githubusercontent.com/22464805/198878143-5c6fcd1f-096a-42f6-8ffe-da16df8cde06.png)

### Sequence Diagram
> A Sequence diagrams display how a group of functions, database tables, and objects will be used to in a specific transaction.  

![image](https://user-images.githubusercontent.com/22464805/198878507-c2bf3c3e-6bec-40bf-9781-5f972eee316c.png)
#### Example Above explained: 
 - A student enrolling in a student seminar is considered the transaction.
 - Each arrow is a function, such as enrollStudent(aStudent). "aStudent" is the object being passed into the enrollStudent() function. 
 - The Seminar course and courses are tables withen the database.



### State Diagrams
 > A state diagram describes which states or steps are in a multi-transactional process
 ![image](https://user-images.githubusercontent.com/22464805/198879005-eddfa049-08e2-40cc-8709-a60d92338fea.png)

#### Example above explained
 = In a E-commerce website, a shoppping cart is a multi transactional process.
 - A shopping cart can be a single row in a shoppingCart Table, but once at least one item is added, the state is changed from "empty" to "ready for checkout"
 - Anytime an online shopper visits the website, a shoppingCart is created, which is empty.
 - The arrow is can be a function/action, which leads to a potential change in state. Every state needs a function/action to change, however every action doesn't have to lead to a state change. 
 - In the example above, other items can be added to the shoppingcart, however only 1 item is needed in the cart to have the state to be "ready for checkout"
 - When the online shoppper "checks out", the state of the shoppingCart changes to "checking out", and items can no longer be added
 - Once check out is complete, the check out is finished, and the shoppingCart is cleared of any items.
 
### Class Diagram
> A overview of the database and it's tables. The tables are organized in a way to describe the relaationship with each other. NO REVIEW NEEDED FOR THIS ONE

![image](https://user-images.githubusercontent.com/22464805/198879395-cc16e367-f76a-4aee-956c-d7a4b2aac70b.png)
