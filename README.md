# Bank Marketing Campaign Effectiveness

## Overview

This project examines term-deposit subscriptions from a Portuguese bank’s telephone campaigns. It compares contact channels, outreach frequency, and campaign history to identify a follow-up strategy worth testing.

**Tools** · Python, Pandas, Matplotlib, and Seaborn

[Analysis notebook](bank-marketing-campaign-effectiveness.ipynb) · [UCI Bank Marketing dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing) · [Moro, Cortez, and Rita (2014)](https://doi.org/10.1016/j.dss.2014.03.001)

## Questions and answers

| Question | Finding |
| --- | --- |
| What was the overall subscription rate? | **11.3%** (4,639 of 41,176 records after removing exact duplicates). |
| Which contact channel had more subscriptions? | Cellular had **14.7%** (3,852 of 26,135) versus **5.2%** for telephone (787 of 15,041). |
| How did outcomes vary by number of contacts? | The rate fell from **13.0%** after one contact to **6.1%** after five or more. |
| How did previous campaign outcomes relate to subscriptions? | The rate was **65.1%** after prior success, **14.2%** after prior failure, and **8.8%** with no recorded prior outcome. |
| Did time since prior contact matter? | Among 1,515 records with known recency and prior contact, the rate was **66.2%** at 4–7 days and **57.1%** at 8+ days. |
| Was there a consistent best weekday? | Thursday led overall at **12.1%**. The leading weekday differed in each of the three largest month groups. |
| Did the contact-count pattern hold within each channel? | At five or more contacts, rates were lower than at one contact for both cellular (**7.7% vs. 16.6%**) and telephone (**4.1% vs. 6.0%**). |

## Conclusion

Test two follow-up schedules, balance the test groups by channel and prior outcome, and measure subscriptions per assigned client over a fixed period. The observed rates describe campaign records. They cannot establish the effect of changing contact frequency.
