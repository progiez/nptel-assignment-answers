# NPTEL Cloud Computing and Distributed Systems Week 03 Assignment Answers

Are you looking for NPTEL Cloud Computing and Distributed Systems Week 03 Assignment Answers? This repository will help you find your answers and solutions for Week 03 of the **Cloud Computing and Distributed Systems** course. We provide detailed solutions to help you complete your assignments efficiently.

## Cloud Computing and Distributed Systems Week 3 Answers (Jan-Apr 2025)

***

1\. In a Classical Algorithm of Ring Election, what will be the message complexity for N labelled processes.

- (N-1) messages
- (2N-1) messages
- (3N-1) messages
- (4N-1) messages

[View Answer](https://my.progiez.com/courses/cloud-computing-and-distributed-systems/)

***

2\. True or False ?

There is no leader election algorithm for anonymous rings, even if algorithm knows the ring size (non-uniform) and synchronous model.

- True
- False

[View Answer](https://my.progiez.com/courses/cloud-computing-and-distributed-systems/)

***

3\. True or False ?

Zookeeper is a replicated service that holds the metadata of distributed applications.

- True
- False

[View Answer](https://my.progiez.com/courses/cloud-computing-and-distributed-systems/)

***

4\. True or False ?

“Leader Election problem represents a general class of non symmetry-breaking problems.”

- True
- False

[View Answer](https://my.progiez.com/courses/cloud-computing-and-distributed-systems/)

***

5\. ZooKeeper itself is intended to be replicated over a sets of hosts called :

- Chunks
- Ensemble
- Subdomains
- None of the mentioned

[View Answer](https://my.progiez.com/courses/cloud-computing-and-distributed-systems/)

***

6\. Find the message and time complexity of below algorithm:

send value of own id to the left

when receive an id j (from the right):

if j > id then

forward j to the left (this processor has lost)

if j = id then

elect self (this processor has won)

if j < id then

do nothing

- O(n
  <sup>
  2
  </sup>
  ) Messages and O(n) time
- O(logn) Messages and O(logn) time
- O(n) Messages and O(n
  <sup>
  2
  </sup>
  ) time
- O(n
  <sup>
  3
  </sup>
  ) Messages and O(n) time

[View Answer](https://my.progiez.com/courses/cloud-computing-and-distributed-systems/)

***

7\. In the O(nlogn) messages leader election algorithm, the probe distance in phase k is **_**\_**_** and the Number of messages initiated by a processor in phase k is at most \_\_\_\_\_\_\_\_\_\_\_\_\_\_including probes and replies in both directions.

- 2
  <sup>
  k−1
  </sup>
  ,4
  <sup>
  k
  </sup>
- 2k,4∗2
  <sup>
  k
  </sup>
- k,2
  <sup>
  k
  </sup>
- 2
  <sup>
  k
  </sup>
  ,4∗2
  <sup>
  k
  </sup>

[****See also**  **Cloud Computing and Distributed Systems Week 2 Answers****](https://progiez.com/cloud-computing-and-distributed-systems-week-2-answers)

[View Answer](https://my.progiez.com/courses/cloud-computing-and-distributed-systems/)

***

8\. Consider the following statements:

**Statement 1:** When two processes are competing with each other causing data corruption, it is called deadlock

**Statement 2:** When two processes are waiting for each other directly or indirectly, it is called race condition.

- Only statement 1 is true
- Only statement 2 is true
- Both statements are true
- Both statements are false

[View Answer](https://my.progiez.com/courses/cloud-computing-and-distributed-systems/)

***

9\. In an anonymous ring topology, which of the following is true regarding leader election?

- Leader election is always possible in both synchronous and asynchronous settings
- Leader election is possible only if the number of nodes is known.
- Leader election is impossible in an anonymous ring without additional mechanisms.
- The election can be performed using a random number assigned to each node.

[View Answer](https://my.progiez.com/courses/cloud-computing-and-distributed-systems/)

***

10\. How does having unique node identifiers (non-uniform ring) affect the leader election process?

- It makes the election process more complex and inefficient.
- It allows leader election to be completed in a finite number of steps using identifier-based comparison.
- It has no impact, as the algorithm would work the same way in uniform and non-uniform rings.
- It requires additional communication rounds to resolve conflicts among nodes
