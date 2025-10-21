# SM Paints – Process Improvement Simulation

**Team:** Milonee Parekh, Natalie Woods, Evelyn Galarza, Paul Glatz, Kudakwashe Mundove
**Tool:** Arena Simulation  
**Simulation Horizon:** 5 replications × 60 days (terminating model)

---

## Business Challenge
SM Paints was unable to consistently deliver orders to distribution centers within its three-day target, limiting its lean initiative to reduce inventory while maintaining service levels. The production process — **Mix & Grind, Thinning, Holding, and Filling** — faced capacity and scheduling constraints that delayed order fulfillment.

The goal was to determine which operational changes could help SM Paints reach a **98% on-time delivery rate** without large capital investment.

---

## Approach
1. **Modeled the end-to-end workflow** in Arena with Poisson order arrivals (≈23 per day) and realistic tank capacities.  
2. **Defined batch attributes** for quart and bucket proportions to represent order variability.  
3. **Simulated utilization and throughput** across Mix & Grind, Thinning, and Hold operations.  
4. **Tested improvement scenarios**, including adjusted hold delays, tank sequencing, and dedicated process lines.

---

## Key Findings
- **Hold tanks** were the primary bottleneck. Extending hold delays sharply reduced throughput.  
- **Mix & Grind utilization (~71%)** indicated limited spare capacity.  
- **Thin and hold tanks (27–32%)** showed imbalanced flow.  
- **Average throughput time:** 7.1 hours (95% CI: 6.4–7.9), stable across replications.

---

## Recommended Solution
Introducing a **dedicated quart filling line** significantly improved system flow:
- Quart orders previously shared filling capacity with gallon and bucket batches, creating hold delays.  
- A separate quart line isolates smaller-volume jobs, freeing existing tanks for larger batches.  
- Revised tank-assignment rules further balanced utilization across resources.

**Supporting Actions**
- Optimize hold-tank scheduling to minimize idle capacity.  
- Extend mixer operating hours or add minimal capacity to prevent upstream buildup.

---

## Outcome
The proposed configuration — adding a quart line and optimizing tank allocation — reduced congestion, stabilized flow, and improved throughput.  
Simulation results indicate that these targeted process changes would move SM Paints closer to its **98% on-time delivery goal** without major infrastructure expansion.

---
