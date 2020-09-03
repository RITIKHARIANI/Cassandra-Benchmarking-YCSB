# Cassandra-Benchmarking-YCSB

YCSB Benchmark Tests on Cassandra NoSQL Database. Ran Workloads A to F.

Workloads:
- Workload A: Update heavy workload: 50/50% Mix of Reads/Writes
- Workload B: Read mostly workload: 95/5% Mix of Reads/Writes
- Workload C: Read-only: 100% reads
- Workload D: Read the latest workload: More traffic on recent inserts
- Workload E: Short ranges: Short range based queries
- Workload F: Read-modify-write: Read, modify and update existing records