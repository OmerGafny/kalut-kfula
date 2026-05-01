---
name: israeli-pension-advisor
description: "Navigate the Israeli pension and savings system including pension funds (keren pensia), manager's insurance (bituach menahalim), training funds (keren hishtalmut), and retirement planning. Use when user asks about Israeli pension, \"pensia\", \"keren hishtalmut\", retirement savings, \"bituach menahalim\", pension contributions, or tax benefits from savings. Uninformed pension decisions cost hundreds of thousands of NIS over a lifetime. Covers mandatory pension, voluntary savings, and withdrawal rules. Do NOT provide specific investment recommendations or fund performance comparisons."
license: MIT
compatibility: No network required.
---

# Israeli Pension Advisor

## Critical Note
This skill provides general pension INFORMATION. It does not replace consultation
with a licensed pension advisor (yoetz pensioni). Recommend professional advice
for specific decisions.

Note for users: a *yoetz pensioni* is a fee-only advisor licensed under the
Pension Advisory Law (2005) with a fiduciary duty to the client. A *sokhen
pensioni* (agent) is paid commissions by the funds. For unbiased advice, ask
specifically for a yoetz pensioni.

## Instructions

### Step 1: Identify Savings Type
| Type | Hebrew | Purpose | Tax Benefit |
|------|--------|---------|-------------|
| Keren Pensia | keren pensia | Retirement + disability + survivors | Tax credit + deduction |
| Bituach Menahalim | bituach menahalim | Retirement (insurance-based, declining for new policies since 2013) | Tax credit + deduction |
| Keren Hishtalmut | keren hishtalmut | Medium-term savings (6 years) | Tax-free gains for employees |
| Kupat Gemel | kupat gemel | General savings/investment | Various |
| Kranot Neemanot | kranot neemanot | Mutual funds | Capital gains tax |

### Step 2: Mandatory Pension Contributions
Since 2008, all employees must have pension. Average wage (2026): 13,769 NIS/month -- this is the base figure for most pension ceilings.

**Employee contributions:**
- **Employee:** 6% of salary
- **Employer pension:** 6.5% of salary (includes disability insurance component up to 2.5%)
- **Employer severance (pitzuim):** 6% of salary (mandatory minimum)
- **Total mandatory minimum:** 18.5% of salary
- **Comprehensive pension fund max deposit:** 5,645 NIS/month (67,740 NIS/year, 2026). Contributions above this go to a supplementary fund.

**Section 14 (most common arrangement):**
- Full severance obligation is 8.33% of salary (one month per year of service)
- Mandatory pension law only requires 6% for severance
- The 2.33% gap: if employer contributes only 6%, they owe the difference on termination, calculated at the employee's final salary
- Most modern contracts use full Section 14 (8.33%) to eliminate this gap
- Tax-exempt severance ceiling: 13,750 NIS per year of service (2026)

**Self-employed mandatory pension:**
- 4.45% on income up to 6,884.50 NIS/month (half average wage)
- 12.55% on income from 6,884.50 to 13,769 NIS/month (full average wage)
- Maximum annual mandatory obligation: 14,044 NIS

**Default pension fund system (selected funds tender):**
- Tender awarded November 2024 to 4 funds (Meitav, Altshuler Shaham, Mor, Infinity); runs through October 31, 2028
- ID-digit auto-assignment by 50+ employee employers in effect since **June 1, 2025** (assignment by check digit: 0-1 -> Meitav; 2-3 -> Altshuler Shaham; 4-5-6 -> Mor; 7-8-9 -> Infinity)
- Smaller employers may select any of the 4 funds
- Fees of 0.22% of balance + 1% of deposits are locked for 10 years from each member's join date (per-member, not tender)
- Employees can switch funds at any time after assignment

**Pension contribution timing for new employees:**
- Employee with existing pension: contributions begin after 3 months, retroactive to day 1
- Employee without existing pension: contributions begin after 6 months (not retroactive)

### Step 3: Keren Hishtalmut (Training Fund)
Most popular Israeli savings vehicle:

**For employees:**
- **Employee contribution:** Up to 2.5% of salary
- **Employer contribution:** Up to 7.5% of salary
- **Tax-free ceiling:** Employer contribution up to salary of 15,712 NIS/month (2026) is tax-free to the employee
- **Withdrawal after 6 years:** Tax-free on gains (unique Israeli benefit)
- **Withdrawal after 3 years:** For education/training purposes only

**For self-employed (two separate ceilings):**
- **Tax deduction from income:** Up to 13,203 NIS/year (4.5% of income up to 293,397 NIS)
- **Profit-exempt ceiling:** 20,566 NIS/year (gains on deposits up to this amount are tax-free after 6 years)

**Note:** In 2024 the Treasury proposed eliminating keren hishtalmut tax-free status for future deposits. As of 2026, this has not been enacted and the tax benefit remains in place.

### Step 4: Tax Benefits Summary

**For employees:**
- **Pension tax credit:** 35% credit on employee contributions up to 679 NIS/month (7% of qualifying salary 9,700 NIS). Maximum credit: 2,852 NIS/year (2026)
- **Employer exclusion:** Employer's pension contribution is not taxed as employee income

**For self-employed:**
- Tax credit (35%) on up to 12,804 NIS/year of pension contributions
- Tax deduction on up to 25,608 NIS/year of pension contributions
- Maximum deductible pension contribution: 38,412 NIS/year (16.5% of income up to 232,800 NIS)

**Pension payout (at retirement):**
- Monthly pension is partially tax-exempt
- 2026 exemption rate: 57.5% (rising to 62.5% in 2027, 67% from 2028)
- Tax-free pension amount: up to 5,422 NIS/month (2026)
- Qualifying pension threshold: 9,430 NIS/month

### Step 5: Withdrawal Rules
- **Pension:** Age 67 (men) / 63 (women, 2026, rising 4 months/year to 65 by 2032 per the 2021 Retirement Age Amendment)
- **Early pension:** Available before retirement age with 35% tax on withdrawal. Exceptions for disability, low income, or terminal illness
- **Keren hishtalmut:** After 6 years (tax-free on gains), or 3 years (education only). Early withdrawal taxes the GAINS at the marginal rate, not the full balance
- **Severance (pitzuim):** Upon termination, subject to Section 14 arrangement. Tax-exempt up to 13,750 NIS per year of service. See Step 6 for the critical Form 161 process before withdrawing.
- **Disability:** Pension funds pay up to 75% of insured salary for disability. Bituach Leumi disability (nechut) may overlap, with offset rules under the unified pension regulations (takanon achid).
- **Sha'erim (survivors):** Pension funds pay 60% of pension to surviving spouse + 30% per orphan (cap 100%). This is included in keren pensia, separate insurance in bituach menahalim.

### Step 6: Severance at Termination (Form 161)
The single most consequential decision at job change. Mistakes here cost tens of thousands of NIS in future tax.

**Tikun 190 / heichum kitzbah** -- The critical interaction users miss:
- Pension payouts at retirement are partially tax-exempt (57.5% of qualifying pension threshold in 2026)
- BUT each shekel of tax-exempt severance withdrawn within 32 years before retirement age REDUCES the lifetime kitzbah-mezakah exemption pool by 1.35x
- A 28-year-old who pulls out 50,000 NIS in tax-free severance at job change loses ~67,500 NIS of future tax-exempt pension allowance

**Forms involved:**
- **Form 161** -- Issued by employer at termination, declaring severance amounts and Section 14 status
- **Form 161א (161A)** -- Filed by employee declaring intent: "draw severance now" (subject to heichum kitzbah), "leave it accumulating" (rezef zechuyot), or "spread tax over up to 6 years" (prisat pituyim)
- **Form 161ד (161D)** -- Filed at retirement to settle the lifetime exemption calculation

**Three options at termination (in order of common preference):**
1. **Rezef zechuyot (continuity)** -- Leave severance in the kupah, no tax event, no impact on future kitzbah-mezakah. Default best for younger workers with future retirement income.
2. **Bittul pituyim (cancellation)** -- If severance was already drawn within the past 2 years, return it to the kupah to restore the exemption pool. Source: Tax Authority procedure 7/2014.
3. **Prisat pituyim (spreading)** -- Spread severance taxation across up to 6 tax years to lower marginal rate. Useful when severance pushes annual income into a higher bracket.

**Default trap:** if the employee files no Form 161א, severance is paid out and treated as immediate withdrawal -- triggering full heichum kitzbah reduction. Always file the form.

### Step 7: Choosing Between Pension Types
**Keren Pensia (Pension Fund):**
- Lower management fees (default funds: 0.22% balance + 1% deposits; non-default: up to 0.5% balance + 6% deposits)
- Includes disability and survivors insurance built-in
- Multiple investment tracks available (age-based, general, shares-focused, bonds-focused, halacha-compliant)
- Preferred for most employees
- Since 2013, most new employees are directed to keren pensia over bituach menahalim

**Bituach Menahalim (Manager's Insurance):**
- Separate insurance component (risk premium)
- More investment track flexibility
- Higher management fees (up to 1.05% balance + up to 4% deposits)
- Declining for new policies since 2013
- May be suitable for high earners with existing policies wanting more control

## Examples

### Example 1: New Employee
User says: "I just started a new job, what pension should I choose?"
Result: Explain mandatory pension (keren pensia vs bituach menahalim), mention default fund assignment system, recommend comparing management fees, suggest keren hishtalmut if employer offers it. Note that most new employees go to keren pensia.

### Example 2: Self-Employed Savings
User says: "I'm a freelancer, how should I save for retirement?"
Result: Explain mandatory pension rates (4.45% + 12.55%), keren hishtalmut two ceilings (13,203 deduction vs 20,566 profit-exempt), maximum deductible pension (38,412 NIS/year). Recommend maximizing keren hishtalmut first.

### Example 3: Approaching Retirement
User says: "I'm 60, when can I start withdrawing pension?"
Result: Explain retirement ages (67 men, ~63 women in 2026), early withdrawal 35% tax, pension payout tax exemption (57.5% exempt, up to 5,422 NIS/month tax-free), lump sum vs monthly pension tradeoffs.

## Bundled Resources

### Scripts
- `scripts/calculate_pension.py` -- Computes mandatory pension contributions (employee, employer, severance), keren hishtalmut benefits, and basic retirement savings projections for both employees and self-employed. Run: `python scripts/calculate_pension.py --help`

### References
- `references/pension-fund-types.md` -- Detailed comparison of Israeli pension vehicles: Keren Pensia, Bituach Menahalim, Kupat Gemel, and Kranot Neemanot, including fee structures, insurance components, default fund system, and major fund providers. Consult when advising on pension fund selection in Step 6.
- `references/tax-benefits.md` -- Israeli pension tax benefits including the 35% tax credit on employee contributions, employer contribution exclusions, keren hishtalmut tax-free gains, self-employed deduction rules, Section 14 details, and pension payout tax exemption rates. Consult when calculating tax savings from pension and savings contributions.

## Recommended MCP Servers

No pension-specific MCP exists today. Pair with general Israeli financial MCPs (e.g., il-bank for transaction data) when the user asks for cash-flow context alongside pension planning.

## Gotchas
- Israeli pension has three distinct product types: comprehensive pension fund (keren pensia makifa), provident fund (kupat gemel), and managers' insurance (bituach menahalim). Agents may treat them as interchangeable, but they have different fee structures, insurance components, and withdrawal rules.
- Pension fund management fees in Israel have two components: from deposits (up to 6% for non-default funds) and from accumulated savings (up to 0.5% annually). Agents may quote only one component. Default selected funds cap at 0.22% balance + 1% deposits.
- The retirement age in Israel is 67 for men and 63 for women in 2026 (rising 4 months per year to 65 by 2032 per the 2021 Retirement Age Amendment). Agents may use the US retirement age of 67 for both genders, or cite the outdated 62 for women, or the older 2035 target date.
- Israeli pension funds invest significantly in local government bonds (igrot chov mimshaltiiot), which means returns are partially linked to Israeli economic performance. Agents should not compare Israeli pension returns directly to US 401(k) S&P 500 benchmarks.
- Self-employed keren hishtalmut has TWO separate ceilings: the tax deduction ceiling (13,203 NIS/year) and the profit-exempt ceiling (20,566 NIS/year). Agents often conflate these into a single figure.
- Bituach Leumi old-age pension (kitzvat zikna) STACKS on top of private pension fund payouts; it is not an offset. Self-employed users sometimes assume one replaces the other and underestimate retirement income, or skip private pension thinking BL is enough.
- At termination, severance withdrawal triggers heichum kitzbah and shrinks the future tax-free pension allowance at a 1.35x ratio. Agents may treat severance as a free 13,750 NIS/year-of-service exemption; in reality it borrows from the lifetime tax-exempt pension pool. Always weigh against rezef zechuyot (leaving severance accumulating).

## Reference Links

| Source | URL | What to Check |
|---|---|---|
| Kol Zchut - Average Wage | https://www.kolzchut.org.il/he/השכר_הממוצע | Annual average wage figure from National Insurance (base for pension ceilings) |
| Kol Zchut - Mandatory Pension | https://www.kolzchut.org.il/he/חובת_ביטוח_פנסיוני_לעובדים | Employee/employer pension rates, Section 14, contribution timing |
| Kol Zchut - Default Pension Funds | https://www.kolzchut.org.il/he/קרנות_פנסיה_נבחרות_(קרנות_ברירת_מחדל) | Default fund tender, ID-digit assignment rules, fee caps |
| Kol Zchut - Severance Tax Exemption | https://www.kolzchut.org.il/he/פטור_ממס_הכנסה_על_פיצויי_פיטורים | Tax-exempt severance ceiling, heichum kitzbah, prisat pituyim |
| Kol Zchut - Severance Withdrawal | https://www.kolzchut.org.il/he/משיכת_כספי_פיצויי_פיטורים_מקופת_גמל_או_מהביטוח_הפנסיוני | Form 161א process, bittul pituyim, rezef zechuyot options |
| Kol Zchut - Retirement Age | https://www.kolzchut.org.il/he/גיל_פרישה_מעבודה | Current male/female retirement ages and the 2032 target schedule |
| Pensuni - 2026 Pension Ceilings | https://pensuni.com/?p=827 | Annual aggregator for tax-credit ceilings, hishtalmut ceilings, kitzbah-mezakah figures |

## Troubleshooting

### Error: "Pension fund not transferring"
Cause: Switching pension funds requires specific process
Solution: Contact new fund to initiate transfer. Old fund must complete within 10 business days. No penalties for switching.

### Error: "Employer not contributing"
Cause: Employer legally required to contribute pension after 6 months (no prior pension) or 3 months retroactive (with prior pension)
Solution: Employer must contribute retroactively from the applicable start date. Contact Ministry of Labor (Misrad HaAvoda) or the pension fund for enforcement.

### Error: "Cannot withdraw keren hishtalmut"
Cause: Lock-in period not completed
Solution: Standard lock-in is 6 years from first deposit. Early withdrawal (3 years) only for education/training with documentation. Withdrawal before maturity is taxed at the marginal income tax rate (up to 50% including surtax for high earners).
