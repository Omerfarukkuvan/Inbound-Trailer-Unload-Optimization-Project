# Workflow Metrics – Inbound Trailer Tracking

This table summarizes the simulated outcomes of the implemented workflow.

| Metric                                         |   Value           |      Notes                                   
|------------------------------------------------|-------------------|----------------------------------------------
| Total Appointments	                           |  59	             |  Total number of trailer appointments analyzed.
| Resolved Count	                               |  59	             |  All appointments have been resolved.
| Open Count	                                   |  0	               |  No open cases remaining.
| Average Resolution Time (Days)	               | 34.54	           |  Average number of days taken to resolve each case.
| Total Recovered Value                          | $29,140,466.07    |	Total recovered amount from all resolved trailers.
| Average Recovered Value                        | $493,906.20	     | Average recovered value per resolved trailer.
| Total Unloaded Trailer	                       | 87	               | Total number of trailers successfully unloaded.
| Unloaded Trailer Rate (%)	                     | 147.46	           | High rate may indicate multiple unloads per appointment or data overlap.


# 📦 Inbound Trailer Results Summary

This report summarizes the key findings from the dataset *“Unloaded Trailer & Recovered Value Data.xlsx”* — analyzing inbound trailer unloading performance, resolution time, and recovered value trends.

---

## 🧾 1. Delivery appts daily
- Contains detailed records for each delivery appointment.
- Columns include appointment number, creation date, resolution date, delay type, recovered value, and unloaded trailer count.
- *All appointments are marked as "Resolved."*
- *Delay Types:*
  - Trailer Defect
  - Appointment Delayed
  - Past Scheduled Date
- Recovered values range from *$60K to over $1.2M*, depending on delay type and issue severity.

---

## 📅 2. Daily Unloaded Trailer & Receovered Value
- Shows *daily totals* for unloaded trailers and recovered value.
- Covers data from *September 1–11, 2025*.
- Example daily results:
  - *Sep 1:* 1 trailer unloaded → $145,560 recovered  
  - *Sep 4:* 8 trailers unloaded → $2.8M recovered (peak day)
- Indicates fluctuating daily trailer counts and recovered values, reflecting operational variation.

![Workflow Diagram](https://github.com/Omerfarukkuvan/Inbound-Trailer-Unload-Optimization-Project/blob/main/Graphics/Unloaded%20Trailer%20%26%20Recovered%20Value.png)

---

## 📈 3. Weekly performance
- Summarizes weekly totals of *recovered value* and *unloaded trailers*.
- *Weeks Covered:* September 1–26, 2025
- Breakdown:
  | Week | Recovered Value | Unloaded Trailers |
  |------|-----------------|------------------|
  | Sep 1–7  | $8,659,184.60 | 21 |
  | Sep 8–14 | $7,375,468.68 | 20 |
  | Sep 15–21 | $6,146,875.27 | 23 |
  | Sep 22–26 | $6,958,937.52 | 23 |
- *Total Recovered Value:* $29,140,466.07  
- *Total Unloaded Trailers:* 87  
- Shows consistent performance with slightly lower recovery after Week 1.

![Workflow Diagram](https://github.com/Omerfarukkuvan/Inbound-Trailer-Unload-Optimization-Project/blob/main/Graphics/Weekly%20Operational%20and%20Financial%20Performance.png)

---

## ⚙️ 4. Recovered Value by Delay Type
- Breaks down recovered amounts *by delay reason* on a daily basis.
- *Delay Categories:*
  - Appointment Delayed → *$14.03M*
  - Past Scheduled Date → *$4.68M*
  - Trailer Defect → *$10.43M*
- Appointment-related delays caused the *highest total recovery value*.

![Workflow Diagram](https://github.com/Omerfarukkuvan/Inbound-Trailer-Unload-Optimization-Project/blob/main/Graphics/Recovered%20Value%20by%20Delay%20Type.png)

---

## ⏱️ 5. Average of Resolution Date
- Shows *average resolution time* (in days) per delay type:
  | Delay Type | Avg. Resolution Time (Days) | Total Recovered Value |
  |-------------|-----------------------------|------------------------|
  | Appointment Delayed | 34.08 | $14.03M |
  | Past Scheduled Date | 36.94 | $4.68M |
  | Trailer Defect | 36.23 | $10.43M |
- *Overall Average Resolution Time:* 35.38 days  
- Suggests all delay categories require ~5 weeks to close on average.

![Workflow Diagram](https://github.com/Omerfarukkuvan/Inbound-Trailer-Unload-Optimization-Project/blob/main/Graphics/Average%20of%20Resolution%20Date.png)
![Workflow Diagram](https://github.com/Omerfarukkuvan/Inbound-Trailer-Unload-Optimization-Project/blob/main/Graphics/Analysis%20on%20Average%20Resolution%20Days%20by%20Delay%20Type.png)

---

## 📊 6. KPI Summary
| KPI Name | Value |
|-----------|--------|
| Total Appointments | 59 |
| Resolved Count | 59 |
| Open Count | 0 |
| Average Resolution Time (Days) | 34.54 |
| Total Recovered Value | $29,140,466.07 |
| Average Recovered Value per Case | $493,906 |
| Total Unloaded Trailers | 87 |
| Unloaded Trailer Rate (%) | 147.46% |

- Indicates *all appointments were resolved* with strong recovery metrics.

---


## ✅ Overall Insights
- *59 inbound trailer appointments* fully resolved.  
- *87 trailers unloaded, generating *$29.14 million** in total recovered value.  
- *Average resolution time:* ~35 days.  
- *Top issue type:* Appointment Delayed (highest recovery impact).  
- *Strong weekly consistency* with the first week being most profitable.

---

### 📁 Folder Purpose
This folder (Inbound Trailer Results) documents the performance outcomes of the *Inbound Trailer Unloading and Recovery Analysis*, serving as a reference for:
- Weekly KPI tracking
- Delay type impact analysis
- Process improvement discussions
- Audit or report submissions

- As a result of all these efforts, another key objective of this project is to collect root cause data after the delays are resolved and to work on proactive solutions to prevent such issues before they occur.
The project will continue to evolve internally to minimize system-related problems and improve overall efficiency.
---
