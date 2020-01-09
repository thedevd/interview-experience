## Nagarro (Role: Java Lead | Location: Gurgaon | Date: 3rd Jan 2020)
I was interviewed for Java Lead role with technologies - Java8, Spring, Spring boot, Spring Microservices, Hibernate JPA, AWS, Redis, MySQL, Maven, unix, docker, design patterns. There were total 6 rounds I faced.

**Round 1 - IQ** \
IQ based 50 questions in 12 minutes.

**Round 2 - Coding** \
Coding rounds (Three questions will be given that you have to complete in 1 hour 15 minutes). These are very very easy, just you need to know basic of java apis like String manipulation, hashmap. I remember two questions which were- converting C++ variable to java standard and vice-versa and second one was counting the character in a string and arrange the counts in alphabatical order (ababcd --> a2b2c1d1).

**Round 3 - Multiple choice based questions** \
In this round they had mutliple choice question based on everything related to java development and microservices such as Java, Java8, Spring, Spring boot, Spring Microservices, Rest WebServices, Hibernate, JPA, MySQL, AWS, design patterns and many more. Time given for this round was 200 minutes (3 hours 20 minutes). I completed it in 1 hour.

**Round 4 - Technical** \
This was initial technical round with mixed of technologies based question some of them are -
* Project details.
* How many ways to create string in java (Wanted to know about concept of string constant pool and intern() method).
* Difference b/w HashMap and concurrentHashMap.
* Difference b/w failfast and failsafe iterator.
* Features of Java8. Explaine each one with thier advantage.
* Spring vs Spring boot.
* Singleton vs prototype. Annotation for this?
* Hibernate advantages. Diff b/w hiberante and jpa.
* save() vs persist() in hibernate.
* cascade vs inverse in hiberante.
* What are strategies of @GeneratedValue for primary key.
* Spring bean life cycle.
* Monolythic vs microservice.
* What libraries you used in microservices.

**Round 5 - Technical** \
This was mostly focused on system design using microservice architecture.
* Design food delivery app using microservice architecture.
  * Explain the complete flow of a request going through each and every microservice of the app.
  * What would you do if one of the microservice does not respond when serving the request. (he wanted to know how fault tolerance is achieved)
  * How transactions will be taken care in this design (He wanted to know about saga design pattern).
  * Type of distributed transaction.
* HashMap related tricky questions like what if we have overriden equals() but not hashcode() so what would happend if try to get from map using object as key.
* How the redis cluster works? Is it master-slave or master-master like cassandra?
* Give example of builtin Functianal interfaces in java.
* Tree related questions (How do you desing the class and what are traversals methods in tree).
* How to generate fabonacci series using java8 stream APIs.

**After this round, I was asked to share my documents for further process of releasing the offer letter, but do not know what happend there, HR asked me to give interview on Unix/Maven/SQL/Docker for other profile requirements. So I had to give another round**.

**Round 6 - Technical** \
This was majorly on Unix, docker, sql and little bit on hibernate too.
* Some basic commands of unix such as 
  * how to remove dir+sub directories (rm -r command)
  * how to copy file from local to remote and vice-versa (scp and scp -r)
  * how to seach a text in file (usage of grep and thier widely used option)
  * Tell some commands to work with any file in vi edition.
  * What are permission and how to set it (Use of chmod command with combination of 4(read) + 2(write) + 1(execute) )
  * Do you know how to write shell script to look for a directory for the log files and send email after each an hour with information of the log file name)
* How to setup a docker so that It should automatically start after any crash.
* How to list the configuration of a container which were used at the time of starting the container at the beginning.
* Write a simple class to represent Entity Employee using Hibernate annotations.
* Sql query to find the manager id, manager name and no of employees working for them (Considering table has empid, empname, mgrid).
* Types of index in mysql and Explain clustered-index with example.

**Some extra questions, which may be asked by Nagarro for java+springboot+microservice profile**
* Spring AOP
* Tree and Graphs (DFS vs BFS)
* Optimistic vs pessimistic locking in database system.
* ACID property in transaction.
* Isolation levels in transaction and what is Dirty read, non-repeatable read and phantom read). How this is implemented in Spring boot. (wanted to know about @Transactional annotation)
* Memcache vs redis.
* Configuration management problem in microservice architecture and how to solve this in spring cloud.
* Spring security.
* Oauth2.
