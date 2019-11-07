# Introduction

## Azure application architecture

- Applications scale horizontally instead of vertically
- Parallel & Asynchronous operations (Find exact meaning of these in terms of computing)
- Telemetry is important (what exactly is telemetry)
-

### Terms

Parallel computing: distributing the application in such a way that it can be executed concurrently on separate processors & then the results can be accumulated at the end

[Asynchronous vs Synchronous Execution](https://stackoverflow.com/questions/748175/asynchronous-vs-synchronous-execution-what-does-it-really-mean)

Telemetry: Telemetry is the collection of measurements or other data at remote or inaccessible points and their automatic transmission to receiving equipment for monitoring.

    Strong Consistency offers up-to-date data but at the cost of high latency.
    While Eventual consistency offers low latency but may reply to read requests with stale data since all nodes of the database may not have the updated data.

MTBF(Mean time between failure)=total operational uptime between failures / number of failures
MTTR (Mean time to repair)=how long it will take to get a failed product running again.

- Application scaling & performance can be enhanced by using the following:
  - Data partitioning : really useful, this if I believe correct deals with db sharding
