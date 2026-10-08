
### **4. Amazon ElastiCache (Redis / Memcached)**

#### **The Core Problem It Solves**

- **Database Bottlenecks & High Read Latency:** Storing data on disk (even fast SSDs) creates millisecond delays. When thousands of users request the exact same data simultaneously (e.g., a viral news article or popular product detail page), disk-based databases get overwhelmed.
    
- **Microsecond Response Times:** Solves the need for sub-millisecond retrieval of temporary, frequently accessed data.
    

#### **Key Strengths & Ideal Use Cases**

- **In-Memory Caching Layer:** Sits in front of RDS or DynamoDB to cache hot query results in RAM.
    
- **Best For:** Session storage, database query caching, real-time leaderboards, rate-limiting counters, and pub/sub messaging channels.