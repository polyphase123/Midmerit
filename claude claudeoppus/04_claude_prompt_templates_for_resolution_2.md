# READY-TO-USE CLAUDE PROMPT TEMPLATES FOR RESOLUTION 2

Use these exact copy-paste prompt structures when asking Claude to draft Resolution 2, calculate GATP tariffs, or conduct audit verifications.

---

### Template 1: Drafting the Full Reference Parameters Resolution (Resolution 2)

```text
You are Senior Energy Regulatory Counsel and Chief Financial Modeler at the Energy Regulatory Commission (ERC).

Draft the complete, formal ERC Resolution entitled:
"A RESOLUTION ADOPTING THE REFERENCE DCF MODEL PARAMETERS, GAS PRICE BENCHMARK VALUES, ALLOWABLE LOGISTICS COST CAPS, AND REFERENCE HEAT RATES UNDER THE GAS AUCTION IMPLEMENTING RULES (GAIR) FOR THE MID-MERIT NATURAL GAS CAPACITY AUCTION PROGRAM (ERC CASE NO. 2026-015 RM)"

Use the exact ground-truth parameters from the claudenumbers repository:
1. Technology Capital Benchmarks:
   - CCGT: 1,200 MW, $600/kW brownfield vs. $900/kW greenfield, 45% CF (37-42% Luzon TOR band).
   - OCGT: 200 MW, $450/kW brownfield vs. $520/kW greenfield, 20% CF.
   - Gas-Reciprocating Engine: 100 MW, $750/kW brownfield vs. $850/kW greenfield, 40% CF.
2. Financing & O&M:
   - CCGT Fixed O&M: $13.71/kW-yr, Variable O&M: $2.00/MWh, G&A: 6.0%.
   - 70:30 Debt:Equity, 8.0% Pre-tax Cost of Debt, 15-year repayment tenor, 10.0% pre-tax WACC.
3. Logistics Cost Caps (CLLC):
   - FSRU / Terminal Regasification Fee: $1.50/MMBtu hard cap.
   - BOG Evaporative Loss Cap: 0.10%/day (max 0.15%/day).
   - Pipeline Transport: $0.40/MMBtu.
4. Heat Rate Ceilings:
   - CCGT New-Build: 6,100 BTU/kWh (0.006100 MMBtu/kWh).
   - CCGT Existing: 6,350 BTU/kWh (0.006350 MMBtu/kWh).
   - G-RE: 8,000 BTU/kWh. OCGT: 9,800 BTU/kWh.
5. Regulatory Mechanisms:
   - Option C (80% Consumer / 20% GenCo) Fuel Cost Savings Sharing.
   - 60% MMDQ Volume Protection with 15-year guarantee recovery sunset.
   - Mandatory automated deduction of audit disallowances ($15.65M precedent) from monthly MMSA ledgers.

Draft the resolution with formal WHEREAS recitals, OPERATIVE RESOLUTION sections, and complete Annex Tables (Annex A, Annex O, Annex G, Annex BOG, Annex CLLC).
```

---

### Template 2: Levelized Tariff / GATP Calculation Prompt

```text
You are Senior Financial Analyst at the ERC.

Calculate the exact Levelized Cost of Electricity (LCOE / GATP) in PhP/kWh for a representative CCGT plant using the ERC DCF Model and the following adopted Resolution 2 parameters:
- Reference Capacity: 1,200 MW
- Net Capacity Factor: 45.0%
- Brownfield AIPC: $600.00/kW (USD/PHP FX = 56.00)
- Fixed O&M: $13.71/kW-year
- Variable O&M: $2.00/MWh
- G&A: 6.0% of (FOM + VOM)
- Debt/Equity: 70% Debt / 30% Equity
- Debt Cost: 8.00% p.a., Debt Repayment: 15 years
- Target Equity Return: 12.00% post-tax, WACC: 10.00% pre-tax
- Construction: 3 years, Operating Life: 30 years
- Corporate Tax: 25% Regular CIT / 2% MCIT (Year 4+)

Provide:
1. Unbundled Capital Recovery Fee (CRF in PhP/kWh)
2. Fixed and Variable Non-Fuel O&M Rate (PhP/kWh)
3. Capped Landed Logistics Cost Component (CLLC in PhP/kWh at $1.50/MMBtu cap)
4. Total Base Gas Auction Threshold Price (GATP in PhP/kWh)
5. Fuel Pass-Through add-on under Option C (80/20 Sharing) at Platts JKM = $13.50/MMBtu and Heat Rate = 6,100 BTU/kWh.
```
