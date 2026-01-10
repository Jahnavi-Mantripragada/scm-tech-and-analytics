
# Supply Chain, Retail & Product Analytics — A Decision-Focused Lab

This repository is a living analytics and thinking lab where I explore how data, constraints, and systems interact to shape decisions in retail, supply chain, and marketplace environments.

Rather than treating analytics as reporting, this work focuses on how insights influence operational choices, product behavior, and system design — particularly in areas like demand uncertainty, inventory trade-offs, returns, fulfillment, and pricing.

The projects and notes here combine:
* Supply chain and retail fundamentals
* Data analysis, modeling, and simulation
* A product and systems-thinking lens focused on real-world constraints

This repository is built incrementally through experiments, analyses, and decision journals, reflecting how understanding deepens over time in real operating environments.

## Projects

### Project - 1 - Olist Logistics — From "Dumb Multipliers" to Dynamic Visibility

#### The Problem
Olist relied on a **static 2× multiplier** for delivery ETAs to mask high logistics variance.  
In major hubs like **São Paulo**, this meant promising a **12-day delivery** for a journey that physically takes **~5 days**, significantly hurting **checkout conversion rates**.

#### The Insight
Data analysis revealed that the **“chaos” (standard deviation)** in the Brazilian postal system is roughly equal to the **average transit time** itself.  
A purely mathematical fix—simply shortening the ETA—would push **late deliveries to ~15–20%**, creating a customer-support nightmare.

#### The Recommendation
Shift the product strategy from **accuracy** (guessing a single “safe” date) to **transparency** (showing the journey).

By implementing **real-time milestone tracking**, Olist can:
- Offer more **aggressive early estimates**
- Use **information**—not time padding—to buffer chaos when delays actually occur


## Focus Areas

* ### Retail & Category Analytics
 Category performance, pricing and promotion effects, assortment and margin trade-offs.

* ### Supply Chain & Operations Analytics
 Demand forecasting, inventory and replenishment logic, returns behavior, fulfillment metrics.

* ### Marketplace & Fulfillment Systems
Operational bottlenecks, customer friction, seller and platform trade-offs.

* ### Product & Systems Thinking
How metrics shape behavior, second-order effects, and where product or process changes create leverage.

* ### Decision Journals & Reflections
Short notes on why certain metrics matter, what assumptions break in reality, and what I’d redesign in a system or product.

## Why this repository exists

I’m interested in roles at the intersection of analytics, operations, and product, where data is used not just to explain outcomes, but to guide decisions under real constraints.

This repository serves as:

* a personal learning archive

* a thinking surface for complex systems

* and a way to articulate how analytics connects to business and product impact

## How this repository evolves

This is not a finished curriculum.
It grows through small, focused explorations, revisions, and learnings — similar to how real-world understanding develops on the job.
