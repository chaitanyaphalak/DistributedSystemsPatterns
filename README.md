Single Node Patterns:
  1. Sidecar
    eg. 1) Add HTTPS support
        2) Dynamic configuration
        3) Modularity and reuse of components
        4) Making a simple PaaS service
        5) Adaptation and monitoring of services/resource usage
  2. Ambassador
    eg. 1) Reuse and modularity
        2) Shard a service
        3) Service discovery and configuration/service brokering
        4) Request splitting/experimentation on partial service
  3. Adapter
    eg. 1) Expose different interfaces among different services as a single common interface
          a) Monitoring with prometheus
          b) Logging with fluentd
          c) Health check monitor

Serving Patterns:
  1. Replicated Load-Balanced Services
    eg. 1) Stateless replicated services
        2) Caching layer
        3) SSL termination
        4) Rate limiting and denial of service prevention
        5) Application layer/sticky session based replicated services
  2. Sharded Services
    eg. 1) Sharded cache
        2) Sharded and replicated cache
        3) Consistent hashing sharded services
        4) Sharded replicated serving
  3. Scatter/Gather
    eg. 1) Scatter/Gather with root distribution
        2) Scatter/Gather with leaf sharding
  4. Functions and Event-Driven Processing
    eg. 1) The Decorator Pattern: Request or Response Transformation
        2) Handling events
        3) Event based pipelines
  5. Ownership Election
    eg. 1) Leader election
        2) Implementing locks
        3) Implementing ownership
        4) Handling concurrent data manipulation

Batch Computational Patterns
  1. Work Queue Systems
  2. Event-Driven Batch Processing
    eg. 1) Copier
        2) Filter
        3) Splitter
        4) Sharder
        5) Merger
        6) Pub/Sub system
  3. Coordinated Batch Processing
    eg. 1) Join(or Barrier Synchronization)
        2) Reduce