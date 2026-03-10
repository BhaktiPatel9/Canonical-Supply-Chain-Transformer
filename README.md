# Canonical Supply Chain Transformer 🏗️

### The Challenge
Managing multi-terabyte datasets often leads to "data swamp" conditions where manual reconciliation is constant. At **K.G.Patel & Co.**, I faced an 8-hour financial closing cycle due to unoptimized SQL.

### The Solution
I built this transformation layer using a **Medallion Architecture** (Bronze/Silver/Gold). 
* **Performance Tuning**: Swapped legacy subqueries for CTEs and Window Functions, mirroring the **25% speed improvement** I achieved in previous roles.
* **Canonical Modeling**: Built a "Single Source of Truth" for **OTIF** (On-Time In-Full) and **OOS** (Out-of-Stock) metrics.

### Impact
* **Efficiency**: Cut the monthly financial closing cycle by over **8 hours**.
* **Accuracy**: Reduced manual data-reconciliation errors by **40%**.
