1)Migrating from Monolith to Microservices?<br>
a)Identifying the bounded contexts(or service boundaries)<br>
b)Seperate Frontend from Backend<br>
c)Introduce an API gateway<br>
d)split monolith incrementally<br>
Note: Build micro services for failure, monitoring, automation and testing. If all this is done successfully, boundaries can be pushed  even further to make a completely server less architecture. <br>(For more info refer: https://medium.com/@briceicle/migrating-from-a-monolith-to-a-microservices-architecture-99cecf8af366)

2)Difference between RPC and REST?<br>
RPC is used to call a function/procedure on a remote machine. It provides high-level of abstraction. But this may come with a penalty with regard to performance, as you will have to marshalling/unmarshalling even for trivial tasks.

Whereas, REST is more simple and flexible. It too, is used for communication between two machines using http. You can GET,POST,DELETE etc. using the http with respect to REST.<br>
3)Difference between throughput and latency?<br>
Ans: An assembly line is manufacturing cars. It takes eight hours to manufacture a car and that the factory produces one hundred and twenty cars per day.

The latency is: 8 hours.<br>
The throughput is: 120 cars / day or 5 cars / hour.<br>
Conclusion: Throughput is about how much and latency is about how fast.

4)What is meant by non reifiable type?<br>
A reifiable type is a type whose type information is fully available at runtime. This includes primitives, non-generic types, raw types, and invocations of unbound wildcards. Example of reifiable type is arrays. 

Non-reifiable types are types where information has been removed at compile-time by type erasure invocations of generic types that are not defined as unbounded wildcards. A non-reifiable type does not have all of its information available at runtime. Example of non-reifiable type are Examples of non-reifiable types are List<String> and List<Number>.

5)What is Heap Pollution?<br>
Ans: Heap pollution occurs when a variable of a parameterized type refers to an object that is not of that parameterized type. This situation occurs if the program performed some operation that gives rise to an unchecked warning at compile-time. An unchecked warning is generated if, either at compile-time or at runtime, the correctness of an operation involving a parameterized type (for example, a cast or method call) cannot be verified. For example, heap pollution occurs when mixing raw types and parameterized types, or when performing unchecked casts.

Note: Effect of heap pollution is classcastexception at runtime.


