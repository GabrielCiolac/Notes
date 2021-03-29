[[Simulation]] is used when analizing queue models.

Queueing models, rather analyized mathematically or through simulation, provide analysist with a powerful tool to determin throughput of a queueing system.

## Characterestics of a Qeueing System:
- *Customers*, and *Servers* (Consumer/Producer)
- Calling population, is the set of potential consumers
- Finite or Infinite Calling Populations
	- In infinite populations, the arrival rate is not affected by consumers who left the calling population. 
- System Capacity, the limit to the number of consumers which can be waiting, or using the system
- The Arrival Process, for infinite calling populations it's usually characterized in terms of interarrival times, these times can either be scheduled or random(on a Poisson distribution).
- [[Queue Behavior]], how consumers react when faced when throughput and queue size.
- Queuing Displine, algoritm for determining who gets serverd first
- Service Time, how long it takes a consumer to be served


## Queueing Notation:
- A: Represents the interarrival time distributon
- B: Represents the service-time distributon
- c: Represents the number of parallel servers
- N: represents the system capacity
- K: represets the size of the calling population

Formated: A/B/c/N/K
### A and B can be represted by the following
- M: Exponential
- D: Constant
- Ek: Erlang
- PH: Phase Type
- H: Hyperexponential
- G: Arbitrary
- GI: Independent


