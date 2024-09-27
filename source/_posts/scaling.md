---
title: "Scaling: Horizontal vs. Vertical"
---


![Scaling](/images/scaling.png)

## Vertical Scaling

**Definition**: Vertical scaling involves adding more power to a single machine, such as increasing CPU, RAM, or storage capacity.

### Pros
- **Simplicity**: Easier to implement as it involves upgrading the existing machine without requiring changes to the application.
- **No App Changes**: Existing applications generally do not need modifications to benefit from increased resources.

### Cons
- **Capacity Limitations**: Limited by the maximum capacity of the machine. There’s a physical limit to how much power a single machine can handle.
- **Cost**: Upgrading hardware can be expensive, especially for high-end components.
- **Single Point of Failure**: If the machine fails, the entire application or service can become unavailable.

## Horizontal Scaling

**Definition**: Horizontal scaling involves adding more machines to distribute the load and increase capacity.

### Pros
- **Fault Tolerance**: Enhanced reliability and fault tolerance since the application is distributed across multiple machines. Failure of one machine does not bring down the entire system.
- **Traffic Handling**: Better suited for handling increased traffic and load by distributing the workload among several machines.
- **Scalability**: Easier to scale out by adding more machines as needed.

### Cons
- **Complexity**: More complex to implement and manage. Requires designing the application to work in a distributed environment.
- **Distributed App Design**: Needs changes to the application architecture, such as implementing load balancing, distributed databases, and network configurations.