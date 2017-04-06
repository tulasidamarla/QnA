1)Migrating from Monolith to Microservices?<br>
a)Identifying the bounded contexts(or service boundaries)<br>
b)Seperate Frontend from Backend<br>
c)Introduce an API gateway<br>
d)split monolith incrementally<br>
Note: Build micro services for failure, monitoring, automation and testing. If all this is done successfully, boundaries can be pushed  even further to make a completely server less architecture. <br>(For more info refer: https://medium.com/@briceicle/migrating-from-a-monolith-to-a-microservices-architecture-99cecf8af366)

2)Difference between RPC and REST?<br>
RPC is used to call a function/procedure on a remote machine. It provides high-level of abstraction. But this may come with a penalty with regard to performance, as you will have to marshalling/unmarshalling even for trivial tasks.

Whereas, REST is more simple and flexible. It too, is used for communication between two machines using http. You can GET,POST,DELETE etc. using the http with respect to REST.
3)
