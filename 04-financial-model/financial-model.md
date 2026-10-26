# Financial Model: [Fable / Meridian / your initiative]

> Module 5 · Build the Business Case and the Kill Line, ★ Deliverable 5

## 1. Business case

| Assumption | Value | Source / rationale |
|---|---|---|
| Strategic bet | Many paying users leave Fable once they feel better. I want to give them a reason to stay: a weekly record that shows how well they have been doing, using their practice and sleep data. If they cancel, they lose the record. More people stay on premium, so revenue goes up (KR3). | _____ |
| What the case rests on | 1. The record keeps people paying. The share still on premium at day 180 goes from 25% to 40%. This assumption matters most. 2. 20,000 premium users reach day 90 each quarter. 3. Premium costs $9.99 a month. 4. People who are still paying at day 180 pay for about six more months. 5. A simple first version costs about $200,000. These are my assumptions. The brief does not give these numbers. | _____ |
| Expected return | Each extra paying user brings about $60 (six months at $9.99). If 15 more people in every 100 stay, that is 3,000 extra paying users each quarter. That is about $180,000 a quarter, or about $720,000 a year. We will see the first sign at day 120, about two months before day 180. All numbers are estimates. | _____ |

> **The case in one paragraph:** The bet: Many paying users leave Fable once they feel better. A weekly record of how well they have been doing gives them a reason to stay, because cancelling means losing it. More people stay on premium, so revenue goes up (KR3). Assumptions, ranked (all mine; the brief gives none of these numbers): 1. The record lifts the share still on premium at day 180 from 25% to 40%. This matters most, so we measure it against a group that does not get the record. 2. 20,000 premium users reach day 90 each quarter. 3. Premium costs $9.99 a month. 4. People still paying at day 180 pay for about six more months. 5. A simple first version costs about $200,000 to build, plus about $50,000 a year for clinical review, support and running costs. Expected return: Each extra paying user brings about $60. If 15 more people in every 100 stay, that is 3,000 extra paying users and about $180,000 each quarter, roughly $720,000 a year. If the lift is 30% smaller, it is about $126,000 a quarter, which still covers the cost within a year. We see the first sign at day 120. All numbers are estimates. Kill criterion: On 31 March 2027 we compare premium retention at day 120 between users with the record and the group without it. If the gap is less than 5 points, we stop building the record and move its engineers to the onboarding redesign in Q2 2027. We do not wait another quarter.

## 2. Kill criteria

> **Kill criterion:** On 31 March 2027 we check premium retention at day 120 for the first group using the record. If it is not at least 5 points above 25%, we stop building the record. Those engineers move to the onboarding redesign in Q2 2027. We do not wait another quarter.

## Link to full artifact

_[link to this deliverable in your repo]_

## Lab notes

**Make your evaluation and funding decision**

- **What assumption is doing the most work? If this number is 20-30% off, what changes?:** The 4% individual-to-team conversion. At 2.8% to 3.2%, converting users fall from 120 to 84 to 96 a quarter and Q1 ARR from $103,680 to about $73,000 to $83,000. CAC per converting user rises from about $950 to $1,190 to $1,360, so payback stretches to 16 to 19 months.
- **What is the structural problem in this case? Look past the headline numbers for something that does not hold up on closer inspection.:** The payback is wrong. CAC is $38 per individual, but only 4% convert, so CAC per converting user is about $950 against $72 a month in team revenue: about 13 months, not 4.7. The 15% team churn is never used, and repeating 120 conversions every quarter assumes the pool of 3,000 weekly-actives refills. For Fable, a team tier is a B2B product with new buyers, outside the existing freemium and premium model.
- **Is the kill criterion complete and actionable? Does it name the consequence, or hand the decision back to the room?:** No. It names the metric, a threshold and a date, but "the go-to-market approach is reassessed" is not a consequence: it hands the decision back to the room. And the 3% threshold sits below the 4% the case needs, so the bet could miss its own return and still survive.
- **Your verdict: FUND / FUND WITH ONE CONDITION / DO NOT FUND. If a condition, name it; otherwise explain in one sentence.:** DO NOT FUND. The corrected payback is about 13 months, the case ignores churn, and a team tier is the Fable for Teams bet I ruled out as a Hard No. What would change my mind: a pilot showing at least 4% conversion with payback under 12 months on fully loaded CAC, without pulling engineers from the post-day-90 work.
