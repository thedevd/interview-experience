## Synechron (Role: Java/Spark Developer | Location: Pune | Date: 23 Nov 2019)
I was invited for F2F interview at Nehru place, Delhi. There were total 3 rounds (L1, L2 and HR round).
1. **L1-round** - It was like a telephonic round where I was interviewed with one to one technical discussion mostly threoritcal part.
   * First obviouse question was tell me aboyt your experience on Big data.
   * What is CountDownLatch in java?
   * What major changes have been done in Spark 2.x as compared with spark 1.6?
   * Flow of spark program execution?
   * What are different deployement modes of spark? Difference b/w client and cluster mode?
   * I have been given a piece of code with list of transformation and then collect() action and then further transformation+action on the result of collect. And the question was very straightforward that which piece of code will run on worker and which on driver node?
   * What are Kafka Producer Delivery Semantics? (Reference- https://dzone.com/articles/kafka-producer-delivery-semantics)
   * If keys are not given when producing data by kafka producer then how Kafka distributes the data across no of partitions of a topic? (The answer was round-robin fashion used by default partitioner)?
   * I had been given a dataframe with three columns and the question was How to derive a new column from an existing columns of spark dataframe? (reference- use of with().otherwise())
   * Write a sample of spark function (note here it is mentioned function not method --> function is defined with val and methods are with def)
   * What is spark closure?
   * We have an RDD, how the default no of partitions are decided? How to increase the paritions?
   * colesce() vs repartition()?
   * groupByKey() vs reduceByKey()?
   * some more... not able to recall them :(
   
 2. **L2 round** - This was more of coding round.
    * We have a csv file having the states with its population along with country? How to load it and display the the country name with max no of population?
    * Write simplest example of wait-notify concept?
    * What is SynchronousQueue?
    * What is hashcode and equals contract? How to use them? Code an example? What happens if we return a constant from hashcode() implementation?
    * We have employee object and we have hashcode() and equals() imlementation. Explain internal of inserting employee objects in HashSet?
    * Which is better to process structured data - RDD or dataframe? (Dataframe , hint is sparkSql optimization engine).
    * Have you ever come to in a situation where you needed to analyze the DAG in spark UI?
    * Dynamic Programming problem - We have a 3X3 matrix and find total how many ways are there to reach to ending cell of matrix starting from very first cell, the constraint is that you can only go right or bottom (hint- 0 ways for 1X1 metrix, 1 way from 1X2 matrix ..... and total 6 ways are there to reach ending cell starting from very first cell in 3X3 matrix)
    * What is partial functions in scala? Write a simple partial function.
    * We have list of no as - 111, 143, 233, 350, 90, 410 and we want output like - 100, 11, 100, 43, 100, 100, 33, 100, 100, 100, 50, 90, 100, 100, 100, 100, 10. How to do this in scala? (Hint is use tailRecursive function with pattern matching. Or it is also possible using fill() method of Seq collection )
    * We have list - 1,2,3,4,5,6. Generate all the possible numbers using this list i.e. 111111, 111112, 111113..... so on. (hint is use of for comprehension loop)
    * Future and Promises in scala?
    * What is monad in scala?
    * Since scala has no concept of checked exception, so what are alternatives to inform the user of the API about the possible errors that they need to take care? (hint using sealed trait and it exhaustive pattern matching concept)
    * What is Class level locking and object level locking in java?
    * If we have synchronized in java then Why Locks? What do you mean by the word Reentrant in ReentrantLock?
    * What is semaphores in java?
    * What is lamba function in Java? What is functional interface? What is pure function?
    * What is covariant in java? Advantage of using this.
    
 3. **HR round** - Discussion on reason to change, Constraint on Shift timings and location, salary expectation etc..
