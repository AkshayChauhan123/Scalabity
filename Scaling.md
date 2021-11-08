# Scaling

The process of increasing or decreasing the capacity of the system by changing the number of processes available to service requests is called **Scaling**.

When and why do we need **_Scaling_** ?

When the user base grows exponentially or the services becomes popular from what it started out as so handling traffic would be difficult then the Scaling will help us to keep our services **up**.

There are two ways to perform scaling : 

1. **Horizontal Scaling**

2. **Vertical Scaling**


![Horizontal Scaling vs Vertical Scaling](https://res.cloudinary.com/nlogn/images/w_698,h_393/f_auto,q_auto/v1587453317/Purple-and-Cream-Illustrated-Technology-Pitch-Deck-Presentation-5/Purple-and-Cream-Illustrated-Technology-Pitch-Deck-Presentation-5.jpg?_i=AA)


## Vertical Scaling or Scaling-up

Adding more resources to a single node and adding additional CPU, RAM, and DISK to cope with an increasing workload.

Basically, vertical scaling gives you the ability to increase your current hardware or software capacity. We can also buy a whole new machine, that is more powerful than can handle the more load.


## Horizontal Scaling or Scaling-out

Adding more instances of machines without first implementing improvements to existing specifications. 

By scaling out, you share the processing power and load balancing across multiple machines.


## **_Vertical Scaling_** vs **_Horizontal Scaling_** 


| Vertical Vs Horizontal Scaling| Vertical scaling | Horizontal Scaling |
|-----------------------|-----------------------|-----------------------|
| Load Balancer | Load Balancer not Required | Load Balancer Required
| Data | Data is executed on a single node | Data is partitioned and executed on multiple nodes |
| Data Management | Easy to manage – share data reference | Complex task as there is no shared address space |
| Downtime | Downtime while upgrading the machine | No downtime |
| Upper limit | Limited by machine specifications | Not limited by machine specifications |
| Cost | Lower licensing fee | Higher licensing fee |

## We can also choose a hybrid solution, Here we take qualities of both, Vertical Scaling and  Horizontal Scaling.


# Load Balancers

A **Load Balancer**  efficiently distributes incoming network traffic across a group of backend servers, also known as a server farm or server pool.

A load balancer acts as the “traffic cop” sitting in front of your servers and routing client requests across all servers capable of fulfilling those requests in a manner that maximizes speed and capacity utilization and ensures that no one server is overworked, which could degrade performance. 
If a single server goes down, the load balancer redirects traffic to the remaining online servers.
When a new server is added to the server group, the load balancer automatically starts to send requests to it.


![Load Balancer Working](https://www.nginx.com/wp-content/uploads/2014/07/what-is-load-balancing-diagram-NGINX-768x389.png)


## Resources

1. [System Design: What is Horizontal vs Vertical Scaling? Be A Better Dev YouTube channel](https://www.youtube.com/watch?v=p1YQU5sEz4g)

2. [Load Balancing](https://www.nginx.com/resources/glossary/load-balancing/)

3. [Scaling from GFG](https://www.geeksforgeeks.org/system-design-horizontal-and-vertical-scaling/)

4. [Importance Of Scalability](https://www.conceptatech.com/blog/importance-of-scalability-in-software-design)

5. [Horizontal vs Vertical Scaling](https://www.clickittech.com/devops/vertical-vs-horizontal-scaling/)