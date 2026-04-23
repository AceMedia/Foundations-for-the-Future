# Social Care and End-of-Life Costings

This appendix turns the end-of-life and dementia care proposal into a budget model. It does not pretend that every figure is final. The aim is to separate what is already known from what needs Treasury, DHSC, NHS, and local-authority modelling.

The linked policy chapter is [end-of-life-and-dementia-care.md](../health/end-of-life-and-dementia-care.md).

---

## What we are trying to fund

The core package is the **Dementia and End-of-Life Care Guarantee**:

- publicly fund the dementia premium in care homes;
- restore a lifetime cap on eligible personal care costs;
- raise the Personal Dignity Allowance;
- expand hospice-at-home and care-home palliative support;
- protect ordinary assets more generously;
- create an End-of-Life Support Passport;
- guarantee food, warmth, adaptations, and home safety;
- build a community care workforce around the person.

This should be treated as a **fairness and risk-pooling reform**, not a simple savings programme. Some costs are new public costs because the state is taking pressure off families. Some costs should be offset by lower emergency admissions, fewer delayed discharges, less crisis social care, and reduced administrative dispute.

---

## Current baseline pressures

| Pressure | Current evidence | Why it matters |
|---|---:|---|
| Care home fees | England local authority average residential/nursing care cost in 2024/25: **£1,185.55/week**, around **£61,649/year** | Ordinary savings can disappear quickly |
| Self-funder fees | Recent sector data: residential dementia care around **£1,343/week** and nursing dementia care around **£1,564/week** | Self-funders face much higher bills than many council-funded rates |
| Dementia burden | Alzheimer's Society estimates dementia costs the UK **£42bn/year**, rising to **£90bn by 2040** | Dementia is a system-wide cost, not a private family problem |
| Dementia in care homes | Alzheimer's Society says around **70%** of older-age residential care residents in England have dementia | Care-home reform is largely dementia reform |
| Family burden | Alzheimer's Society estimates **63%** of dementia costs are borne by people with dementia and families | Current policy shifts medical-looking costs onto households |
| End-of-life public spend | Nuffield Trust / Marie Curie estimate at least **£22bn** public expenditure on people in their final year of life in 2022 | Money is already being spent, often too late or in the wrong setting |
| Final-year hospital spend | Nuffield Trust reported hospital care dominates final-year health spending, with emergency care a major component | Community care may reduce avoidable hospital pressure |
| Older people's direct contributions | DHSC finance data shows client contributions from long-term care for those aged 65 and over reached **£3.5bn** in 2024/25 | A large part of the burden is already being carried directly by older people |
| Fuel poverty at end of life | Marie Curie/Loughborough estimate **128,000** people died in fuel poverty in the UK in 2023 | Warmth is an end-of-life health issue |
| Workforce pressure | Skills for Care data for 2024/25 reported about **111,000** adult social care vacancies in England | Delivery depends on workforce, not only funding |
| Existing vice-duty scale | OBR 2025/26 forecasts: alcohol duties **£11.9bn**, tobacco duties **£8bn**, betting/gaming duties **£4bn** | A visible earmark could fund part of the guarantee |

---

## Planning cohorts

The appendix needs working cohort sizes, even if they remain approximate. The safest way to do this is to use published England activity data and then show scenario bands rather than pretending we know one exact eligible number.

Useful anchors:

| Cohort anchor | Current official scale | How to use it |
|---|---:|---|
| People aged 65 and over receiving long-term support in England on 31 December 2025 | **403,000** | Upper boundary for older long-term support cohort |
| People in residential care homes on 31 December 2025 | **139,000** | Current residential long-term support count |
| People in nursing homes on 31 December 2025 | **55,000** | Current nursing long-term support count |
| Share of residential long-term support recipients aged 65+ | **77%** | Use to estimate older residential cohort |
| Share of nursing long-term support recipients aged 65+ | **88%** | Use to estimate older nursing cohort |
| Deaths registered in England in 2024 | **531,954** | Useful upper boundary for annual end-of-life trigger cohorts |
| Deaths registered in England and Wales in 2024 | **568,613** | Wider annual mortality context |

Using the age shares above as an inference from the published data:

- older residential long-term support cohort in England is roughly **107,000**;
- older nursing long-term support cohort in England is roughly **48,000**;
- combined older residential and nursing cohort is roughly **155,000**.

That last figure is an inference from official sources, not a direct published count. It is still a useful planning anchor for this appendix.

---

## Cost blocks to model

### 1. Dementia Care Supplement

The policy chapter proposes that the state should publicly fund the extra dementia premium above standard care costs.

Known inputs:

- dementia care is materially more expensive than standard care;
- Alzheimer's Society has estimated dementia care is around **15%** more expensive to deliver than standard social care;
- around **70%** of older-age residential care residents in England have dementia.

Illustrative formula:

```text
Annual cost = eligible dementia residents x standard annual care cost x dementia premium percentage
```

Illustrative per-person scale:

| Baseline annual cost | 15% dementia premium | Policy meaning |
|---:|---:|---|
| £61,649/year | £9,247/year | Based on England local authority average weekly care cost |
| £69,836/year | £10,475/year | Based on £1,343/week residential dementia self-funder figure |
| £81,328/year | £12,199/year | Based on £1,564/week nursing dementia self-funder figure |

Working England cohort logic:

- around **70%** of older-age residential care residents in England are estimated to have dementia;
- applying published age shares to current residential and nursing counts implies around **155,000** older people in care-home settings funded or arranged through the system at a point in time;
- because the 70% figure relates to older-age residential care residents rather than every nursing resident, the safest planning range is **90,000 to 120,000** eligible residents rather than one exact number.

Illustrative England planning range:

| Eligible residents | Using £9,247 supplement | Using £10,475 supplement |
|---:|---:|---:|
| 90,000 | £832m | £943m |
| 105,000 | £971m | £1.10bn |
| 120,000 | £1.11bn | £1.26bn |

Budget treatment:

- **Direct public cost:** reasonable England planning range is roughly **£0.8bn to £1.3bn** depending on cohort definition and whether the supplement is benchmarked to local-authority or self-funder costs.
- **Family saving:** potentially large, especially for self-funders.
- **System benefit:** more realistic funding may reduce cross-subsidy, provider instability, and disputes.

### 2. Lifetime care cap and means-test reform

The previous adult social care charging reforms included an **£86,000** lifetime cap on eligible personal care costs. Government analysis estimated steady-state public cost at about **£3.7bn in 2027/28**, including illustrative Barnett consequentials.

This provides a scale marker, not a final recommendation.

Options to model:

| Option | Description | Fiscal risk | Fairness impact |
|---|---|---|---|
| Restore previous cap | Bring back £86k cap and more generous means test | Known starting estimate: around £3.7bn steady state | Protects against catastrophic costs |
| Dementia-weighted cap | Count dementia-related assessed care fully and quickly toward the cap | Higher than previous cap if broader costs count | Stronger protection for degenerative illness |
| Terminal/advanced condition fast track | Lower or faster cap for terminal, severe dementia, or advanced frailty | Targeted cost increase | Protects people least able to wait |
| Progressive estate contribution above high threshold | Protect ordinary assets, ask more only from very high-value estates | Can offset some cost | Avoids unlimited inheritance protection for the wealthiest |

Budget treatment:

- **Core cost:** use **£3.7bn** as an initial scale marker.
- **Policy decision:** whether the cap is universal, dementia-weighted, or targeted by condition.
- **Repo planning assumption:** if ministers adopt a more generous dementia-weighted or terminal fast-track design, a sensible working allowance is the published **£3.7bn** scale marker plus an uplift of around **10% to 20%**, implying roughly **£4.1bn to £4.4bn**. That uplift is an inference for planning, not an official costing.
- **Distributional analysis needed:** homeowners, renters, regions, disabled people, surviving spouses, and families with modest estates.

### 3. Personal Dignity Allowance

The current Personal Expenses Allowance leaves care-home residents with very limited weekly money for personal life. The policy proposes a higher **Personal Dignity Allowance**.

The current residential and nursing long-term support population in England is close to **200,000** people at a point in time, so that is a more useful central planning assumption than the earlier 100,000 example.

Illustrative options:

| Increase per resident | Annual cost per eligible resident | If applied to 150,000 people | If applied to 200,000 people | If applied to 250,000 people |
|---:|---:|---:|---:|---:|
| +£20/week | £1,040/year | £156m/year | £208m/year | £260m/year |
| +£35/week | £1,820/year | £273m/year | £364m/year | £455m/year |
| +£50/week | £2,600/year | £390m/year | £520m/year | £650m/year |

Budget treatment:

- **Direct cost:** modest compared with care-cap reform.
- **Purpose:** preserve humanity, not generate savings.
- **Possible offset:** lower loneliness and distress, but do not count this as a hard saving without evidence.

### 4. Hospice-at-home and palliative support

The final year of life already carries high public expenditure. The aim is to shift more support out of avoidable emergency hospital use and into planned community care.

Cost blocks:

- 24/7 palliative advice lines;
- hospice-at-home teams;
- community nursing and pharmacy delivery;
- anticipatory prescribing;
- respite and sitting services;
- palliative support in care homes;
- bereavement support.

Savings mechanisms:

- fewer avoidable emergency admissions;
- shorter hospital stays;
- fewer delayed discharges;
- fewer ambulance callouts caused by unsupported symptom crises;
- more deaths in preferred place of care where safe and wanted.

Budget treatment:

| Item | Cost/saving status |
|---|---|
| New community and hospice capacity | Direct cost, should be funded upfront |
| Avoided emergency hospital use | Potential offset, model cautiously |
| Avoided delayed discharge | Potential offset, linked to housing/adaptations and social care |
| Better family experience | Social value, not a simple cashable saving |

Planning allowance:

- Nuffield Trust estimates the public purse currently funds **£414m** of services provided by independent hospices.
- Because the reform here is wider than hospice charities alone and also covers advice lines, community support, care-home palliative support, and pharmacy/logistics, a practical gross planning range is **£0.25bn to £0.75bn** for a meaningful expansion.

### 5. Food, warmth, adaptations, and home safety

These are small-cost interventions compared with hospital admission or residential care.

Policy components:

- end-of-life energy social tariff;
- tailored meals through bulk food procurement;
- rapid adaptations such as rails, ramps, key safes, commodes, bed moves, and wet-room support;
- heating, damp, mould, and trip-hazard repairs;
- equipment delivery, recycling, and maintenance;
- emergency carer support.

Illustrative model:

| Support package | Annual unit cost | 50,000 people | 100,000 people | 250,000 people |
|---|---:|---:|---:|---:|
| Light support | £500 | £25m | £50m | £125m |
| Standard support | £1,500 | £75m | £150m | £375m |
| Intensive support | £3,000 | £150m | £300m | £750m |

Budget treatment:

- **Direct cost:** likely manageable relative to hospital and care-home costs.
- **Offsets:** avoided admissions, reduced delayed discharge, fewer crisis care packages.
- **Coverage sense-check:** 50,000 people is under 10% of annual deaths in England; 100,000 is under 20%; 250,000 would be a much broader frailty and end-of-life prevention package rather than a terminal-only scheme.
- **Linked docs:** [bulk food procurement](../welfare/bulk-food-procurement.md), [housing policy](../housing/housing-policy.md), [welfare reform](../welfare/welfare-and-wellbeing-reform.md).

### 6. End-of-Life Support Passport

The passport is mainly an administration and digital coordination reform.

Likely cost blocks:

- digital service build;
- integration with NHS, local authorities, DWP, energy support, Blue Badge, hospice, and equipment services;
- case coordination;
- advice and advocacy.

Likely benefits:

- fewer repeated assessments;
- faster benefit access;
- less unpaid carer stress;
- reduced local authority dispute and chasing;
- earlier activation of support packages.

Budget treatment:

- **One-off build assumption for repo planning:** **£25m to £75m**.
- **Ongoing coordination assumption:** roughly **£250 to £500** per active case, depending on how much advocacy and case-management is bundled in.
- **Savings:** administrative and crisis avoidance, but model conservatively.

Illustrative annual costings:

| Active cohort | £250 per person + £25m build | £500 per person + £50m build |
|---:|---:|---:|
| 50,000 people | £38m | £75m |
| 100,000 people | £50m | £100m |
| 250,000 people | £88m | £175m |

---

## Funding scenarios

Existing vice duties provide a plausible partial funding stream if a share is visibly earmarked for health and care. In this framework, vice-tax receipts should go first to a **Health and Care Betterment Fund** rather than being split with defence or general resilience.

OBR 2025/26 forecasts used in the policy chapter:

| Duty stream | Forecast receipts |
|---|---:|
| Alcohol duties | £11.9bn |
| Tobacco duties | £8.0bn |
| Betting and gaming duties | £4.0bn |
| **Combined** | **£23.9bn** |

Illustrative earmarks:

| Earmark share | Annual receipts | What it could cover |
|---:|---:|---|
| 5% | £1.2bn | Food/warmth/adaptations, dignity allowance, passport, some palliative support |
| 10% | £2.4bn | Major contribution toward dementia supplement and community end-of-life support |
| 15% | £3.6bn | Close to previous care-cap reform scale marker |
| 20% | £4.8bn | Could fund care-cap reform plus wider dignity supports, depending on design |

Important treatment:

- these are **earmarked receipts**, not efficiency savings;
- they should not be counted inside the core £3-6bn savings range;
- future regulated adult-use markets should remain **TBD** until legal design and tax rates are specified;
- prescribed medical products should be low- or zero-duty where clinically justified.
- public-service rehabilitation can reduce some delivery costs through supervised food, equipment, laundry, garden, and maintenance support, but it should not be treated as a primary funding stream.

---

## Potential offsets and avoided costs

The reform should not be sold as "free". It should be sold as fairer public insurance with some likely offsets.

The strongest published offset anchor is hospital spending in the final year of life. Nuffield Trust estimates:

- **£9.6bn** of UK health spending for people in the last year of life was hospital care;
- **£6.6bn** of that was emergency hospital care;
- **£8.6bn** was hospital inpatient care;
- people in the last year of life account for nearly **10%** of all hospital costs.

That does not mean these amounts are cashable on demand. But it does justify cautious scenario-testing.

Illustrative UK-wide offset scenarios:

| Offset scenario | Saving if emergency hospital spend falls | Interpretation |
|---|---:|---|
| 2% reduction in emergency hospital spend | £132m | Very cautious system effect |
| 5% reduction in emergency hospital spend | £330m | Plausible medium-run offset if community support materially improves |
| 10% reduction in emergency hospital spend | £660m | Strong effect, should not be assumed in central case |

Illustrative inpatient shift scenarios:

| Offset scenario | Saving if inpatient spend falls | Interpretation |
|---|---:|---|
| 1% reduction in inpatient spend | £86m | Very cautious |
| 3% reduction in inpatient spend | £258m | Meaningful but still partial |
| 5% reduction in inpatient spend | £430m | Strong system effect |

| Offset route | Why plausible | Caution |
|---|---|---|
| Fewer avoidable emergency admissions | Better palliative care, symptom control, food, warmth, and carer support | Needs NHS activity modelling |
| Reduced delayed discharge | Faster adaptations, equipment, care packages, and home safety | Savings may be capacity-releasing rather than cashable |
| Less crisis social care | Earlier support prevents emergency placements | Depends on local authority implementation |
| Fewer disputes and assessments | Clearer passport and national rules reduce churn | Admin savings likely modest |
| Improved carer stability | Carers supported earlier are less likely to collapse into crisis | Social value high, cash savings harder |
| Workforce retention | Better training and career pathways reduce churn | Requires pay and conditions reform too |

---

## Indicative package totals

The spending side is clearer if the package is shown in two layers:

1. a **dignity and community support layer**; and
2. a **full insurance layer** that also restores a care cap.

### Dignity and community support layer

Illustrative gross package:

| Element | Low | Core | Higher |
|---|---:|---:|---:|
| Dementia Care Supplement | £0.83bn | £0.97bn | £1.26bn |
| Personal Dignity Allowance | £0.27bn | £0.36bn | £0.46bn |
| Hospice-at-home and palliative expansion | £0.25bn | £0.50bn | £0.75bn |
| Food, warmth, adaptations, and home safety | £0.08bn | £0.15bn | £0.38bn |
| End-of-Life Support Passport | £0.04bn | £0.10bn | £0.18bn |
| **Gross total** | **£1.47bn** | **£2.08bn** | **£3.03bn** |

Interpretation:

- a **10% vice-duty earmark** at around **£2.4bn** could broadly fund the core dignity-and-community layer;
- a **15% earmark** at around **£3.6bn** could fund a stronger version of that layer with some headroom.

### Full insurance layer including care-cap reform

If the package also restores a lifetime cap and more generous means test:

| Package | Add official care-cap scale marker | Add more generous dementia-weighted / terminal-fast-track planning allowance |
|---|---:|---:|
| Low dignity package + cap | £5.17bn | £5.57bn to £5.87bn |
| Core dignity package + cap | £5.78bn | £6.18bn to £6.48bn |
| Higher dignity package + cap | £6.73bn | £7.13bn to £7.43bn |

This is the more honest fiscal picture:

- **10% earmark** can carry a serious share of the package, but not the full insurance layer;
- **15% earmark** can fund most of the dignity layer and make a major contribution to cap reform;
- **20% earmark** at around **£4.8bn** still likely needs top-up funding from general taxation or mature avoided-cost savings if ministers want a fuller cap-and-dignity settlement.

---

## Distributional test

The proposal should be judged against five household types:

| Household | Current risk | Reform test |
|---|---|---|
| Low-income renter | Little wealth but high risk of poor housing, fuel poverty, and weak support | Does the passport trigger practical help quickly? |
| Modest homeowner | May lose lifetime savings or home equity to care fees | Does the cap protect ordinary assets? |
| Surviving spouse or dependent | Fear of forced sale or loss of security | Are home and income protections strong enough? |
| Family carer | Risk of burnout, poverty, and work loss | Is respite, food, heat, and income support automatic? |
| High-value estate | Can contribute more without hardship | Is there a progressive contribution above a high threshold? |

This matters because the policy must avoid two unfair outcomes at once:

- stripping ordinary families of everything they built;
- asking young workers and renters to fully protect unlimited wealth for the richest estates.

---

## Suggested budget presentation

The main [summary-of-savings.md](./summary-of-savings.md) file should keep social care reform separate from the existing direct savings total until modelling is complete.

Suggested wording:

> Social care and end-of-life reform is a fairness and insurance package with potential avoided health and crisis costs. It should be shown as a separately funded commitment, partly offset by earmarked betterment receipts and cautious avoided-cost modelling, rather than folded into the current £3-6bn savings range.

Suggested headline line:

| Area | Mechanism | Budget treatment |
|---|---|---|
| Social care and end-of-life dignity | Dementia supplement, care cap, dignity allowance, hospice-at-home, food/warmth/adaptations, support passport | Direct cost TBD; funding via 10-15% vice-duty earmark plus avoided-cost modelling |

---

## Next modelling tasks

- Refine dementia cohort sizing by nation and by residential versus nursing setting.
- Test whether the Dementia Care Supplement should follow local-authority rates, self-funder rates, or a blended national tariff.
- Replace the current care-cap planning uplifts with official updated Treasury/DHSC costings if reforms are revived.
- Build an England-specific avoided-hospital-use model rather than relying on UK-wide Nuffield anchors.
- Separate cashable savings from capacity-releasing benefits in discharge and emergency-care modelling.
- Refine support-passport setup and running costs against an actual cross-government service design.
- Test 5%, 10%, 15%, and 20% vice-duty earmark scenarios against the combined package totals.
- Avoid double-counting savings already listed under housing, health, and welfare.

---

## References

- Department of Health and Social Care (2025). *Adult social care finance report, England: 2024 to 2025*. https://www.gov.uk/government/statistics/adult-social-care-finance-report-england-2024-to-2025/adult-social-care-finance-report-england-2024-to-2025
- Department of Health and Social Care (2025). *Adult social care activity report 2024 to 2025: commentary*. https://www.gov.uk/government/statistics/adult-social-care-activity-report-england-2024-to-2025/adult-social-care-activity-report-2024-to-2025-commentary
- Department of Health and Social Care (2026). *Adult social care client level data, England: quarterly update to December 2025*. https://www.gov.uk/government/statistics/adult-social-care-client-level-data-england-quarterly-update-to-december-2025/adult-social-care-client-level-data-england-quarterly-update-to-december-2025
- Department of Health and Social Care (2024). *Adult social care charging reform: analysis*. https://www.gov.uk/government/publications/build-back-better-our-plan-for-health-and-social-care/adult-social-care-charging-reform-analysis
- Alzheimer's Society. *What we think about social care*. https://www.alzheimers.org.uk/what-we-do/policy-and-influencing/our-position-key-dementia-challenges/social-care
- Alzheimer's Society. *What are the costs of dementia diagnosis and care in the UK?* https://www.alzheimers.org.uk/about-us/policy-and-influencing/dementia-scale-impact-numbers
- Nuffield Trust (2024). *Public expenditure in the last year of life*. https://www.nuffieldtrust.org.uk/research/public-expenditure-in-the-last-year-of-life
- Office for National Statistics (2025). *Death registration summary statistics, England and Wales: 2024*. https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/bulletins/deathregistrationsummarystatisticsenglandandwales/2024
- Marie Curie (2024). *Dying in Poverty 2024*. https://www.mariecurie.org.uk/media/press-releases/dying-in-poverty-2024/385013
- Loughborough University / Centre for Research in Social Policy (2024). *Fuel poverty and terminal illness*. https://www.lboro.ac.uk/research/crsp/our-research/fuel-poverty-and-terminal-illness/
- Skills for Care / Department of Health and Social Care (2025). *Care workforce pathway for adult social care*. https://www.gov.uk/government/publications/care-workforce-pathway-for-adult-social-care/
- Care Quality Commission (2025). *The state of health care and adult social care in England 2024/25 - Adult social care*. https://www.cqc.org.uk/publications/major-report/state-care/2024-2025/access/asc
- Office for Budget Responsibility (2026). *Alcohol duties*. https://obr.uk/forecasts-in-depth/tax-by-tax-spend-by-spend/alcohol-duties/
- Office for Budget Responsibility (2026). *Tobacco duties*. https://obr.uk/forecasts-in-depth/tax-by-tax-spend-by-spend/tobacco-duties/
- Office for Budget Responsibility (2026). *Betting and gaming duties*. https://obr.uk/forecasts-in-depth/tax-by-tax-spend-by-spend/betting-gaming-duties/
