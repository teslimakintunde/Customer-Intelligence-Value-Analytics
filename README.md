# Customer Intelligence

This project analyses **customer demographics, behavioural segmentation, customer lifetime value, relationship health, revenue concentration, and customer treatment strategy** across a **2019–2025 customer dataset** using **MySQL and Power BI**.

The objective was to move beyond basic customer profiling and determine **who the customers are, how they behave, which relationships generate the most value, where customer health is deteriorating, and how customer value should influence retention and commercial treatment.**

**Tools:** MySQL · Power BI

---

## Customer Intelligence Dashboard

### Page 1 — Customer Demographics & Segmentation

**Business Question**

> **Who are our customers, where are they concentrated, and which customer groups matter most to the business?**

**Key Insight**

The business has built a broad customer base of **10,000 customers**, with customer concentration strongest in the **West (3,415)** and **North (3,082)** regions, together representing approximately **65% of the customer base**.

The customer population is primarily working-age, with the **35–44 segment representing 28.3%** of customers and approximately **72% of customers falling between ages 25 and 54**.

Customer acquisition also accelerated significantly in the most recent cohorts. Annual acquisitions increased from approximately **1,200–1,260 customers between 2019 and 2023** to **1,947 in 2024 and 1,903 in 2025**.

However, customer volume does not directly translate into commercial value. **Wholesale customers generated ₦184.22M**, approximately **43.2% of total revenue**, despite customer counts being distributed across multiple segments.

**Business Implication**

Customer growth should be evaluated through both **customer acquisition and economic contribution**. Geographic concentration, customer segment, acquisition source, and revenue contribution should be considered together when developing customer growth and retention strategies.

---

### Page 2 — RFM Customer Segmentation

**Business Question**

> **Which customers are highly engaged, which relationships are weakening, and where are the greatest retention opportunities?**

**Key Insight**

The RFM analysis identifies a strong high-engagement customer core, with **1,823 Champions representing 18.23% of the customer base**. Champions demonstrate an average purchase frequency of **16.28** and average monetary value of approximately **₦69,737**, with average recency of only **13 days**.

At the same time, **Hibernating and Lost customers account for 30.71% of the customer base**, representing a substantial pool of relationships that are no longer actively generating value.

The portfolio also contains a significant conversion opportunity. **Potential Loyalists, Promising, and New Customers represent approximately 25.9% of the customer base**, providing a population that can potentially be developed into stronger long-term relationships.

Importantly, customer risk is not purely a volume issue. The **At Risk segment represents only 1.75% of customers**, but its average monetary value is approximately **₦31,372**. The small **Can't Lose Them** segment contains only 8 customers but has an average monetary value of approximately **₦62,322**.

**Business Implication**

Customer retention should be differentiated by **relationship value and behavioural state**. High-value customers showing signs of inactivity require protection, while Potential Loyalists and Promising customers require structured engagement designed to increase frequency and long-term value.

---

### Page 3 — Customer Lifetime Value & Health

**Business Question**

> **How much are customer relationships worth, how healthy are they, and where is future customer value at risk?**

**Key Insight**

The customer portfolio has an average realised CLV of **₦27,314**, compared with an average projected CLV of **₦64,285**. This indicates substantial expected future value across the customer base, but the distribution is highly concentrated: **95.12% of customers have CLV below ₦100K**, while a very small number of customers generate exceptionally high lifetime value.

The value concentration becomes more pronounced across revenue tiers. **VIP customers have an average realised CLV of ₦132,003 and projected CLV of ₦272,427**, substantially above the overall customer average.

Customer health is mixed, with an average Health Score of approximately **0.588**, while only **38.91% of customers are classified as active**. The combination of active customers, dormant relationships, and high-value customers at risk demonstrates why customer value cannot be assessed through revenue alone.

Between 2024 and 2025, realised customer value increased modestly while active customer share also improved. However, projected CLV and CLV:CAC declined slightly, indicating **mixed signals between realised engagement and forward-looking customer economics**.

**Business Implication**

Customer strategy should distinguish between **realised value, projected value, and relationship health**. High-value customers should be monitored for early deterioration, while lower-value customers with improving engagement should be evaluated for their potential to become future high-value relationships.

---

### Page 4 — Customer Revenue Tiers & Pricing Policy

**Business Question**

> **How should customer treatment and incentives differ according to customer value and relationship behaviour?**

**Key Insight**

Customer revenue is highly concentrated among a relatively small portion of the customer base. **VIP customers represent only 9.61% of customers but generate ₦199.35M, approximately 46.8% of total revenue.**

When High Value customers are combined with VIP customers, they represent only **23.86% of customers but contribute approximately 69.9% of total revenue**.

This concentration creates two distinct commercial priorities. The first is protecting high-value relationships: **VIP and High Value customers who are Champions or Loyal customers represent an economically important customer core**. The second is developing future value: Growth and Standard customers containing Potential Loyalists and Promising customers provide opportunities for structured migration into higher-value tiers.

The RFM and revenue-tier views also reveal that **customer behaviour and customer economics are different dimensions**. A customer may have high historical value but be Hibernating, while another may have lower current value but demonstrate strong recent engagement.

**Business Implication**

Customer treatment should be based on the intersection of **economic value and relationship behaviour**, rather than revenue tier alone. Retention, reactivation, development, and incentive strategies should therefore be differentiated across customer groups.

---

## Key Business Findings

* **Customer acquisition accelerated:** annual customer acquisition increased from approximately **1,200–1,260 customers during 2019–2023** to **1,947 in 2024 and 1,903 in 2025**.
* **Customer concentration is geographically significant:** the **West and North account for approximately 65% of the customer base**, with 3,415 and 3,082 customers respectively.
* **The customer base is predominantly working-age:** approximately **72% of customers are between 25 and 54 years old**, with the 35–44 segment representing **28.3%**.
* **Revenue concentration differs from customer concentration:** Wholesale generated **₦184.22M**, representing approximately **43.2% of total revenue**.
* **Champions represent a significant high-engagement group:** **1,823 customers (18.23%)** are classified as Champions, with average frequency of **16.28 purchases** and average monetary value of approximately **₦69,737**.
* **Customer inactivity is material:** **Hibernating and Lost customers represent 30.71% of the customer base**, creating a substantial reactivation and retention opportunity.
* **A meaningful development pool exists:** Potential Loyalists, Promising, and New Customers represent approximately **25.9% of customers**.
* **Risk is economically concentrated:** At Risk customers represent only **1.75% of the base**, but their average monetary value is approximately **₦31,372**.
* **Customer value is highly skewed:** **95.12% of customers have CLV below ₦100K**, while a small number of customers generate disproportionately high lifetime value.
* **VIP customers are commercially critical:** VIPs represent only **9.61% of customers but approximately 46.8% of total revenue**.
* **High Value + VIP customers drive the majority of revenue:** approximately **23.9% of customers generate 69.9% of total revenue**.
* **VIP customers have substantially higher lifetime value:** average realised CLV is approximately **₦132K**, compared with **₦27.3K across the overall customer base**.
* **Customer health is mixed:** only **38.91% of customers are classified as active**, while the average Health Score is approximately **0.588**.
* **2025 presents mixed customer-economic signals:** realised value and active customer share improved modestly, while projected CLV and CLV:CAC declined slightly.
* **Customer value and customer behaviour should be analysed together:** RFM identifies relationship status, while revenue/CLV tiers identify economic value; their intersection provides a more actionable customer strategy.

---

## Strategic Recommendations

* Prioritise **VIP and High Value customers** for proactive retention and relationship monitoring because a relatively small customer population contributes a disproportionate share of revenue.
* Build targeted **reactivation programmes for Hibernating and Lost customers**, prioritising customers with historically high monetary value or strong prior purchase frequency.
* Develop **Potential Loyalists and Promising customers** through personalised engagement, cross-sell, repeat-purchase, and loyalty initiatives.
* Monitor **At Risk and Can't Lose Them customers** closely because their small population size can conceal meaningful economic exposure.
* Use **RFM behaviour and customer economic value together** when designing customer treatment rather than relying on revenue tiers alone.
* Investigate the transition of customers between **Entry → Growth → High Value → VIP** to identify the behavioural and commercial factors associated with value progression.
* Focus regional customer strategies on the **West and North**, which collectively represent approximately 65% of the customer base, while investigating opportunities in lower-volume regions.
* Evaluate customer acquisition channels using **customer quality and downstream value**, rather than acquisition volume alone.
* Use customer Health Score and RFM movement as **early-warning indicators** for deteriorating customer relationships.
* Validate pricing and discount decisions against **retention, revenue, and margin outcomes** before applying differentiated incentives broadly.
* Replace aggregated sums of recommended discount percentages with **average or median recommended discount levels** by customer tier to make incentive analysis statistically meaningful.
* Add **profit/margin and discount-cost metrics** to the pricing-policy view before making claims about maximising margin.

---

## Data & Analytics Approach

**MySQL**

* Customer data cleaning and transformation
* Customer demographic profiling
* Customer segmentation analysis
* Acquisition cohort analysis
* Revenue and customer-value aggregation
* RFM segmentation
* Recency, frequency, and monetary analysis
* Customer lifetime value analysis
* Customer health analysis
* CLV:CAC analysis
* Revenue-tier classification
* Customer value concentration analysis

**Power BI**

* Interactive customer intelligence dashboard
* Executive customer KPIs
* Demographic and geographic segmentation
* Acquisition trend analysis
* RFM customer segmentation
* Customer lifetime value analysis
* Customer health monitoring
* Revenue-tier analysis
* RFM × revenue-tier analysis
* Customer value concentration analysis
* Year-over-year customer analysis
* Customer treatment and pricing-policy analysis

---

## Business Impact

The analysis moves customer reporting from:

**"Who are our customers and how much have they purchased?"**

to:

**"Which customers create the most value, how healthy are those relationships, where is customer value at risk, and how should customer treatment differ according to economic and behavioural value?"**

The resulting framework provides a **data-driven foundation for customer retention, reactivation, customer development, value-based segmentation, loyalty strategy, and differentiated commercial treatment.**

It also establishes a clear progression from:

**Customer Base → Customer Behaviour → Customer Economics → Commercial Action**

allowing management to move from understanding **who the customers are**, to identifying **how they behave**, quantifying **what their relationships are worth**, and determining **where retention and growth efforts should be focused**.

---

## Tech Stack

| Tool         | Role                                              |
|--------------|---------------------------------------------------|
| **MySQL**    | Data cleaning, transformation, RFM, CLV & modelling |
| **Power BI** | Interactive dashboard, visualisation & executive reporting |
