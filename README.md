# Supply Chain, Retail & Product Analytics — A Decision-Focused Lab

This repository is a living analytics and thinking lab where I explore how data, constraints, and systems interact to shape decisions in retail, supply chain, and marketplace environments.

Rather than treating analytics as reporting, this work focuses on how insights influence **operational choices, product behavior, and system design** — particularly in areas like demand uncertainty, inventory trade-offs, returns, fulfillment, and pricing.

### 🛠 The Lab Framework
The projects and notes here combine:
* **Supply chain and retail fundamentals**
* **Data analysis, modeling, and simulation**
* **Product & systems-thinking** focused on real-world constraints

---

## 🚀 Projects

<details>
<summary><b>Project 1: Olist Logistics — From "Dumb Multipliers" to Dynamic Visibility</b></summary>

### The Problem
Olist relied on a **static 2× multiplier** for delivery ETAs to mask high logistics variance. In major hubs like São Paulo, this meant promising a **12-day delivery** for a journey that physically takes **~5 days**, significantly hurting checkout conversion rates.

### The Insight
Data analysis revealed that the “chaos” (standard deviation) in the Brazilian postal system is roughly equal to the average transit time itself. A purely mathematical fix—simply shortening the ETA—would push late deliveries to ~15–20%, creating a customer-support nightmare.

### The Recommendation
Shift the product strategy from **accuracy** (guessing a single “safe” date) to **transparency** (showing the journey). By implementing real-time milestone tracking, Olist can:
* Offer more aggressive early estimates.
* Use information—not time padding—to buffer chaos when delays actually occur.
</details>

<details>
<summary><b>Project 2: The "Leaky Bucket" — Quantifying the Trust Tax on Customer Retention</b></summary>

### The Problem
Olist suffers from a severe **"One-Timer" problem**, with a **Repeat Purchase Rate (RPR) of only 3.12%**. Despite being a general marketplace, 97% of customers never return, suggesting that the "Customer Experience Gap"—the friction between the promise made at checkout and the actual delivery reality—is killing long-term loyalty.

### The Insight
By merging logistics performance with user behavioral data, the analysis revealed a **"Trust Tax"** in urban hubs. In São Paulo (the largest market), the system over-estimates delivery by **10.2 days**. 
* **Competitive Friction:** In cities where competitors like Amazon offer 1-2 day delivery, Olist’s 12-day "Safe Estimate" makes the platform look uncompetitive.
* **The Utility Trap:** Higher retention in remote states like Acre (~5.2%) suggests Olist is currently a "Necessary Utility" for niche access, but a "Disposable Commodity" in cities where trust and speed are the primary drivers.
* **The Price Barrier:** Repeat buyers consistently spend **~16% less** ($102 vs $121) than one-timers, showing that high-ticket purchases are "one-and-done" events due to delivery anxiety.

### The Recommendation
Pivot from a "Growth at all costs" acquisition model to a **"Trust-First" Retention Strategy**:
* **Dynamic Urban Buffers:** Aggressively reduce ETA padding in high-density urban hubs (SP/RJ) to lower the perception barrier at checkout.
* **Category-Specific Nurturing:** Incentivize the "Habit-Forming" categories (Health, Beauty, Sports) that showed overlap between loyalists and one-timers, but with lower-friction shipping promises.
* **Proactive Recovery:** Use the "System Gap" data to trigger automated loyalty rewards. If the tech knows a delivery was significantly padded or delayed, offer a "Trust Discount" before the customer churns.
</details>


## 🔍 Focus Areas

<details>
<summary>Retail & Category Analytics</summary>
Category performance, pricing and promotion effects, assortment and margin trade-offs.
</details>

<details>
<summary>Supply Chain & Operations Analytics</summary>
Demand forecasting, inventory and replenishment logic, returns behavior, fulfillment metrics.
</details>

<details>
<summary>Marketplace & Fulfillment Systems</summary>
Operational bottlenecks, customer friction, seller and platform trade-offs.
</details>

<details>
<summary>Product & Systems Thinking</summary>
How metrics shape behavior, second-order effects, and where product or process changes create leverage.
</details>

<details>
<summary>Decision Journals & Reflections</summary>
Short notes on why certain metrics matter, what assumptions break in reality, and what I’d redesign in a system or product.
</details>

---

## 💡 Why this repository exists

I’m interested in roles at the intersection of **analytics, operations, and product**, where data is used not just to explain outcomes, but to guide decisions under real constraints. 

This repository serves as:
1.  **A personal learning archive**
2.  **A thinking surface** for complex systems
3.  **A way to articulate** how analytics connects to business and product impact

> **How this repository evolves:** This is not a finished curriculum. It grows through small, focused explorations, revisions, and learnings — similar to how real-world understanding develops on the job.
