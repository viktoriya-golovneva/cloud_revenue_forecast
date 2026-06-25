# Business Summary and Action Notes
## NimbusCompute Revenue and Cash Forecast — June to August 2026

**Forecast cutoff:** June 6, 2026  
**Forecast horizon:** June, July, and August 2026  
**Audience:** Finance, Sales, Legal, Accounts Receivable, Account Management, and Leadership

---

# 1. Executive Summary

NimbusCompute has grown from approximately **$472K of monthly consumption revenue in January 2024** to approximately **$1.466M in May 2026**.

The forecast indicates continued growth in the Base scenario, but a large share of the expected increase depends on a small number of CRM opportunities, especially Vertex Labs.

## Base forecast

- **Consumption revenue:** approximately **$6.349M** across June–August.
- **Cash collections:** approximately **$12.148M** across June–August.
- **Core cash excluding Vertex Labs:** approximately **$5.938M**.
- **Conditional Vertex Labs prepayment:** approximately **$6.211M**.

The most important conclusion is that the Base cash forecast is highly concentrated.

Approximately half of the Base cash forecast depends on one CRM record and its assumed annual-prepayment structure.

---

# 2. Final Forecast Results

All figures below are in **thousands of US dollars**.

## 2.1 Consumption revenue forecast

| Month | Downside | Base | Upside |
|---|---:|---:|---:|
| June 2026 | 1,581 | 1,639 | 1,654 |
| July 2026 | 1,552 | 2,301 | 2,400 |
| August 2026 | 1,524 | 2,409 | 2,532 |
| **June–August total** | **4,657** | **6,349** | **6,586** |

### Interpretation

The Base scenario implies average monthly consumption revenue of approximately:

```text
$6.349M / 3 ≈ $2.116M per month
```

This is approximately **44% above the May 2026 run rate of $1.466M per month**.

The main reason for the increase is not organic growth alone.

The July and August step-up is mainly driven by Vertex Labs:

```text
Expected monthly consumption: approximately $690K
Expected start: July 2026
```

Without Vertex, forecast consumption would remain much closer to the Downside trajectory.

---

## 2.2 Cash collections forecast

| Month | Downside | Base | Upside |
|---|---:|---:|---:|
| June 2026 | 2,941 | 2,985 | 2,985 |
| July 2026 | 1,420 | 7,703 | 8,394 |
| August 2026 | 1,164 | 1,461 | 1,471 |
| **June–August total** | **5,526** | **12,148** | **12,851** |

### Base cash decomposition

| Component | Approximate Base cash |
|---|---:|
| Core cash excluding Vertex | 5,938 |
| Conditional Vertex prepayment | 6,211 |
| **Base total** | **12,148** |

### Interpretation

July is the most sensitive month.

The Base forecast includes approximately **$6.21M of Vertex prepayment in July**.

Without Vertex, July cash would be approximately:

```text
$1.42M
```

rather than:

```text
$7.70M
```

This means the current July liquidity view should not be treated as fully committed until the Vertex structure is confirmed.

---

# 3. Main Business Drivers

## 3.1 Organic customer base

The organic forecast is anchored to May 2026, the latest complete actual month.

Scenario assumptions:

| Scenario | Organic monthly growth |
|---|---:|
| Downside | −2% |
| Base | +2% |
| Upside | +3% |

Organic growth creates a relatively smooth revenue path.

It does not explain the large July increase by itself.

---

## 3.2 Vertex Labs

The model treats:

```text
OPP-1037
```

as the umbrella Vertex opportunity.

The following opportunities are excluded as possible duplicates:

```text
OPP-1035
OPP-1036
```

The model assumes:

- approximately **$690K monthly consumption**;
- July start;
- 24-month term;
- approximately **$13.8M committed spend**;
- annual prepayment;
- 90% probability in the Base scenario.

This produces:

```text
13.8M × 12 / 24 = 6.9M annualized first-year prepayment
```

and:

```text
6.9M × 90% ≈ 6.21M Base cash
```

This assumption must be validated before the forecast is used for liquidity planning.

---

## 3.3 OPP-1039

The model assumes OPP-1039 is an annual-prepay deal.

Expected June cash contribution:

```text
approximately $1.8M
```

If the actual payment structure is monthly rather than annual prepayment:

```text
June Base cash falls from approximately $2.985M
to approximately $1.185M
```

The opportunity is linked to an unmatched CRM account and may correspond to:

```text
CON-1888 / CUST-0058
```

This mapping requires confirmation.

---

## 3.4 OPP-1038

The model treats OPP-1038 as a quarterly-prepay opportunity.

Expected Base cash contribution in August:

```text
approximately $210K
```

This is based on:

```text
approximately $300K quarterly prepayment × 70% probability
```

---

## 3.5 Existing accounts receivable

Accounts receivable is reconstructed as of June 6, rather than using the final invoice status in the source extract.

This is important because invoices paid after June 6 were still open at forecast time.

Expected near-term AR collections are approximately:

| Month | Expected collection |
|---|---:|
| June | 1,097K |
| July | 1,188K |
| August | 284K |

These collections mainly relate to April and May service cohorts.

---

## 3.6 Overdue receivables

The overdue AR balance is approximately:

```text
$1.442M
```

Approximately 70% of this balance is more than 180 days overdue.

Base recovery assumptions:

| Aging bucket | Recovery assumption |
|---|---:|
| 1–30 days | 80% |
| 31–90 days | 50% |
| 91–180 days | 20% |
| 180+ days | 5% |

Expected Base recovery over June–August:

```text
approximately $263K
```

or approximately:

```text
$88K per month
```

The recovery rates are assumptions and must be validated with the AR team.

---

## 3.7 Future usage collections

Future monthly-arrears consumption is converted into cash using historical service-to-payment lags.

Observed lag weights used in the model:

| Collection timing | Historical share |
|---|---:|
| One month after service | approximately 16.2% |
| Two months after service | approximately 55.8% |

This explains why strong summer consumption does not fully convert into summer cash.

A substantial portion of June–August consumption will be collected after the forecast horizon.

---

# 4. Decisions Required by Business Team

## 4.1 Sales — Vertex Labs

### Required decision

Confirm whether:

1. `OPP-1037` is the full umbrella opportunity;
2. `OPP-1035` and `OPP-1036` are separate components;
3. or all three records represent distinct incremental deals.

### Why it matters

The current model excludes `OPP-1035` and `OPP-1036` and includes only `OPP-1037`.

The records do not reconcile perfectly:

```text
410K + 230K = 640K
```

while:

```text
OPP-1037 = 690K
```

The difference means the umbrella assumption is plausible but not proven.

### Forecast impact

Potential impact:

- approximately **$690K per month of consumption**;
- approximately **$6.21M of July Base cash**.

### Recommended owner

```text
Sales / Deal Desk
```

### Recommended timing

```text
Before the forecast is used for June-end liquidity planning
```

---

## 4.2 Finance and Legal — OPP-1039

### Required decision

Confirm:

- annual prepay versus monthly billing;
- committed amount;
- contract start date;
- whether `OPP-1039` maps to `CON-1888 / CUST-0058`.

### Forecast impact

If the deal is monthly rather than annual prepay:

```text
June Base cash decreases by approximately $1.8M
```

### Recommended owner

```text
Finance / Legal / Deal Desk
```

---

## 4.3 Accounts Receivable — Overdue balance

### Required decision

For each large overdue invoice, confirm:

- active collection process;
- dispute;
- payment plan;
- write-off candidate;
- uncollectible status.

### Forecast impact

The model assumes approximately **$263K recovery** during the horizon.

Without account-level validation, this should be treated as scenario-based rather than committed cash.

### Recommended owner

```text
Accounts Receivable
```

---

## 4.4 Account Management — Churned customers with May usage

The following customers are marked as churned but still have May usage:

```text
CUST-0011
CUST-0012
CUST-0016
CUST-0037
```

Possible explanations:

- status update lag;
- final offboarding consumption;
- billing-system status error.

They are excluded from the organic forecast because their billing status is not active.

If they are still active, the current organic baseline is understated.

### Recommended owner

```text
Account Management / Customer Success
```

---

## 4.5 Sales — High network-egress concentration

Network egress represents a material share of revenue.

Two customers are major volume outliers:

```text
CUST-0018
CUST-0079
```

The current forecast assumes that their recent usage continues.

Sales should confirm whether this activity is supported by:

- contractual minimum volume;
- committed usage;
- stable workload;
- or pay-as-you-go activity that may be volatile.

### Recommended owner

```text
Sales / Account Management
```

---

## 4.6 Finance — April billing-system change

A billing-system source change occurred in April 2026.

The analysis identified invoice anomalies around this period.

The organic forecast itself is anchored to May, not to a March–May average.

However, April and May invoices are important for the existing-AR cash forecast.

Finance should confirm that April invoice data passed reconciliation and that no duplicate or missing invoices remain.

### Recommended owner

```text
Finance / Billing Operations
```

---

# 5. Risk Register

| Risk | Probability | Financial impact | Current treatment |
|---|---|---|---|
| Vertex opportunities are duplicated or misclassified | High | Very high | Keep one umbrella record; show Vertex cash separately |
| Vertex annual prepayment does not occur in July | Medium | Very high | Conditional component in Base and Upside |
| OPP-1039 is monthly rather than annual prepay | Medium | High | Open Finance/Legal validation |
| Overdue AR is less collectible than assumed | High | Medium | Aging-based recovery and lower Downside rates |
| Quarterly billing cycles are phased differently | Medium | Low to medium | Approximate with historical lag |
| Contract statuses are stale | Medium | Low to medium | Documented limitation |
| Churn statuses are delayed | Medium | Low to medium | Excluded from active organic base |
| Egress usage declines for key customers | Medium | Medium | Assumed to continue at recent level |
| Future start dates slip | Medium | High | Downside excludes non-Closed Won pipeline |

---

# 6. Recommended Planning View

Leadership should use two cash views in parallel.

## 6.1 Core operating cash

```text
Approximately $5.94M in the Base scenario
excluding Vertex
```

This includes:

- existing AR;
- overdue recovery assumptions;
- future arrears collections;
- other pipeline prepayments.

## 6.2 Conditional cash

```text
Approximately $6.21M from Vertex
```

This should remain a separate line until:

- deal structure is confirmed;
- annual prepayment is confirmed;
- expected collection month is confirmed.

This avoids overstating available liquidity.

---

# 7. Recommended Actions

## Immediate

1. Confirm Vertex opportunity structure.
2. Confirm Vertex payment structure and expected payment date.
3. Confirm OPP-1039 annual prepayment and CRM-to-contract mapping.
4. Review the largest overdue accounts.
5. Validate churned customers with recent usage.

## Before the next forecast refresh

1. Add customer-level billing-cycle phase.
2. Add confirmed invoice dates for future prepayments.
3. Add account-level AR recovery status.
4. Reconcile contract status against contract end dates.
5. Separate committed and non-committed egress usage.
6. Refresh pipeline probabilities and start dates.

---

# 8. Final Business Takeaways

1. **Consumption is expected to grow, but the Base step-up is highly pipeline-dependent.**
2. **July cash is not a normal operating month; it is dominated by one assumed annual prepayment.**
3. **Core cash is materially lower than the headline Base total.**
4. **Existing AR supports June and July collections, while summer usage converts into cash with a lag.**
5. **The forecast should be updated immediately after Vertex and OPP-1039 are validated.**
6. **The main forecasting risk is business-data quality, not the mathematical model itself.**

---

# 9. One-Slide Summary

## Base case

```text
Consumption revenue, June–August: $6.35M
Cash collections, June–August: $12.15M
Core cash excluding Vertex: $5.94M
Conditional Vertex cash: $6.21M
```

## Main dependency

```text
Vertex Labs:
$690K monthly consumption
$6.21M Base prepayment
```

## Main decisions

```text
Sales: confirm Vertex deal structure
Finance/Legal: confirm OPP-1039 annual prepayment
AR: validate $1.44M overdue balance
Account Management: validate churned customers with May usage
```
