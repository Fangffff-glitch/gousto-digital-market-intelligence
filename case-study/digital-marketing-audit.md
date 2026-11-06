# Digital marketing audit

**Research period: May 2026.** This audit examines Gousto’s historical search visibility, competitive position and website experience. Later interpretation changes are documented in the revision log. Evidence IDs refer to the [register](../evidence/evidence-register.csv).

## 1. Competitive position: translate scale into choices

The comparison screenshot in Appendix A, Figure A3 displays **12 May 2026, UK, desktop**. These are SEMrush estimates, not first-party analytics or customer counts.

| Brand | Authority Score | Estimated organic traffic | Organic keywords | Non-branded share |
|---|---:|---:|---:|---:|
| Gousto | 52 | 409,600 | 37,700 | 16% |
| HelloFresh | 58 | 767,300 | 74,100 | 38% |
| Mindful Chef | 42 | 47,900 | 8,000 | 27% |
| Prep Kitchen | 44 | 60,700 | 6,500 | 40% |

**E01–E02.** Gousto's non-branded share was 22 percentage points below HelloFresh, 11 below Mindful Chef and 24 below Prep Kitchen. Shares alone do not measure absolute reach: applying the rounded shares to the same comparison estimates gives approximately 65.5K non-branded traffic for Gousto, versus 12.9K for Mindful Chef and 24.3K for Prep Kitchen. These derived values are approximate and are not unique visitors or incremental acquisitions.

| Comparison | Commercial implication | Practical response | What would validate it? |
|---|---|---|---|
| HelloFresh: larger estimated keyword footprint and traffic | Matching the whole footprint could spread content resources too thinly. More visibility does not establish better conversion. | Select a small number of relevant category clusters before expanding to broad recipe traffic. | Query-level rankings, content gaps, qualified visits and subscription outcomes. |
| Mindful Chef: smaller total reach but higher non-branded share | A focused brand can be visible for specific needs; a higher share alone does not prove superior acquisition efficiency. | Examine whether relevant recipe-box and dietary-intent pages answer needs Gousto can actually serve. | Search-result review, product availability and conversion by landing-page/query cluster. |
| Prep Kitchen: higher non-branded share with a prepared-meal context in the original analysis | Some apparent keyword opportunities may attract people seeking ready-to-eat meals rather than ingredients to cook. | Validate intent before targeting meal-prep searches; explain preparation requirements clearly. | Search results, user expectations, qualified enquiry/subscription rate and reasons for abandonment. |

This extends the original competitor description into resource allocation and validation choices. Competitor positioning above follows the coursework context; it is not a November 2026 market refresh.

## 2. Keyword opportunity: fit before volume

The original Table 4 proposed the following terms. Their volume, difficulty and commercial-intent classifications are retained as **coursework-reported figures**; the exact keyword-level exports were not recovered in this review (E03).

| Keyword | Monthly volume estimate | KD | Revised priority and reasoning |
|---|---:|---:|---|
| food boxes | 3,600 | 24 | Validate first: lower reported difficulty, but broad intent could include non-recipe products. |
| food box delivery | 1,300 | 41 | Validate first: delivery intent may fit the offer if search results support a recipe-box interpretation. |
| meal prep services | 4,400 | 51 | Secondary: confirm whether users expect prepared meals; commercial classification is not proof of willingness to subscribe. |
| meal prep delivery | 2,900 | 60 | Defer until intent and content effort are understood. |
| meal prep companies | 1,300 | 59 | Defer: potentially useful comparison intent, but substantial relevance and competition uncertainty. |

The sum is **13,500 estimated searches**, not 13,500 distinct prospects or addressable customers. Queries can overlap. KD 51–60 is not automatically an easy opportunity; no first-page ranking or profit is promised.

Before production, review the current search results, map each candidate to an existing or proposed page, check product fit and estimate effort. Retain informational content where it supports a useful journey rather than assuming informational queries have no commercial value.

## 3. Technical audit: prioritise verified issues

Appendix B shows a mobile crawl updated **12 May 2026**, with JavaScript rendering disabled, covering **100 pages**. It reports 73% Site Health, 28 error instances and 1,156 warning instances (E04). Counts are not unique affected pages, financial losses or proof of crawl-budget harm. The 92% comparator is labelled “Top-10% websites” in the tool, not a meal-kit industry benchmark.

| Retained issue | Count in screenshot | Revised response |
|---|---:|---|
| Duplicate content | 4 pages | Inspect URL purpose and indexation before choosing canonicalisation or redirects. |
| Duplicate titles | 8 issues | Confirm page differences and create descriptive titles; duplication alone does not establish keyword cannibalisation. |
| Duplicate meta descriptions | 10 pages | Write distinct summaries for relevant pages, then monitor query/page CTR with position and device context. |
| Broken internal images | 6 issues | Confirm affected assets and repair them, prioritising commercial journeys. |
| Missing alt attributes | 460 image instances | Distinguish informative, functional and decorative images; use meaningful alternatives or empty alt text as appropriate. |

**E05.** These are a sampled remediation queue. Duplicate content is not inherently a spam violation; canonicalisation depends on the URL relationship ([Google guidance](https://developers.google.com/search/docs/crawling-indexing/canonicalization)). Decorative images should generally have an empty alt attribute, rather than added keyword text ([W3C guidance](https://www.w3.org/WAI/tutorials/images/decorative/)).

## 4. Performance: separate lab signals from actual outcomes

Appendix B7 records the following mobile Lighthouse-based results (E06):

| Page | LCP, seconds | TBT, ms | CLS |
|---|---:|---:|---:|
| Homepage | 20.72 | 1,616 | 0.000 |
| Menu and plans | 19.97 | 981 | 0.000 |
| Box prices | 13.36 | 1,288 | 0.001 |
| Student discount | 8.10 | 1,306 | 0.030 |
| Cookie policy | 2.25 | 34 | 0.000 |

The original report transcribed pricing CLS as 0.01; the screenshot shows **0.001**. Of ten sampled URLs, one was unavailable for measurement; the CLS panel shows nine good results and one unavailable result, rather than ten measured passes.

These readings justify reproducing performance problems on important pages. They do not prove a specific bounce rate, lost revenue, ranking decline or cause. The original warning panel supplies leads about JavaScript/CSS; a performance trace is still needed before attributing the LCP delay to images or scripts.

TBT is a lab diagnostic, not a measured field INP result. The revised measurement plan uses LCP, INP and CLS for field assessment where data are available, with TBT retained for controlled lab comparison ([web.dev](https://web.dev/articles/inp)).

## 5. Data reconciliation

The separate domain overview displays **7 May 2026** and reports 412.6K organic traffic and 123.6K backlinks. The 12 May competitor comparison reports 409.6K and 123.9K. Both readings are retained with their snapshot dates; the comparison table consistently uses the latter. No growth or decline is inferred from these two snapshots alone.

The original comparison's “Traffic Cost” figures are labelled **Paid Traffic Cost** in Figure A3. They are excluded from the headline table because they are neither actual advertising expenditure nor acquisition cost.

The next step is the [action and measurement plan](../recommendations/action-plan.md), which connects technical and content work to specific decision gates.
