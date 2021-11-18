## Question
# What is fault tolerance?

--

# What is the interviewer looking for?
- Understanding of fault tolerance in the context of microservices
- Importance and its benefits

--

# Answer
- Ability of an architecture to continue operating in the event of the failure of some of its component(s)
- How much tolerance does the system have for a specific fault
- Some of the benefits:
    - Prevent disruptions arising from a single point of failure, ensuring high availability and business continuity
    - Helps applications fail fast and recover smoothly

---

## Question
# What are some of strategies/patterns to implement fault tolerance in microservices?

--

# What is the interviewer looking for?
- Understanding of fault tolerance in the context of microservices
- Awareness of various fault tolerance patterns
- Whether you have hands-on experience

--

# Answer
- Fault tolerance solutions usually focus on
    - Circuit Breaker
    - Bulkhead
    - Retries
    - Rate limiters
    - Timeouts
- Supported Implementations
    - Netflix Hystrix (maintenance mode)
    - Resilience4J
    - Sentinel
    - Spring Retry

---