# Mid-Merit Gas Auction Rules (GAIR): 100 Developer Questions, Explained Simply (ELI15)

*Based on the current working draft of the Rules on the Gas Auction Threshold Price, Gas Price Benchmark and Settlement Mechanism (ERC Case No. 2026-015 RM). Section numbers refer to that draft. Values marked "to be set" will be fixed by the Commission in the Reference Parameters Resolution. This is an explainer, not the Rules: where they differ, the Rules govern.*

---

## A. The basics

**1. What is the GAT Price?**
It is the ceiling for your bid. If your Price Offer is higher than the GAT Price for your Facility Type, you are automatically out (Sec. 5). Think of it as the "most you're allowed to ask" for building and running the plant, not counting fuel.

**2. What exactly does the GAT Price pay for?**
Two things: CRF, the money to pay back the plant (capital, financing, taxes, overhead), and OM, the cost of running and maintaining it. GATP = CRF + OM (Sec. 8.6). Fuel is paid separately.

**3. Why isn't fuel in the GAT Price?**
Fuel prices jump around every month, and different bidders use different gas (Malampaya, imported LNG, a mix). Keeping fuel out means everyone competes on the same thing, the cost of the plant itself, and fuel is paid at actual cost up to a cap (Sec. 9, 10).

**4. Who sets the GAT Price?**
The ERC, using a cash-flow model and a set of reference values for things like capital cost, interest rates and capacity factor (Sec. 8). The DOE runs the auction itself.

**5. When will the GAT Price be issued?**
Within 60 calendar days after the Invitation to Bid for the first auction round, and within 30 days for later rounds (Sec. 7).

**6. Is there one GAT Price for everyone?**
No. There is a separate GAT Price for each Facility Type: CCGT, OCGT, gas-engine plants, and any other gas technology the DOE adds (Sec. 6).

**7. Does it matter whether I use Malampaya gas or imported LNG?**
Not for the GAT Price: it is the same for every gas source (Sec. 10). Your gas source affects only your Fuel Cost, which is benchmarked and capped separately.

**8. What is the "Gas Auction Price" (GAP)?**
It is your winning Price Offer, endorsed by the DOE. You get paid your GAP per kWh, plus the certified Fuel Cost (Sec. 29).

**9. Is the GAT Price adjusted for inflation every year?**
No. Once set, it stays fixed in pesos for the whole award: no indexing for inflation, exchange rates or interest rates (Sec. 8.9). Price that risk into your offer.

**10. Is the GAT Price in dollars or pesos?**
Pesos per kWh. Even if your loans are in dollars, the GAT Price and your GAP are fixed in pesos (Sec. 8.5).

## B. How the GAT Price is computed

**11. How does the ERC actually calculate it?**
It builds a model of a typical reference plant, adds up every year's costs over its life, and finds the flat price per kWh at which the owner earns exactly its required equity return. In finance terms, the equity NPV is zero (Sec. 8.4, 8.8.8).

**12. What return on equity does the model assume?**
A Reference Equity Required Rate of Return set by the Commission for each auction round (Annex A.12). It is a nominal figure.

**13. What debt assumptions are used?**
A reference debt-to-equity ratio, cost of debt and repayment period, all set by the Commission (Annex A.9–A.11). The working model uses typical project-finance values.

**14. Over how many years are costs recovered?**
The model uses the plant's economic life, the Reference Operating Period (Annex A.8). This can be longer than your contract with the auction.

**15. Does the model assume my plant runs all the time?**
No. It uses a Reference Net Capacity Factor for a mid-merit plant (Annex A.2). Mid-merit plants run part of the day, not 24/7.

**16. What capital cost does the model use?**
A Reference All-In Project Cost per kW for each Facility Type (Annex A.3). "All-in" covers equipment, construction, development, contingency, financing during construction and working capital.

**17. Are taxes included?**
Yes. Income tax, real property tax, local business tax and the ER 1-94 host-community benefit are all in the model, so they sit inside the CRF part of the price (Sec. 8.8.3; Annex A.14, A.26).

**18. Is my grid connection included?**
Only your own dedicated connection to the grid. Bigger shared transmission projects (Associated Transmission Projects) are paid back another way: the grid operator reimburses you, not consumers through your price (Sec. 9.3).

**19. Will the ERC publish its assumptions?**
Yes. The Reference Parameters Resolution has to state each key value and where it came from (Sec. 8.7). That is what you can challenge with evidence.

**20. Can I see the model itself?**
The Rules set out every calculation step (Sec. 8.8). Bidders can rebuild the computation from the published parameters.

## C. Bidding

**21. What do I actually bid?**
A Price Offer in PhP/kWh covering your plant cost (capital and O&M), with no fuel and no logistics (Sec. 5, 8.6).

**22. Can I include logistics costs like regas fees in my bid?**
No. Logistics costs must not be in any Price Offer. They are recovered through the Fuel Cost, up to the caps (Sec. 8.6).

**23. What happens if my offer is above the GAT Price?**
It is automatically disqualified (Sec. 5).

**24. How are bids ranked?**
On the Price Offer, within each declared Fuel Source Category, as the DOE Terms of Reference provide (Sec. 5).

**25. Why rank within fuel categories?**
Because fuel is paid separately and capped the same way for everyone in a category. Comparing plant prices within the same fuel type is fair.

**26. Do I have to declare my fuel source?**
Yes. You declare a Fuel Source Category under the Terms of Reference (Sec. 14.4).

**27. Can I change my fuel source later?**
Only through the Replacement Fuel rules, if your declared fuel is unavailable (supply interruption, force majeure and similar), and subject to conditions (Sec. 21.1).

**28. Should I bid exactly at the GAT Price?**
That is a business choice. The GAT Price is a ceiling; the auction picks the lowest offers. A lower, realistic offer improves your chance of winning.

**29. Are there technical requirements for my plant?**
Yes. The reference plant must meet the minimum flexibility requirements in the Terms of Reference, such as ramping and start-up for mid-merit duty (Sec. 6.5).

**30. Will the ERC tell me my fuel supplier or contract terms?**
No. The ERC does not choose your fuel source, supplier or contract structure. You must submit your gas or LNG contracts so the ERC can benchmark and verify them (Sec. 14.4, 15.4).

## D. Fuel Cost and the Gas Price Benchmark

**31. How do I get paid for fuel?**
Through the Fuel Cost Pass-Through: each month, your actual, reasonable and prudent fuel cost is paid, up to the benchmark and caps, after ERC certification (Sec. 21, 23).

**32. What is the Fuel Cost formula?**
FC = FCC + CLLC. That is the fuel commodity (the gas itself) plus the Capped Landed Logistics Cost (getting the gas to your plant), both in PhP/kWh (Sec. 18).

**33. What is the "Gas Price Benchmark"?**
The maximum reference price for gas that can be passed to consumers, built from a Reference Gas Price for your gas source plus capped logistics costs (Sec. 12, 13).

**34. How is the Reference Gas Price for imported LNG set?**
From market benchmarks such as the JKM spot index and equivalent long-term contract prices, published monthly by the ERC (Sec. 15).

**35. What if my LNG contract is oil-linked (Brent)?**
Allowed. The contract price can use the formula Slope × Brent + Constant, with the slope inside a range the ERC sets (Sec. 15.1(d)).

**36. How is the Reference Gas Price for Malampaya or other domestic gas set?**
From actual domestic gas contract prices, DOE price determinations and similar benchmarks. It can't be higher than the price of imported LNG, unless the ERC approves otherwise after a hearing (Sec. 14).

**37. What if I use a blend of domestic gas and LNG?**
The reference price is a weighted average based on how much of each gas you actually used that month (Sec. 16).

**38. What if my actual fuel cost is above the benchmark?**
Only the benchmark amount is paid. The extra is your cost (Sec. 23).

**39. What if my actual fuel cost is below the benchmark?**
You get paid your actual cost, not the benchmark. The difference goes to consumers (Sec. 23.2).

**40. What if fuel prices spike suddenly in one month?**
The ERC can spread a very large month-on-month increase over later months (rate-shock smoothing). You still recover the full prudent amount, just later (Sec. 23.1).

**41. How often is the benchmark updated?**
At least once a year, or within 60 days of a big market change, after public consultation (Sec. 20).

**42. Is VAT on fuel recoverable?**
Yes, at the applicable rate. Imported LNG carries VAT; domestic (indigenous) gas is VAT-exempt under the PNGIDA law, so its VAT rate is zero. Blends use a weighted rate (Sec. 18(d)).

## E. Logistics costs (CLLC) and the caps

**43. What counts as a logistics cost?**
Regasification/terminal fees, pipeline transport, marine or trucking transport, LNG storage, gas processing/conditioning, and measurement and metering (Sec. 17).

**44. Are logistics costs capped?**
Yes, component by component. Each is paid at the lower of your actual cost and its cap (Sec. 17, 18(e), 23).

**45. What are the cap values?**
To be set by the Commission for each auction round, possibly different for each Fuel Source Category, and reviewed at least yearly (Sec. 17, 20).

**46. Do regasification and terminal fees apply to Malampaya gas?**
No. Malampaya gas arrives by pipeline as gas, not as LNG, so there is nothing to regasify. Those fees apply to imported LNG only. Domestic gas can carry pipeline, processing and metering costs (Sec. 17).

**47. Is boil-off gas (LNG lost to evaporation) paid separately?**
No separate allowance. Normal boil-off is part of the regasification/terminal component and its cap (Sec. 17).

**48. What if my terminal contract charges a fixed monthly fee even when I use no LNG?**
The Rules certify actual, prudent logistics costs up to the cap, measured against the fuel actually used. How a fixed fee in a month with no LNG is treated is not spelled out yet. Assume it may not be fully recoverable, and raise it in consultation.

**49. Why cap logistics at all?**
So consumers don't pay for unnecessary or inflated charges, such as an overpriced terminal fee from a sister company. Caps reward efficient supply chains.

**50. Can I recover a terminal or pipeline I built myself through logistics charges?**
Not if that cost is already in your capital cost or in the GAT Price. The Rules bar paying for the same infrastructure twice (Sec. 17).

**51. Is VAT on logistics services recoverable?**
Yes, shown as a separate line, excluding any component that is VAT-exempt (Sec. 18(f)).

**52. What if logistics costs move a lot during the year?**
The ERC can update the caps within 60 days of a material, sustained change in freight, insurance or other logistics costs (Sec. 20).

## F. Heat rate

**53. What is "heat rate"?**
How much fuel energy your plant burns to make one kWh. A lower heat rate means a more efficient plant.

**54. Why does heat rate matter to me?**
Fuel Cost = gas price × heat rate × exchange rate. A less efficient plant burns more gas per kWh, so the heat rate directly sets how much fuel you can recover (Sec. 18).

**55. Is there a heat rate cap?**
Yes. The ERC sets a Reference Heat Rate cap for each Facility Type. Fuel burned above it is not passed to consumers (Sec. 19).

**56. Is the cap based on full-load, brand-new conditions?**
No. It reflects realistic mid-merit operation: part-load, ramping and cycling, at Philippine site conditions (Sec. 19).

**57. Does the cap allow for my plant getting older?**
The ERC can include a heat-rate degradation factor for normal wear and tear when it reviews the cap (Sec. 20).

**58. Which heat rate is used each month?**
Your verified actual average net heat rate for the month, but never more than the cap (Sec. 18(b), 19).

## G. Exchange rate and taxes

**59. Which exchange rate converts dollar fuel costs to pesos?**
The current draft says the BSP rate averaged over the settlement period (Sec. 18(c)). The wording is being refined: one option under study is using the BAP rate on the actual payment date for true-ups, to match BIR rules.

**60. Why does the exchange rate matter?**
Most LNG is priced in dollars. A weaker peso means a higher peso fuel cost, which is passed through, but only at the official rate, with no extra markup.

**61. Can I add bank charges or a spread on the exchange rate?**
No. Fuel is converted at the official benchmark rate only. Bank charges are your own cost.

**62. What does the BIR say about exchange rates?**
For tax purposes, BIR RMC No. 12-2024 uses BAP rates on the transaction date for US-dollar transactions, and doesn't allow monthly averages. Keep your fuel billing and tax books reconcilable.

**63. Is my capacity price (GAP) affected by exchange rates?**
No. The GAP is fixed in pesos. Only the Fuel Cost moves with the exchange rate (Sec. 8.5, 8.9).

**64. Are BOI or PEZA incentives assumed in the GAT Price?**
No. The model assumes no tax holiday or special incentives (Annex A.14). If you have them, your actual costs may be lower than the reference.

**65. Is customs duty on imported equipment included?**
Yes, in the capital cost assumptions (Annex A.22).

**66. Is VAT on imported equipment recoverable?**
In the model it is treated as a project cost unless a BOI incentive allows recovery (Annex A.22).

## H. Getting paid: settlement

**67. How is my monthly payment calculated?**
MMSA = Energy Delivered × (GAP + Fuel Cost), counting energy delivered during the Mid-Merit Operating Period (Sec. 29).

**68. Who pays me?**
Mainly the WESM spot market, settled by the Market Operator (IEMOP). The auction mechanism tops up or trims what the WESM pays, so you end up with your MMSA (Sec. 28–31).

**69. What if the WESM pays me less than my MMSA?**
The shortfall is collected from WESM customers in your grid and paid to you (Sec. 30).

**70. What if the WESM pays me more than my MMSA?**
The excess flows back to WESM customers (Sec. 31).

**71. How is the shortfall shared among customers?**
In proportion to each customer's energy use (GESQ) in the same settlement period (Sec. 30.2).

**72. How long does the shortfall guarantee last?**
Only during your Settlement Guarantee Period, which matches your Supply Delivery Period in the Terms of Reference, even though the model recovers capital over a longer life (Sec. 30.5).

**73. Is energy outside mid-merit hours paid at GAP?**
No. Where the Terms of Reference require energy outside mid-merit hours (like Lot 1), that energy is paid Fuel Cost only, with no GAP. For other plants, off-hours energy is settled under normal WESM rules, except energy produced on the System Operator's redispatch instruction, which may be paid at Fuel Cost (Sec. 29).

**74. When can the Market Operator start settlement?**
Only after the ERC approves the Settlement Mechanism and the WESM Governance Arm certifies the systems are ready (Sec. 33).

**75. What if fuel certification is late for WESM settlement?**
The MO uses the last certified Fuel Cost or an ERC provisional estimate, then corrects it later (Sec. 23.3).

**76. Do I get paid for capacity even if I'm not dispatched?**
The settlement is based on energy actually delivered, not a separate capacity payment (Sec. 29).

**77. Who pays the Market Operator's costs of running all this?**
The MO can apply to the ERC to recover prudent costs. You don't pay them through your GAP (Sec. 32).

**78. Can customers claim extra compensation beyond their allocation?**
No. Customers get only their computed collection or flowback allocation (Sec. 31.6).

## I. Reporting, certification and audit

**79. What must I report each month?**
A Monthly Fuel Cost Report to the ERC within 10 calendar days after each billing month. It covers fuel quantities, prices, logistics invoices, heat rate and the fuel cost computation (Sec. 22).

**80. How fast does the ERC certify my Fuel Cost?**
Completeness check within 5 working days, staff audit within 10 more working days, and certification by the 30th calendar day after the billing month (Sec. 23).

**81. Is each fuel component checked separately?**
Yes, component by component: gas price, heat rate, each logistics item. Each is certified at the lower of actual or its benchmark or cap (Sec. 23).

**82. How long must I keep records?**
At least 7 years from each transaction: contracts, invoices, cargo papers, metering records and proof of payment (Sec. 24).

**83. How often will the ERC audit my fuel procurement?**
At least once every 2 years during your award (Sec. 25).

**84. What does the audit check?**
Whether you bought gas at the best reasonable terms, stayed within the caps, and claimed nothing twice; that your heat rate matches your plant's design and tests; and that there are no hidden related-party deals or rebates. You must also disclose related parties when you register and every year after (Sec. 25).

**85. What happens if the audit finds I overcharged?**
The ERC issues a Notice of Disallowance, the amount is offset against your future Fuel Cost payments (with interest), and the ERC reports it to the DOE. Repeated disallowances, 3 or more in 12 months, can bring further action (Sec. 26).

**86. Can the ERC inspect my plant?**
Yes, on at least 5 business days' notice, or without that notice in cases of suspected fraud or serious non-compliance (Sec. 35).

**87. What other reports are required?**
Periodic reports such as audited fuel statements and operating data, in the format the ERC prescribes (Sec. 34).

**88. What are the penalties for breaking the Rules?**
Fines and penalties under Section 46 of EPIRA, for example for false documents, missed reports, or obstructing an audit (Sec. 36).

**89. Can I see how my certified Fuel Cost was computed?**
Yes. Certification is component by component against published benchmarks and caps, so you can trace each number.

**90. What if I disagree with a disallowance?**
The Notice states the amount and the basis, so you can respond with documents. Formal remedies follow the ERC's Rules of Practice and Procedure.

## J. Existing plants (Lot 1), transmission and other questions

**91. Can existing plants join?**
Yes. Lots 1 and 2 are for existing gas plants. Their reference capital cost reflects an operating or retooled plant, not a new build (Annex A.3).

**92. What if a Lot 1 plant needs upgrades to extend its life?**
If the DOE grants an extension of up to 5 years after retrofitting, you can apply to the ERC to adjust your GAP for the extension period. It is not automatic, and it can't recover costs twice (Sec. 11).

**93. How fast does the ERC decide on an extension GAP?**
Within 45 calendar days of a complete application (Sec. 11.4).

**94. Who must connect my plant to the grid?**
You. It is primarily the winning bidder's responsibility (Sec. 9.1).

**95. What if the grid connection is delayed?**
You may choose to finance and build the needed transmission yourself, with ERC approval, and be reimbursed its fair market value when the grid operator takes it over. This is outside your GAP (Sec. 9.2–9.3).

**96. Is there an auction lot in Mindanao?**
Not in the current DOE Terms of Reference: the lots are in Luzon and the Visayas.

**97. Are Visayas plants priced differently from Luzon?**
The GAT Price is per Facility Type and per kW, so it is the same for the same technology. Visayas logistics differences show up in the Fuel Cost caps, not the GAT Price.

**98. Can OCGTs or gas engines compete?**
Yes. They have their own GAT Prices as separate Facility Types (Sec. 6).

**99. What if my actual costs end up higher than the reference values?**
The GAT Price won't change for you: it is fixed. That is why you should send evidence during consultation if you think a reference value is too low.

**100. How can I influence the final numbers?**
Join the consultations and submit evidence, such as EPC quotes, financing terms and O&M contracts. The ERC must publish the basis for each parameter, and evidence-backed comments are what move them (Sec. 8.7).

---
*Prepared for stakeholder information. Figures to be set by the Commission are not shown.*
