# Different Service Resilience

## Cloud Research

There are three different levels of resilience for services:
- Global Resilient - A service operates globally with a single database, and its data is replicated across multiple regions inside AWS. One region can fail but the services will keep running. It would take all of the regions in the world to fail for it to experience a full shutdown. 
- Region Resilient - Services that operate in a single region with one set of data per region. Region resilient services operate as separate services in each region and they generally replicate data to multiple AZs in that region. If an AZ fails in one region then the service will continue operating but if the whole region fails then the service will fail. 
- Availability Zone Resilient - services that operate from a single AZ. If the AZ that the service is provisioned into fails then that service will fail. If the hardware fails in an AZ, it'll continue working because AWS has resilient storage systems. 

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[https://twitter.com/sarahg813/status/1305711736473911297](https://twitter.com/sarahg813/status/1305711736473911297)
