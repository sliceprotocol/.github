# ⚖️ Slice

**Slice is a neutral, on-chain dispute resolution protocol.**  
Any app, smart contract, or agent can plug into Slice to resolve disputes in a trustless way.

Slice selects jurors, collects private votes, and publishes a final on-chain ruling that external protocols can safely execute.

---

## 🧠 What Slice Does

Slice acts as a **truth oracle for disputes**.

When two parties disagree, Slice:
1. Randomly selects jurors from a staked pool
2. Collects private votes (commit–reveal)
3. Aggregates votes on-chain
4. Publishes a final ruling: **Party A or Party B**

That’s it.  
Slice doesn’t escrow funds, enforce rules, or judge intent — it **only decides**.

---

## 🔗 Who Uses Slice?

Slice is protocol-agnostic and app-agnostic.

It can be integrated by:
- 🧑‍💻 Freelance & work-for-hire platforms  
- 🤝 P2P trading & escrow systems  
- 🏠 Rental & service marketplaces  

If your system needs a **neutral decision**, it can use Slice.

---

## 🏗️ How Integration Works

**External protocol flow:**

```text
Your Contract → createDispute() → Slice
Slice → juror selection → private voting → ruling
Your Contract → reads ruling → executes logic
```
