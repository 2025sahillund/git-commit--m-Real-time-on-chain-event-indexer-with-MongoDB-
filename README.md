
---

# 🧩 ARCHITECTURE EXPLANATION 

Use this **verbatim** in submission or PPT:

> Our system continuously listens to on-chain transfer events using an off-chain indexer. Each event is normalized and passed through a signal processor that filters noise and detects high-value transfers. Valid signals are persisted in MongoDB for observability and simultaneously pushed to subscribed users via Telegram in real time. The pipeline is modular and can be extended to support multiple chains, event types, or notification channels.

---

# 🎯 PROBLEM STATEMENT ALIGNMENT 

### What was your PS?
> **Real-Time On-Chain Event Indexer & Notification System**

### How your project matches it:

| PS Requirement | Your Implementation |
|---------------|--------------------|
| Real-time indexing | ERC-20 Transfer listener + dynamic trigger |
| Noise filtering | Rule-based signal processor |
| Event persistence | MongoDB with unique tx hash |
| Notifications | Telegram real-time alerts |
| Production-ready infra | Modular services, retries, validation |


“We focused on infra reliability and signal quality instead of UI, which is why our solution mirrors real production Web3 monitoring systems.”_

---



