# 60-day action and measurement plan

**Portfolio extension — 6 November 2026.** Proposed sequence and functional owners, not an executed Gousto engagement. Start dates are relative to approval and access; SEO and cohort outcomes may require observation beyond day 60.

## Priorities and dependencies

| Timing | Work and proposed owner | Deliverable and dependency | Decision gate |
|---|---|---|---|
| Days 1–10 | Analytics + SEO: refresh comparable search and technical baselines. Commercial analytics: define promotion cohorts. | Agreed date/device/market filters; query classification; event definitions; access to permitted analytics. | Do not carry historical estimates into a current business baseline without remeasurement. |
| Days 1–15 | Web engineering + SEO: reproduce issues on homepage, pricing and relevant templates. Customer operations: validate any incident leads. | Performance traces; affected-URL list; severity assessment using operational records. | Fix confirmed high-impact issues. Route any validated critical incident through the existing operational process; do not wait for the SEO timetable. |
| Days 11–30 | Engineering + content: repair confirmed image/metadata issues and prioritised performance bottlenecks. | Tested fixes; comparable lab settings; documented canonical/redirect choices. | Confirm technical improvement and absence of funnel/accessibility regressions before wider rollout. |
| Days 21–45 | SEO + content: pilot relevant non-brand clusters, starting with validated food-box intent. | Search-result review; product-fit assessment; query-to-page map; limited content pilot. | Expand only if qualified traffic and subscription signals support the cost of production. |
| Days 15–45 | Commercial analytics + growth: design promotion or value-message test if data access and volume permit. | Eligibility criteria; comparable control; power/MDE calculation; cost definition; observation window. | Do not select a 30% offer simply because it appeared in the original assignment. Select test arms using economics and commercial constraints. |
| Days 46–60 | Cross-functional review: assess technical delivery, early search results and test readiness/results. | Evidence update, unresolved questions and continue/adjust/stop recommendation. | Extend the observation window for delayed SEO or retention outcomes; do not present early indicators as sustained uplift. |

This sequence brings measurement and performance diagnosis forward rather than waiting until after acquisition expansion. It keeps small, reversible improvements moving while higher-consequence decisions await stronger evidence.

## Measurement definitions

| Objective | Metric and denominator | Baseline / target treatment | Interpretation and review |
|---|---|---|---|
| Reach relevant new search demand | Non-brand clicks / classified query clicks in a fixed Search Console extract; also absolute non-brand clicks and unknown-query coverage | Establish a fresh baseline. Historical 16% is a vendor traffic estimate and is not directly interchangeable with Search Console clicks. | Share can rise when brand demand falls. Inspect absolute volumes, position, device, seasonality and conversions together. |
| Turn discovery into value | Eligible organic landing sessions reaching subscription / eligible organic landing sessions, using a consistent attribution window | Baseline and meaningful change defined before testing | A change in traffic or CTR alone is not incremental revenue. Distinguish attributed outcomes from causal uplift. |
| Improve user experience | Field p75 LCP, INP and CLS, segmented by device where sufficient data exist; controlled lab LCP/TBT for diagnosis | Use documented quality criteria, with lab and field results reported separately; see [web.dev](https://web.dev/articles/inp). | A lab TBT improvement cannot establish a field INP pass. Preserve form completion and accessibility guardrails. |
| Resolve confirmed technical defects | Open and resolved instances by issue type within the same crawl scope; manual verification of key URLs | Baseline from a new consistent crawl, not a promised Site Health score | A higher vendor score is supporting evidence; verify the underlying fix and indexing/journey effects. |
| Evaluate promotion economics | Fixed-horizon contribution per eligible customer = net revenue minus agreed variable costs and acquisition cost, divided by eligible customers | Use a common observation horizon and denominator across comparable test arms | Discounted net revenue already includes the discount; do not subtract it twice. Predefine refund, fulfilment and cost allocation treatment. This is not lifetime value unless a validated lifetime model is used. |
| Assess retention | Customers placing a qualifying repeat order within the agreed window / original eligible cohort | Cohorts must have equal opportunity to mature; define pause/cancellation treatment | Compare uncertainty and contribution alongside repeat ordering; offer redemption alone does not establish profitability. |
| Monitor experience | Verified affected deliveries / total eligible deliveries over the same period, with severity recorded separately | Define from operational baselines and risk policy | Public complaint counts have no shipment denominator. A low aggregate rate can conceal a serious incident. |

## Stop, adjust or expand

Numeric triggers must be calibrated from baseline variation, sample size, business tolerance and severity. The original 15% redemption and 5% fulfilment-error figures are not retained as validated operating thresholds.

- **Expand** a commercial pilot only when its predeclared contribution objective is supported with appropriate uncertainty and guardrails are satisfied.
- **Adjust or extend** when the estimate is inconclusive or the cohort has not matured.
- **Pause or stop** under the agreed harm/incident policy or when the relevant commercial guardrail is breached.
- **Reconsider the hypothesis** when evidence contradicts it; profitable discount-acquired cohorts would weaken the original dependency concern.

No numeric uplift, minimum sample size or optimal discount level can responsibly be supplied without the missing baseline and cost data.
