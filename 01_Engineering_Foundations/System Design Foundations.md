

Tags: #SystemDesign #Engineering #Foundations

## 📌 Core Concepts

### Scalability
- Vertical vs Horizontal scaling
- Stateless vs Stateful services
- Partitioning & Sharding

### Reliability & Availability
- Redundancy & Failover
- Replication strategies
- CAP theorem & PACELC trade-offs

### Data Management
- Consistency models (Strong, Eventual, Causal)
- Distributed transactions
- Caching strategies (Write-through, Write-back, TTL)

### Networking & Communication
- REST vs gRPC vs GraphQL
- Message Queues (Kafka, RabbitMQ, Pulsar)
- Pub/Sub vs Point-to-Point

### Storage Systems
- SQL vs NoSQL
- Indexing and query patterns
- Distributed file systems (HDFS, Ceph, GFS)

### Observability
- Logging (structured vs unstructured)
- Metrics (Prometheus, Grafana)
- Tracing (Jaeger, OpenTelemetry)

---

## 🛠️ Design Patterns

- **Load Balancer** → distribute traffic efficiently
- **Leader Election** → for consensus systems
- **Circuit Breaker** → handle service failures gracefully
- **Event Sourcing** → rebuild state from events
- **CQRS** → split reads and writes for performance

---

## 🔗 Links to Other Notes
- Builds on [[CS_Fundamentals]]
- Closely tied to [[Distributed Systems – Core Concepts]]
- Provides architecture foundation for [[02_MLOps/Core_Concepts]]
- Supports project ideas in [[04_Projects/Portfolio_Tracking]]

---

## 📚 Resources
- Book: *Designing Data-Intensive Applications* – Martin Kleppmann
- Book: *Site Reliability Engineering* – Google
- Course: [System Design Primer](https://github.com/donnemartin/system-design-primer)
- Practice: Grokking the System Design Interview

---

## ✅ Progress Tracking
- [ ] Learn CAP theorem deeply
- [ ] Practice designing a URL Shortener
- [ ] Design a distributed chat application
- [ ] Create an observability setup for a toy system
