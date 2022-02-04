# Queue_modeling_MM2
Queue modeling : comparing two models M/M/1 or M/M/2?
A sales agency has two counters and wonders how to organize the queues. In this project, we want to compare two situations numerically.

### fist situation: 
1. In the first situation, we assume that there are two identical and independent queues of types
M/M/1. For each of them the arrivals are separated by exponential times with parameter λ , the
service times are exponential with parameter β (we assume 2λ < β).

### second situation:
2. We decide to merge the two queues to make a single queue with two wickets called M/M/2.
Customers continue to arrive at the post office at the same rate, so according to an exponential with parameter
2λ. The service time of each customer is still exponential with parameter β. There are now two
counters simultaneously, i.e. when a customer arrives and a counter is free, he is assigned to this
wicket. We will assume that when the two wickets are free, the first is occupied in priority. When
the two counters are occupied, the customers are in line. We often encode the state of the system as
next :
• (0, 0) both wickets are free
• (1, 0) only the first wicket is occupied,
• (0, 1) only the second wicket is occupied,
• (n, 1) both counters are busy and there are n − 1 customers in the queue (for n ≥ 1).
