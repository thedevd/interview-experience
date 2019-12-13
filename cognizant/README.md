## Congnizant (Role: Senior Big Data Engineer | Location: Gurgaon | Date: 13th Dec 2019)
I was interviewed directly with client of Cognizant Technogoy Services. (There were total 3 rounds I faced)

### Level 1
* First obviouse question was tell me about your experience on Big data. And then follow-up questions on the current project (Cluster size, data volume etc..)
* We have a file in hdfs with this type of data -
  ```
  a,1|b,2|a,4|b,2
  b,3
  a,5|c,1
  ```
  Write a scala-spark program to achieve the following output -
  ```
   a 10
   b 7
   c 1
  ```
  **Note** -> Do this using RDD approach and arrange the output in descending order of the count.
  
* We have a file in hdfs with following content -
  ```
  a,1|b,2|c,4|d,2
  b,3
  a,5|c,1
  ```
  Write a scala-spark program to display them in tabular form like this -
  ```
  a   b   c   d
  1   2   4   2
  -1  3   -1  -1
  5   -1   1   -1
  ```
  So you see if do not have value for a particular column in the line we have to store -1. (for example row 2 has only the value for b i.e b,3. so in the output the second row has -1 3 -1 -1 for a,b,c,d respectively.)
  
* You have encountered outofmemory issue in your spark cluster, how are you going to approach this and implement the best practice to avoid this in future?
* What factors you need to keep in mind in deciding the memory and cores configuration to be given to your spark cluster's executor?
* How do you decide which format to use for your data either Avro or Parquet. Explain by giving a usecase?
* You have three machines in your spark cluster, and each worker in the cluster is having unique key and thier count. Design a solution to sort them in ascending order.
  ```
  Machine1          Machine2          Machine3
  A,10              D,5               E,5
  Z,30              B,70
  C,20
  ```

### Level 2
* Tell me an achievement (troubleshooting/optimization/feature enhacement) that you thing was worth to the project ?
* We have two tables A (100 thousands row) and table B (100 milion rows), how do you join them considering optimized way. Further to that lets say both tables are very very huge, how do you join them on a column.
* We have 20 nodes cluster, now you have to design a blocking kind of operation in such a way that only 10 nodes will be allowed to execute a particular operation. (Just like semaphore in java) 
* More (not able to recall)

### Level 3
* Explain each Object oriented concept with example?
* We have a list {"cat", "dog","god"}, write an algorithm to group the words which are anagram for example here dog and god are anagrams, so produce output like this -
  ` [{cat}, {dog,god}]`
* How hashmap works internally?
* How to make class immutable in java. What are the benefits of making a class immutable?
* Why java has Wrapper classes for each primitive types like int --> Integer, long --> Long, char --> Character?
* More (not able to recall)
