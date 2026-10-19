# FORENSIC AUDIT & ECONOMETRIC EVIDENCE COMPENDIUM

Detailed empirical breakdown from the **33-Month Econometric Study** and **Forensic Fuel Cost Investigation Report** (Folder `xxxxxxx`) supporting ERC Resolution 2.

---

## 1. Forensic Audit Disallowance Precedents ($15.657M USD Total)

Forensic examination of power plant billings (FGPC Santa Rita 1,000 MW, FGP San Lorenzo 500 MW, EERI Batangas LNG 1,200 MW) from October 2025 to June 2026 uncovered **$15,657,071.35 USD (PhP 963,239,245.99 PHP)** in improper pass-through charges:

```
Total Disallowance Breakdown:
├── Affiliated Terminal Capacity Fee Markup Overcharges: $8,211,450.00 (52.4%)
│   └── Billed at $2.93/MMBtu vs. Regional FSRU Benchmark of $1.50/MMBtu ($1.43/MMBtu excess)
├── Unsubstantiated / Inflated Boil-Off Gas (BOG) Losses: $4,118,321.35 (26.3%)
│   └── Billed at 0.30% - 0.45%/day vs. SIGTTO/DNV Maximum Allowable Cap of 0.15%/day
└── Unauthorized Local Business Taxes (LBT) & Real Property Taxes: $3,327,300.00 (21.3%)
    └── Billed as direct fuel pass-through in violation of Section 43 of EPIRA
```

### Action for Resolution 2:
- Set hard logistics cap at **$1.50/MMBtu** for terminal fees.
- Lock BOG evaporative allowance at **0.10%/day** (max allowable **0.15%/day**).
- Mandate immediate deduction of disallowances from subsequent monthly MMSA settlement ledgers.

---

## 2. 33-Month Econometric Regression (Jan 2024 – Sep 2026)

Empirical multi-marker regression on MERALCO contracted gas generation tariffs ($Y = \text{PhP/kWh}$) against public global energy markers:

$$Y = 2.145 + 0.382 \times (\text{Platts JKM}) + 0.041 \times (\text{Brent}) + 0.058 \times (\text{USD/PHP FX})$$

- **Platts JKM Correlation:** $R = 0.884$ ($R^2 = 0.781$) — Primary driver of marginal imported LNG costs.
- **Brent Crude Parity Correlation:** $R = 0.762$ — Governs long-term SPA base indexing.
- **European TTF Correlation:** $R = 0.695$ — Indirect arbitrage influence during winter supply spikes.
- **US Henry Hub Correlation:** $R = 0.412$ — Weak direct correlation due to liquefaction + shipping add-ons.

---

## 3. Malampaya Transition & Consumer Rate Impact

| Year | Indigenous Gas Mix (%) | Imported LNG Mix (%) | Estimated Blended Fuel Cost (PhP/kWh) | Consumer Surcharge Impact vs Baseline (PhP/kWh) |
| :--- | :--- | :--- | :--- | :--- |
| **2026** | **60.0%** | **40.0%** | **PhP 4.4230 / kWh** | Base Reference |
| **2028** | **40.0%** | **60.0%** | **PhP 4.8452 / kWh** | + PhP 0.4222 / kWh |
| **2030** | **20.0%** | **80.0%** | **PhP 5.2673 / kWh** | + PhP 0.8443 / kWh |
| **2034** | **0.0%** | **100.0%** | **PhP 5.6894 / kWh** | + PhP 1.2664 / kWh |

*Note: LNG portion carries 12% VAT, whereas indigenous Malampaya gas is VAT-exempt under RA 12120 / BIR RR 002-2026.*
