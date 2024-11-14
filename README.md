# Architecting Reactive Systems For Scalability And Reliability 🗽 by Francesco Cesarini

> Code BEAM NYC

![image](https://github.com/user-attachments/assets/c3efc782-12c7-4125-b6eb-28447f9ac8d6)

- Reactive manifesto https://www.reactivemanifesto.org/ using Java and Scala ideas about distributed systems.
- Expose or use a framework? Erlang background is the key for elixir developers.
- Erlang existed before kubernetes and kafka, the problems will be still the same.
- Designing for scalability with Erlang and OTP. Chapter 13 Node architecture, secret source for scalability.
- Formulate how to do things in the Erlang ecosystem. Why there aren't frameworks doing this? Akka Cluster: Actor Model for JVM.
- Software always needs speed and scalability.
- https://www.oreilly.com/library/view/designing-for-scalability/9781449361556/ 
- Chapter 13 to chapter 16: distributed architectures (at least two nodes), systems that never stop, scaling out, monitoring and preemptive support.
- All systems are distributed, like Phoenix apps, are distributed. Microservices are distributed.
- Concurrency (language) + Distribution (erlang) = scalability
- Immutability: property about don't change the state.

<img width="851" alt="image" src="https://github.com/user-attachments/assets/b1e6e552-4eb1-4dad-b893-00b20bbcb54b">

## Understand the trade-offs of your decisions

<img width="1029" alt="image" src="https://github.com/user-attachments/assets/6e5aa105-c0aa-40fa-853b-da9c4c5a9959">

<img width="945" alt="image" src="https://github.com/user-attachments/assets/230facf4-b100-4598-8bee-9f3aa7a78b01">

## Erlang achievements 

- https://www.allthingsdistributed.com/
- Amazon Science, Dynamo paper: https://www.amazon.science/publications/dynamo-amazons-highly-available-key-value-store
- Riak DB https://docs.riak.com/
- [The way GitHub helped Erlang and the way Erlang helped GitHub](https://www.infoq.com/interviews/erlang-and-github/)

![Ilustración_sin_título](https://github.com/user-attachments/assets/a29b2a04-6fc3-4ba0-9ae6-27ecf71ccdd2)

## Distributed architectures

![Ilustración_sin_título](https://github.com/user-attachments/assets/75ed717c-f669-4843-8ac5-541521cf3f0a)

![image](https://github.com/user-attachments/assets/9cd90625-fbb0-4b60-88b3-182376f9d8db)

![image](https://github.com/user-attachments/assets/bdd9f023-a41c-4e3e-bd29-4185d6376804)

