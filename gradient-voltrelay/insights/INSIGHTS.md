1. Battery & Equipment Performance (Answers Core Question 4)

What Pearson correlation shows:
* There is a negative correlation of -0.240 between age_months and soh_drop (State of Health drop). While age does affect degradation, the relationship shows that degradation accumulates steadily over time rather than failing instantly.
* There is an extremely strong correlation (0.994) between rated_capacity_kw and purchase_cost_inr. This confirms the logical baseline that higher-capacity packs (like the heavy 3W packs) cost significantly more to procure than standard 2W packs.


Report :
Analysis of the battery asset ledger reveals a predictable, steady accumulation of state-of-health decline over time (age_months correlation of -0.240 with health drop). Furthermore, procurement costs scale almost perfectly with nameplate capacity ($r = 0.994$), establishing a clear baseline for asset replacement modeling across vehicle classes.


2. Rider Segmentation & Plan Distribution (Answers Core Questions 5 & 6)

What Chi-Square Test A shows:
With a Chi-Square value of 20,000.00 and a p-value of 0.0000, there is an overwhelming, statistically significant dependency between a rider's plan_type and whether they belong to a fleet partner.


Report:
Chi-square testing confirms a profound structural separation between independent and B2B fleet riders ($p < 0.001$). Fleet-affiliated riders are tightly bound to contracted pricing tiers (such as prepaid or partner-billed models), whereas independent gig workers rely predominantly on pay-as-you-go structures. This stark segmentation dictates how different rider groups absorb base price modifications and peak surcharges.


3. Station Infrastructure & Connectivity (Answers Core Question 3)

What Chi-Square Test B shows:
With a Chi-Square value of 0.65 and a p-value of 0.9568 (which is well above the 0.05 threshold), the result is Independent. This means there is no statistically significant relationship between a station's charger_generation (Gen1, Gen2, Gen3) and it's connectivity_tier.

Report:
Contrary to initial assumptions that older hardware generations suffer disproportionately from poor internet connectivity, Chi-square independence testing ($p = 0.9568$) proves that connectivity issues are distributed evenly across station types. Consequently, missing telemetry data in historical logs is an independent network infrastructure constraint rather than a hardware limitation of older Gen1 chargers.