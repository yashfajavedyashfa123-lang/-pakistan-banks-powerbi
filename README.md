# -pakistan-banks-powerbi
Power BI dashboard comparing five Pakistani banks, 2023-2025
# Pakistan Banks Financial Performance Dashboard (2023-2025)

A Power BI dashboard comparing five Pakistani banks on profitability, efficiency, lending and asset quality, using their published annual financial statements.

## Banks covered

| Bank | Type |
|---|---|
| Meezan Bank | Islamic |
| HBL | Conventional |
| UBL | Conventional |
| MCB Bank | Conventional |
| Askari Bank | Conventional |

**Period:** calendar years 2023, 2024 and 2025
**Basis:** unconsolidated statements, all amounts in Rs million

## What the dashboard shows

- **KPI cards:** advances-to-deposits, ROA, ROE and NPL ratio
- **ROE by bank:** which bank earns the most on shareholders' equity
- **Advances to deposits by bank and year:** how much of each bank's deposits is lent out
- **NPL ratio trend:** asset quality over time
- **Cost to income vs ROA:** efficiency compared with profitability
- **Summary table:** net markup income, profit growth, ROE and cost-to-income
- **Slicers:** year and bank type (Islamic or Conventional)

## Measures (DAX)

| Measure | Definition |
|---|---|
| Total Income | Markup earned - markup expensed + non-markup income |
| Net Markup Income | Markup earned - markup expensed |
| Advances to Deposits | Net advances / deposits |
| ROA | Profit after tax / total assets |
| ROE | Profit after tax / equity |
| NPL Ratio | Non-performing loans / gross advances |
| Cost to Income | Total non-markup expenses / total income |
| Profit Growth | Change in profit after tax versus the previous year |

## Key findings (2025, compared with 2024)

1. **Efficiency drives returns.** Meezan has the highest ROE (31.9%) with the lowest cost-to-income ratio (30%). HBL has the lowest ROE (14.0%) and the highest cost-to-income ratio (56%).
2. **Lending fell at every bank.** Advances-to-deposits dropped at all five banks (for example Askari 51% to 36%, UBL 55% to 26%) because deposits grew faster than loans.
3. **Profit growth was uneven.** UBL +59%, HBL +10%, Askari +8%, MCB -6% and Meezan -12%, the last two reflecting lower markup income.
4. **Asset quality differs.** NPL ratios range from about 1.8% (Meezan) to 7.5% (UBL).

## Data and method

- **Source:** each bank's published annual report or investor presentation (unconsolidated financial statements).
- **Equity** includes the surplus on revaluation of assets.
- **Operating expenses (OpEx)** are total non-markup expenses.
- **ROA and ROE** use year-end balances, not averages.
- **Advances** are net of provisions. For Meezan, advances are Islamic financing and related assets.

## Limitations

- HBL's 2024 NPLs and gross advances are not available, so its NPL ratio is blank for that year.
- UBL's 2023 gross advances and NPLs could not be confirmed against its published figures, so they are left out or treated with caution.
- Some gross advances and NPL values (Meezan, MCB, UBL) are rounded.
- Findings describe 2025 against 2024 and use year-end balances, so they are a comparison, not investment advice.

## Files

| File | Description |
|---|---|
| `Pakistan_Banks_Financial_Dashboard.pbix` | The Power BI report |
| `Bank_PowerBI_Data.xlsx` | The data (Data and Banks sheets) |
| `dashboard.png` | Screenshot of the dashboard |

## Tools

Power BI Desktop, DAX, Excel.

## Author

Yashfa Javed
www.linkedin.com/in/yashfa-javed-javed-800445219
yashfajavedyashfa123@gmail.com




