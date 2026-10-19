# DOE TERMS OF REFERENCE & GAS AUCTION GUIDELINES: MASTER SUMMARY

> [!IMPORTANT]
> **CRITICAL DIRECTIVE FOR CLAUDE & AI AGENTS:**
> **DO NOT SCAN, OCR, OR PARSE THE 3 PDF FILES IN THIS FOLDER (`Terms of Reference/`).**
> All regulatory text, auction parameters, lot tranches, heat rate ceilings, fuel priority hierarchies, capacity factor corridors, settlement formulas, timetables, and penalty frameworks have been extracted, audited, and synthesized in this document and in [`../OCRcomments/Terms of Reference/`](../OCRcomments/Terms%20of%20Reference/). Always use this document as your primary, fast, ground-truth reference.

---

## Table of Contents
1. [Executive Overview & Auction Architecture](#1-executive-overview--auction-architecture)
2. [Document 1: Invitation to Bid (NGA-BEAC Auction Notice & Timetable)](#2-document-1-invitation-to-bid-nga-beac-auction-notice--timetable)
3. [Document 2: Annex B — Terms of Reference (TOR 24 August 2026)](#3-document-2-annex-b--terms-of-reference-tor-24-august-2026)
   - [3.1 Auction Lots & Capacity Tranches](#31-auction-lots--capacity-tranches)
   - [3.2 Technical & Operational Dispatch Corridors](#32-technical--operational-dispatch-corridors)
   - [3.3 Fuel Sourcing Hierarchy & Replacement Fuel Rules](#33-fuel-sourcing-hierarchy--replacement-fuel-rules)
   - [3.4 Price Offer Structure & GAT Price Components](#34-price-offer-structure--gat-price-components)
   - [3.5 Performance Standards, Outages & Liquidated Damages](#35-performance-standards-outages--liquidated-damages)
4. [Document 3: Gas Auction Implementation Guidelines (GAIG - 24 Aug 2026)](#4-document-3-gas-auction-implementation-guidelines-gaig---24-aug-2026)
   - [4.1 Governance Structure (DOE, NGA-BEAC, NGAC, TWG)](#41-governance-structure-doe-nga-beac-ngac-twg)
   - [4.2 Off-Taker Allocation & System-Wide Aggregation](#42-off-taker-allocation--system-wide-aggregation)
   - [4.3 Settlement Mechanism & Market Operator Administration](#43-settlement-mechanism--market-operator-administration)
5. [Summary Table of Core Numerical Benchmarks (Resolution 2)](#5-summary-table-of-core-numerical-benchmarks-resolution-2)
6. [Links to Full Text OCR Extractions](#6-links-to-full-text-ocr-extractions)

---

## 1. Executive Overview & Auction Architecture

Under **Department of Energy (DOE) Department Circular No. DC2026-06-0013** and **Republic Act No. 12120 (PNGIDA)**, the DOE has launched the **Mid-Merit Natural Gas Capacity Auction Program** to procure **3,840 MW** of firm, flexible mid-merit generation capacity for the Luzon Grid.

The auction architecture interacts with the Energy Regulatory Commission (ERC) rulemaking under **ERC Case No. 2026-015 RM (GAIR)** through a strict **Two-Resolution Architecture**:
- **Resolution 1 (GAIR Rules)**: Operative statutory methodology, algebra, legal definitions, and enforcement protocols without hardcoded empirical numbers.
- **Resolution 2 (Reference Parameters)**: Adopts the empirical benchmarks set out in the DOE TOR and econometric models (e.g., \$600/kW vs. \$900/kW AIPC, \$1.50/MMBtu terminal cap, 0.05%–0.15%/day BOG, 6,100 BTU/kWh CCGT heat rate ceiling, 80/20 fuel savings sharing, 60% MMDQ volume protection).

---

## 2. Document 1: Invitation to Bid (NGA-BEAC Auction Notice & Timetable)

- **Source File:** `Inviation to Bid re Mid-Merit Natural Gas Capaticy Auction for Gas-Fired Power Generation.pdf` (4 Pages)
- **Full OCR Extraction:** [`../OCRcomments/Terms of Reference/03_Invitation_to_Bid_DOE_Mid_Merit_Auction.md`](../OCRcomments/Terms%20of%20Reference/03_Invitation_to_Bid_DOE_Mid_Merit_Auction.md)

### Key Provisions & Procedural Milestones:
1. **Target Auction Capacity:** **3,840 MW** mid-merit gas-fired capacity for the Luzon Grid.
2. **Eligibility Criteria:**
   - Generation Companies with Service Contracts or valid DOE Certifications.
   - Proven technical capability in CCGT, OCGT, or Gas-Reciprocating Engine (GRE) operations.
   - Financial capability meeting prescribed net worth and debt-equity coverage.
3. **Auction Timetable & Stages:**
   - **Stage 1 (Registration & Accreditation):** Submission of registration documents to the NGA-BEAC via `NGA@doe.gov.ph`. Payment of non-refundable registration fees.
   - **Stage 2 (Pre-Bid Conference & Bulletins):** Issuance of official Bid Bulletins and clarification responses within 3 working days (WD) of conference.
   - **Stage 3 (Pre-Qualification & Bid Submission):** Submission of electronic and physical copies of Technical & Financial Price Offers.
   - **Stage 4 (Evaluation & Auction Proper):** NGA-BEAC opening and ranking of Price Offers against the ERC-determined Gas Auction Threshold (GAT) Price.
   - **Stage 5 (Post-Auction Validation & Award):** NGA-BEAC validation (2 WD) $\rightarrow$ Endorsement to NGAC (1 WD) $\rightarrow$ DOE Secretary issuance of Notice of Award and Certificates of Winning Bidders.

---

## 3. Document 2: Annex B — Terms of Reference (TOR 24 August 2026)

- **Source File:** `Annex B - Terms of Reference.pdf` (32 Pages)
- **Full OCR Extraction:** [`../OCRcomments/Terms of Reference/01_Annex_B_Terms_of_Reference.md`](../OCRcomments/Terms%20of%20Reference/01_Annex_B_Terms_of_Reference.md)

### 3.1 Auction Lots & Capacity Tranches

### 3.1 Auction Lots & Capacity Tranches

#### Official Evaluated Bidders for Lot 1 (Annex A Summary of Evaluation):
| Bidder # | Company | Generating Project / Facility | Phase / Unit | Fuel Type | Lot | Installed Capacity | Offered Capacity |
| :---: | :--- | :--- | :---: | :---: | :--- | :---: | :---: |
| **13** | **FIRST GAS POWER CORPORATION** | 1000 MW Santa Rita Natural Gas-fired Combined Cycle Power Plant | 1000 MW | **Blended** | **Lot 1 - Luzon (2026)** | **1,052 MW** | **1,000 MW** |
| **14** | **FGP CORP.** | 500 MW San Lorenzo Natural Gas-fired Combined Cycle Power Plant | 500 MW | **Blended** | **Lot 1 - Luzon (2026)** | **530 MW** | **500 MW** |

- **Total Evaluated Lot 1 Offered Capacity:** **1,500 MW** (Santa Rita 1,000 MW + San Lorenzo 500 MW).
- **Installed Fleet Capacity Base:** **1,582 MW** (1,052 MW + 530 MW).

The 3,840 MW auction capacity is partitioned into two distinct tranches to balance existing asset utilization with greenfield additions:

| Parameter | Lot 1 (Existing Gas-Fired Plants) | Lot 2 (New-Build & Repowered Facilities) |
| :--- | :--- | :--- |
| **Capacity Allocation** | **1,200 MW – 1,800 MW** | **2,040 MW – 2,640 MW** |
| **Target Plants** | Operational CCGTs (e.g., Santa Rita, San Lorenzo, Ilijan, San Gabriel) | Greenfield CCGTs / Modern Repowered Combined Cycles |
| **Contract Term** | **5-Year Extension Period** (bridges Malampaya depletion) | **15-Year to 20-Year PSA Term** |
| **Minimum Capacity Factor (CF)** | **24.0%** (minimum non-cycling floor) | **37.0% – 42.0%** (mid-merit design band) |
| **Reference Asset Cost (AIPC)** | **\$600.00 / kW** (Brownfield baseline) | **\$900.00 / kW** (Greenfield overnight cost) |
| **Commercial Operation Date (COD)** | Prompt / Extension start date | Prescribed target COD (2028–2030) |

### 3.2 Technical & Operational Dispatch Corridors
1. **Mid-Merit Operating Window:** 1500H to 0500H (14-hour daily cycling band) plus system-directed grid support.
2. **Ramping & Cycling Capabilities:**
   - Fast start-up capabilities: Hot start $< 60$ mins; Warm start $< 120$ mins; Cold start $< 180$ mins.
   - Ramp rates $\ge 4\%$ to $8\%$ of rated capacity per minute.
3. **Reference Heat Rate Ceilings (LHV Baselines):**
   - **CCGT Facilities:** Baseline **5,900 BTU/kWh**; Mid-Merit Cycling Cap **6,100 – 6,350 BTU/kWh**.
   - **OCGT (Peaker) Facilities:** Cycling Cap **9,800 BTU/kWh**.
   - **Gas-Reciprocating Engines (GRE):** Cycling Cap **8,000 BTU/kWh**.

### 3.3 Fuel Sourcing Hierarchy & Replacement Fuel Rules
1. **Mandatory Priority Ranking (Section 3.3 & 10.2):**
   $$\text{Priority 1: Indigenous Natural Gas} \longrightarrow \text{Priority 2: Blended Natural Gas} \longrightarrow \text{Priority 3: 100\% Imported LNG}$$
2. **Replacement Fuel (Liquid Fuel / Diesel / MGO) Firing:**
   - Strictly restricted to **verified Force Majeure events**, pipeline outages, or certified Malampaya supply curtailments.
   - Cost recovery is strictly capped at equivalent heat rate benchmarks—no commercial markups on alternative distillate fuels.

### 3.4 Price Offer Structure & GAT Price Components
- Bidders submit a single levelized non-fuel Price Offer $(\text{PhP/kWh})$ that cannot exceed the GAT Price:
$$\text{GATP} = \text{CRF} + \text{FOM} + \text{VOM} + \text{CLLC}$$
  - $\text{CRF}$: Capital Recovery Fee (70:30 Debt-Equity, 15-yr debt amortization, 10% target WACC).
  - $\text{FOM} / \text{VOM}$: Fixed and Variable Operations & Maintenance costs.
  - $\text{CLLC}$: Capped Landed Logistics Cost (regasification, storage, terminal fees capped at **\$1.50/MMBtu**; boil-off gas capped at **0.05%–0.15%/day**).
- **Fuel Cost Pass-Through (FCPT):** Fuel is excluded from the bid and settled separately under Rule 4, capped at the Gas Price Benchmark (Platts JKM / Indexed formula).
- **Savings Sharing (Option C):** Whenever actual fuel cost is below benchmark, savings are split **80% to Consumers / 20% to Generator Incentive**.

### 3.5 Performance Standards, Outages & Liquidated Damages
1. **Target Availability Factor:** $\text{AF} \ge 90.0\%$ annual target.
2. **Allowable Outages:**
   - Planned Maintenance: Max 30 to 45 days per calendar year.
   - Unplanned / Forced Outages: Max 15 to 20 days per calendar year.
3. **Shortfall & Liquidated Damages:**
   - Failure to deliver energy during designated mid-merit dispatch triggers replacement power obligations at actual WESM cost or contracted liquidated damages.
   - Volume shortfall recovery floor set at **60% MMDQ** (Maximum Monthly Delivery Quantity).

---

## 4. Document 3: Gas Auction Implementation Guidelines (GAIG - 24 Aug 2026)

- **Source File:** `Gas Auction Implementation Guidelines 24Aug26_130pm.pdf` (15 Pages)
- **Full OCR Extraction:** [`../OCRcomments/Terms of Reference/02_Gas_Auction_Implementation_Guidelines_GAIG.md`](../OCRcomments/Terms%20of%20Reference/02_Gas_Auction_Implementation_Guidelines_GAIG.md)

### 4.1 Governance Structure
- **DOE Secretary:** Approves auction results, issues Certificates of Winning Bidders, and exercises final regulatory authority.
- **NGA-BEAC (Bids & Awards Committee):** Conducts pre-qualification, evaluates bids, enforces compliance, and recommends awards.
- **NGAC (Natural Gas Auction Committee):** Oversight body supervising auction execution.
- **TWG (Technical Working Group):** Evaluates technical parameters, grid interconnection, and SCADA data.

### 4.2 Off-Taker Allocation & System-Wide Aggregation
- **GAIG Section 3 Aggregation Principle:** Mid-merit gas capacity benefits the entire Luzon Grid. Consequently, costs and volumes are aggregated system-wide across all WESM Trading Participants, preventing unfair cost-concentration on single distribution utilities (consistent with Supreme Court / ERC Case No. 2004-74).

### 4.3 Settlement Mechanism & Market Operator Administration
- **Administering Entity:** Independent Electricity Market Operator of the Philippines (**IEMOP**).
- **MMSA Ledger System:** Monthly Mid-Merit Settlement Account tracks non-fuel capacity payments, certified fuel cost pass-throughs, and forensic audit disallowances.
- **Shortfall Recovery & Flowback:**
  - Net monthly shortfalls are recovered proportionally from grid off-takers.
  - Excess spot revenues from non-mid-merit generation are credited back via the 80/20 consumer flowback ledger.

---

## 5. Summary Table of Core Numerical Benchmarks (Resolution 2)

| Parameter / Variable | Benchmark Value | Statutory / Technical Source |
| :--- | :--- | :--- |
| **Total Auction Capacity** | **3,840 MW** | DOE DC2026-06-0013 / TOR Annex B |
| **Lot 1 Capacity Tranche** | **1,200 MW – 1,800 MW** | TOR Annex B, Section 3.1 |
| **Lot 2 Capacity Tranche** | **2,040 MW – 2,640 MW** | TOR Annex B, Section 3.1 |
| **Lot 1 Net Capacity Factor** | **24.0%** (Min Floor) | TOR Annex B (Existing Plant Standard) |
| **Lot 2 Net Capacity Factor** | **37.0% – 42.0%** (Mid-Merit) | TOR Annex B (Greenfield Design) |
| **Brownfield AIPC (Lot 1)** | **\$600.00 / kW** | Model 4 DCF / ERC Benchmark |
| **Greenfield AIPC (Lot 2)** | **\$900.00 / kW** | Model 4 DCF / ERC Benchmark |
| **FSRU Terminal / Regas Cap** | **\$1.50 / MMBtu** | Section 17 / FGE Benchmark |
| **BOG Evaporative Loss Cap** | **0.05% – 0.15% / day** | Section 17 / SIGTTO & DNV Standards |
| **CCGT Heat Rate Ceiling** | **6,100 BTU / kWh** (LHV) | Rule 3 / Econometric JKM Regression ($R=0.884$) |
| **Fuel Savings Sharing** | **80% Consumer / 20% Genco** | Option C / Rule 4, Section 23.2 |
| **Volume Protection Floor** | **60% MMDQ** | Rule 5, Section 30 |
| **Corporate Income Tax (CIT)**| **25.0%** | CREATE Act / Tax Code |
| **Target Debt : Equity** | **70% Debt : 30% Equity** | ERC Regulatory Standard |
| **Target WACC** | **10.0%** (Nominal Pre-Tax) | Model 4 DCF Parameters |

---

## 6. Links to Full Text OCR Extractions

For full verbatim transcripts, section-by-section text, and detailed legal provisions, refer directly to the extracted markdown files in `OCRcomments/`:
- 📄 **[Annex B — Terms of Reference Full Text (32 Pages)](../OCRcomments/Terms%20of%20Reference/01_Annex_B_Terms_of_Reference.md)**
- 📄 **[Gas Auction Implementation Guidelines GAIG Full Text (15 Pages)](../OCRcomments/Terms%20of%20Reference/02_Gas_Auction_Implementation_Guidelines_GAIG.md)**
- 📄 **[Official Invitation to Bid & Schedule Full Text (4 Pages)](../OCRcomments/Terms%20of%20Reference/03_Invitation_to_Bid_DOE_Mid_Merit_Auction.md)**
- 📁 **[Master OCR Repository Index (All 20 Submissions)](../OCRcomments/00_MASTER_OCR_INDEX.md)**
- 📁 **[Master Numbers Cheat Sheet (claudenumbers/)](../claudenumbers/01_master_numbers_cheat_sheet.md)**
