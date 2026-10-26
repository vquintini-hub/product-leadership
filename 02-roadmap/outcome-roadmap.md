# Outcome Roadmap and Trade-off Memo

Fable (B2C) · Product Leadership Certification, Deliverable 2 · Valeria Quintini · Updated 26 October 2026

Fable here is the course's fictional mental-wellness app. All scores and numbers are estimates.

**The problem this quarter:** people feel better within 90 to 120 days and quietly stop using Fable.

Three bets, one per OKR, listed in the order they ship. Built from the Module 1 strategy and OKRs and the Module 2 Rocks and Hard Nos, revised on 15 October with Impact vs Effort scores (1 to 5, after the lab's reality check).

## Now: committed this quarter

| # | Bet | Source | OKR |
| --- | --- | --- | --- |
| 1 | We bet reaching people at the moment in their week when they usually practise will bring them back when they start skipping, for premium users past day 90. | Rock 3: #4, notification fix underneath. Impact 3, Effort 1 | KR1 |
| 2 | We bet a short weekly check-in will keep people practising once a week after they feel better, for premium users past day 90. | Rock 2: #6, reframed. Impact 4, Effort 3 | KR2 |
| 3 | We bet showing people how steady they have been, week by week, will give them a reason to keep premium, for premium users past day 90 who feel well again. | Rock 1: #11, thin first version. Impact 4, Effort 3 | KR3 |

**Sequence:** Bet 1 ships first, because the weekly check-in only works once reminders arrive at the right time.

**Scope of Bet 3 this quarter:** a thin first version of the record, built from in-app activity plus Apple Health sleep data only.

## Next: sequenced after Now

| Item | Why it comes after Now |
| --- | --- |
| Full Apple Health integration, then Oura and other wearables | Prove people value the thin record first, then widen to the full Apple Health data and more partners. |
| A short maintenance practice track (#12, narrowed) | The weekly check-ins will show which practices people keep; build the track from that evidence. |
| Gentle support when someone's patterns change | Needs months of reliable record data, plus clinical advisory review. |
| Onboarding redesign (#1) | Plan Carefully on the matrix: high impact, medium effort. It feeds the post-day-90 group, but the maintenance path needs a baseline first. Q3. |
| Extend the weekly check-in to the first 90 days | Second priority, next quarter. Designed with the Growth team, PM 1 and PM 3 once the version for users past day 90 has results. |
| A maintenance plan at a lower price | Only once KR3 shows whether people downgrade, and once it fits the pricing model. |

## Later: bets, not commitments

- A record people can take to their own coach or practitioner.
- Viewing the record on the web (#8).
- Spanish and Portuguese (#7), once the model works in existing markets.

## Not building this cycle

| Item | Why not |
| --- | --- |
| #2 Daily streak (Hard No 1) | Impact 1, Effort 3. Works against the strategy: people who are well do not need daily pressure, and a broken streak would feel like failure. |
| #3 Social layer (Hard No 2) | Impact 1, Effort 4. Fable is a private space; sharing works against that trust and does nothing for retention after day 90. |
| #13 Fable for Teams (Hard No 3) | Impact 1, Effort 5. Different buyers, a B2B sales motion and contracts the 14-person team cannot support. Revisit once the consumer maintenance path works. |
| #5 Therapist-matching | Ruled out by the no-clinical constraint. |
| #9 Crisis mode | Acute care and clinical risk, outside this initiative. |

Accessibility (#10) and load time (#14) run as maintenance with a fixed share of capacity.

## Trade-off memo

**What we chose.** This quarter all three bets serve one group: premium users past day 90. That is where Fable loses the people most likely to pay.

**What we gave up, and what it costs.**

- **Onboarding redesign.** 40% of new users drop off early, and that data is real. Waiting means fewer people reach day 90. We accept that cost because the maintenance path needs a baseline before we change who enters it. Onboarding is the first item in Next.
- **The check-in for new users.** The Growth team wants it for conversion. It launches for users past day 90 first. The first-90-days version is designed with Growth at the start of next quarter, and until then Growth gets the check-in results every month.
- **The social layer and daily streaks.** Both could lift engagement numbers in the short term. Both work against what people who feel well need: a private space and no daily pressure.
- **Fable for Teams.** It could open new revenue. It needs a B2B sales motion this team does not have, and it pulls focus from the consumer problem we are solving.
- **Full wearables.** Oura and the full Apple Health integration wait until people show they value the thin record.

**How the decision was checked.** I scored the backlog with RICE, WSJF and a weighted scorecard, using assumed numbers. All three put the notification fix and the weekly check-in at or near the top. WSJF and the scorecard put the daily streak last. RICE ranked it high, because RICE counts reach and ignores strategy. The check added two things: a clear sequence, and a thin first version of the record, which is the largest job and the most likely to slip.

**What would change our mind.** If the record does not lift premium retention at day 120 by at least 5 points against a comparison group by 31 March 2027, we stop building it and move its engineers to onboarding. The numbers are in 04-financial-model/financial-model.md.
