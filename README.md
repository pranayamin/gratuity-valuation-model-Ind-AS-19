# Defined Benefit Obligation (Gratuity) Valuation Engine — Ind AS 19 / AS 15

An actuarial valuation model built in Microsoft Excel implementing the Projected Unit Credit (PUC) method to value gratuity obligations in accordance with Ind AS 19 and the Payment of Gratuity Act, 1972.

# Project Overview
* Valuation Method: Projected Unit Credit (PUC) with service proration
* Accounting Standards: Ind AS 19 / AS 15 (Revised)
* Demographic Assumptions: IALM (2012–14) Ultimate Mortality Table, 5.00% flat attrition rate, Retirement Age 60
* Financial Assumptions: Base Discount Rate: 7.25% p.a. | Salary Growth Rate: 6.50% p.a.
* Statutory Limit: ₹20,00,000 benefit cap

## 📊 Key Features
1. Multi-Decrement Cash Flow Projections: Combines mortality decrements ($q_x$), withdrawal decrements ($w_x$), and retirement decrements into cumulative survival probabilities ($tPx$).
2. Dynamic PUC Attribution: Accrues past service liabilities while projecting final drawn wages ($15/26 \times \text{Salary} \times \text{Past Service}$).
3. Sensitivity Analysis (Para 145 Disclosures): Evaluates liability variance against interest rate shifts (±100 bps) and salary escalation shifts (±100 bps).

# Repository Structure
* `Actuarial Valuation Model.xlsx"` — Full Excel valuation model
