# 10 High-Impact Projects That AI Recently Made Doable for One Student

*Researched October 2026. A companion to `med-school-bullet-ideas.md`, with a higher bar: real, measurable impact and real scope, where AI now does work that used to need paid professionals or months of research-assistant labor. Numbers in [brackets] in the sample bullets are targets, not claims.*

---

## The pattern behind every idea here

The biggest health-impact opportunities open to a student fall into two buckets.

**1. Entitlement gaps.** People already have a legal right to money or care but never claim it, because claiming takes expert paperwork:
- Medicare Advantage insurers denied 4.1M prior-authorization requests in 2024. Only **11.5%** were appealed, but **80.7%** of appeals won.
- In ACA Marketplace plans, **fewer than 1%** of denied claims are appealed.
- Fewer than **one-third** of patients who qualify for hospital charity care actually get their bills forgiven (Dollar For's research).
- Simply helping people fill out SNAP applications **tripled** enrollment in a randomized trial. The nonprofit that did this at scale (Benefits Data Trust, serving 120,000 people a year) **shut down in August 2024**.

What blocked people was the expert paperwork: appeal letters citing medical evidence, 40-page hospital financial-assistance policies, document checklists. **AI now drafts that work in minutes.** A trained student volunteer with an AI assistant can do work that used to require a paid patient advocate.

**2. Accountability at scale.** Some problems only change when someone documents them across thousands of records, such as court filings, insurer directories or trial registries. That used to take a research team months. Now one student can build an AI pipeline that reads and codes the records, then hand-check a sample. There's precedent for this working:
- A news investigation of the University of Virginia's lawsuits against patients led UVA to change its policy, and Virginia Commonwealth University stopped suing patients.
- A Duke Law and NC Treasurer analysis of court records found **7,500+ patients sued**. Atrium Health stopped suing patients, and North Carolina's 2024 Medicaid incentive deal went on to erase **more than $6.5B** in medical debt.

**What makes it "great" rather than "good":** pick **one flagship**, recruit a team, and run it for 6–12 months. "I built X, trained 30 volunteers, and recovered $500K for 200 patients" is a story admissions committees remember.

---

## Scorecard

| # | Project | Impact type | What AI unlocks | Barrier to start | Scale ceiling |
|---|---------|-------------|-----------------|------------------|---------------|
| 1 | Charity-care engine (Dollar For chapter) | $ forgiven per patient | Parsing every hospital's assistance policy; filling out applications | Low | Statewide |
| 2 | Insurance-denial appeals clinic | Care obtained, $ restored | Evidence-cited appeal letters | Low–Med | Regional |
| 3 | Medical-debt lawsuit investigation | Policy change | Coding thousands of court filings | Med | Statewide |
| 4 | AI-assisted benefits enrollment (Medicaid/SNAP) | Coverage kept, $ benefits | Document checklists, form pre-fill, translation | Low | Regional |
| 5 | "Ghost network" directory audit | Regulatory action | Scraping and matching insurer directories | Med | Statewide |
| 6 | Clinical-trial navigator | Trial access | Reading trial eligibility criteria (TrialGPT-style) | Med | National (one disease community) |
| 7 | Unreported-trial-results audit at your university | Results made public | Matching trial registrations to publications | Low | Institutional |
| 8 | AI scribe rollout at a free clinic | More patients seen | Documentation | Low (tool is free to free clinics) | One clinic → network |
| 9 | Accessible public-health information (ADA deadline) | Access for disabled residents | Image descriptions, document tagging, plain language | Low | County |
| 10 | AED registry + gap map | Cardiac-arrest survival | Finding unregistered AEDs, coverage-gap analysis, outreach | Low | City |

---

## 1. Charity-care engine: start a Dollar For chapter, then add AI

**The gap.**
- Federal tax law (IRS §501(r)) requires every nonprofit hospital to offer a written financial-assistance policy (often called charity care), publish a plain-language summary, translate it for large non-English-speaking populations, and try to find eligible patients before suing them.
- In practice, Dollar For's research found that fewer than a third of eligible patients get their bills forgiven.
- The Lown Institute estimates nonprofit hospitals' "fair share" shortfall at **$11.5B a year**: what they spend on their communities falls that far short of what they receive in tax breaks.
- Dollar For has helped erase tens of millions of dollars in bills (reported totals vary by date, from about $38M to $157M), and student chapters already exist. A University of Texas chapter has about 40 volunteers.

**What AI unlocks.** Every hospital's policy is a different, dense PDF. AI can turn all of a state's policies into one structured table:
- income cutoffs and asset tests
- whether the hospital grants assistance automatically (presumptive eligibility) and how far back it applies
- required documents and where to send applications

From that table you can build a plain-language eligibility screener in several languages. AI can also pre-fill each hospital's application from a patient's bill and pay stubs, which used to be hours of a specialist's time.

**What you do.**
- Start or join a Dollar For chapter. Partnering is better than building a competitor.
- Build the state policy database and give it to Dollar For and local free clinics.
- Train volunteers, and personally sit with patients to help them apply.

**Sample bullet.**
> Founded [University]'s Dollar For chapter and built an AI-assisted database of financial-assistance policies for all [64] nonprofit hospitals in [state]; led [35] volunteers who helped [180] patients secure $[740,000] in forgiven hospital bills.

**Honest note.** This is different from buying old debt in bulk to forgive it. Randomized trials of that approach found no average health or financial benefit. Charity care stops *current* bills that hospitals are legally required to forgive, often before they turn into collections or lawsuits.

---

## 2. Insurance-denial appeals clinic

**The gap.**
- **Medicare Advantage (2024):** 4.1M prior-authorization denials, only 11.5% appealed, 80.7% overturned on appeal.
- **ACA Marketplace (2024):** 19% of in-network claims denied. In 2023, fewer than 1% of denied claims were appealed.

**What AI unlocks.** A winning appeal cites the plan's own coverage language, the clinical evidence and the specific medical-necessity criteria. Writing one used to take a professional advocate. Free AI tools now draft them; Counterforce Health's founder reports 60–75% success, but those are the company's own unverified figures, and Fight Health Insurance is a similar free tool. A student volunteer can now run the whole workflow: collect the denial letter, draft the appeal with AI, get the clinician's letter of medical necessity, file it and follow up.

**What you do.** Partner with a free clinic, a cancer center's financial-navigation office, a rheumatology or endocrinology practice, or a State Health Insurance Assistance Program (SHIP), which counsels Medicare beneficiaries. Medicare open enrollment runs Oct 15 to Dec 7, which is a natural time to recruit SHIP partners. Build a volunteer protocol and track every outcome.

**Sample bullet.**
> Launched a free insurance-denial appeals clinic with [Clinic]; trained [20] volunteers in an AI-assisted, clinician-reviewed workflow that filed [95] appeals, overturning [61] denials and restoring $[410,000] in coverage (imaging, chemotherapy, insulin pumps).

**Watch-outs.**
- Get patient consent and check each AI tool's data handling. Operate under the partner organization.
- You're not a lawyer, so don't promise outcomes.
- The clinician signs the medical-necessity letter, not you.

---

## 3. Medical-debt lawsuit investigation

**The gap.** Hospitals sue patients, including many who qualified for charity care. These cases sit in court records, but nobody tallies them, and tallying them is what has forced change:
- **Virginia:** a news investigation found UVA had sued patients 36,000+ times; UVA then changed its policy, and VCU stopped suing patients.
- **North Carolina:** the Duke Law and Treasurer analysis (7,500+ patients sued, $57M in judgments, a third of it interest and fees) preceded Atrium Health ending lawsuits and the 2024 Medicaid deal that has erased **$6.5B+** in debt for **2.5M+** people.

**What AI unlocks.** Reading and coding tens of thousands of court filings (who sued, how much, whether wages were garnished or liens placed on homes, which zip codes) used to be a research-assistant army. Now it's a pipeline you build and then check by hand on a random sample.

**What you do.**
1. Check whether your state has an online court case search that you're allowed to scrape.
2. Find a health-policy faculty member or a local newsroom to partner with.
3. Build the dataset and compare hospitals' lawsuits with their charity-care obligations.
4. Publish, and brief the state treasurer's office, legislators and hospital boards.

**Sample bullet.**
> Built an AI pipeline that coded [38,000] civil filings in [state], identifying [9,400] hospital lawsuits against patients, [60]% in zip codes where most residents qualify for free care; findings co-published with [newsroom] and cited at a [state legislative] hearing.

**Watch-outs.**
- Report only aggregates; never name individual patients.
- Follow the court website's terms of use.
- Hand-check a random sample to measure the AI's accuracy, and report that number.

---

## 4. AI-assisted benefits enrollment (Medicaid work requirements + SNAP)

**The gap.**
- **Proven method:** in a randomized trial, helping people with their applications tripled SNAP enrollment (from 6% to 18%).
- **Lost capacity:** Benefits Data Trust, which delivered exactly this at scale, closed in August 2024.
- **New deadline:** Medicaid work requirements hit expansion states by **Jan 1, 2027**, with re-checks roughly every six months.
- **History:** in Arkansas's 2018 trial, about 18,000 people lost coverage, mostly from confusion and red tape rather than not working.

**What AI unlocks.** The helper's expertise: the right document checklist for each case, pre-filled forms, explanations in the person's language, and reminders before deadlines. Trained student volunteers with AI assistants can now deliver the application help that was proven in the trial.

**What you do.** Partner with a food bank, a federally qualified health center (FQHC) or legal aid. Train volunteers, staff help sessions, and track who enrolls and who keeps coverage.

**Sample bullet.**
> Co-led a benefits-access team at [Food Bank/FQHC] using AI-assisted document checklists and multilingual guidance; enrolled or retained [260] households in SNAP and Medicaid ahead of the January 2027 work requirements, securing ~$[900K]/yr in benefits.

---

## 5. "Ghost network" directory audit → state regulators

**The gap.** Insurer directories list mental-health providers who can't actually be reached. A Senate Finance Committee audit of Medicare Advantage plans found more than 80% of listed mental-health providers were "ghosts" (unreachable, not in-network, or not taking new patients). A New York Attorney General review found 86%.

**What AI unlocks.** Scraping every insurer's online directory in your state, removing duplicates, matching listings against state license and NPI provider registries, and analyzing the call results. That data work used to be the hard part.

**What you do.** Recruit student callers. Use human callers: under a 2024 FCC ruling, AI-generated voices count as "artificial" voices under federal telemarketing law, so AI-voice calls need consent. Then file a structured complaint with your state's Department of Insurance, ideally with a faculty mentor or an advocacy group (for example, a NAMI state chapter).

**Sample bullet.**
> Audited [1,200] mental-health listings across [5] insurers in [state] using AI-assisted directory matching and [6] student callers; [72]% were unreachable, out-of-network, or not accepting patients; report submitted to the [state] Department of Insurance.

---

## 6. Clinical-trial navigator for one disease community

**The gap.** Only about **8%** of adult cancer patients enroll in trials, and most aren't held back by unwillingness: patients offered a trial agree about 55% of the time (60% among Black patients). Matching people to trials is the bottleneck.

**What AI unlocks.** NIH's TrialGPT (*Nature Communications*, 2024) checked patients against individual eligibility criteria about as accurately as human experts (87%) and cut screening time about 40% in a small pilot. Reading pages of eligibility criteria for each patient used to need a research nurse; now a student can produce first-pass shortlists that a clinician reviews.

**What you do.** Partner with a patient-advocacy organization for one disease (sickle cell, a rare disease, or a specific cancer).
1. Patients share a consented summary of their case.
2. AI checks it against ClinicalTrials.gov.
3. You verify every criterion yourself and write a plain-language shortlist the patient takes to their own physician.
4. You help them contact trial coordinators.

**Sample bullet.**
> Built an AI-assisted clinical-trial navigation service with [Patient Foundation]; screened [140] patient summaries against ClinicalTrials.gov to produce physician-reviewed shortlists; [23] patients contacted trial sites and [9] enrolled.

**Watch-outs.** This is not medical advice; everything goes through the patient's own physician. Collect only the minimum health information you need, with consent.

---

## 7. Find your university's unreported clinical trials

**The gap.** Federal law (FDAAA) requires many trials to post results within 12 months. A Universities Allied for Essential Medicines and TranspariMed report found only **15 of 40** major institutions fully compliant. Trials covered only by NIH policy, rather than FDAAA, aren't tracked at all. Unreported results waste what participants contributed and skew the evidence doctors rely on.

**What AI unlocks.** Matching every trial your institution has registered to a publication or posted result, including fuzzy matches where titles and outcomes don't line up exactly, used to be weeks of manual searching. AI does the first pass and you verify.

**What you do.** Build the audit, share it privately with your university's research-integrity office first, and track how many trials get their results posted.

**Sample bullet.**
> Audited all [310] completed trials sponsored by [University] since 2015 using an AI-assisted registry-to-publication matching pipeline; identified [58] trials with no public results (~[4,100] participants); after presenting to the research office, [37] posted results within six months.

**Why it lands.** Research integrity, respect for research participants, and an outcome you can measure directly. You need public data and persistence, not anyone's permission.

---

## 8. AI scribe rollout at a free clinic

**The gap.** About 1,400 free clinics, many running on $250K a year or less, are seeing record demand, and their volunteer clinicians' time is the bottleneck.

**What AI unlocks.** Doximity offers its HIPAA-compliant ambient AI scribe free to all U.S. free clinics. Evidence on time saved is modest but real:
- A randomized trial at UCLA found about a 10% cut in note-writing time with one tool, and modest burnout improvements with both tools tested.
- Other trials report about 20–30 minutes saved per clinician per day.

**What you do.** Lead the rollout as a quality-improvement project:
- set up a patient-consent workflow
- train the volunteer clinicians
- measure documentation time, patients seen per session, note quality and clinician retention

**Sample bullet.**
> Led rollout of a free, HIPAA-compliant AI scribe for [15] volunteer clinicians at [Free Clinic]; capacity rose from [18] to [22] patients per session; findings presented at [SSRFC].

**Honest note.** The impact only counts if the saved time turns into more patients seen or better volunteer retention, so measure exactly that.

---

## 9. Accessible public-health information before the ADA deadline

**The gap.** A federal disability-rights rule (ADA Title II) requires state and local governments, including health departments and public hospitals, to make their websites and documents meet the WCAG 2.1 AA accessibility standard:
- by **April 26, 2027** if they serve 50,000 or more people
- by **April 26, 2028** for smaller ones (both dates were pushed back a year in April 2026)

Many health departments have hundreds of inaccessible PDFs and forms that screen readers can't read.

**What AI unlocks.** Making a PDF accessible (image descriptions, tagged structure, readable tables, plain language) was slow, specialized work. AI now drafts most of it, and you check it with accessibility-checker tools and screen-reader testing.

**Sample bullet.**
> Partnered with [County] Health Department to make [240] public-health PDFs and forms WCAG 2.1 AA–accessible ahead of the April 2027 ADA deadline, using AI-drafted image descriptions and tagging verified through screen-reader testing with [2] blind community reviewers.

---

## 10. 911-linked AED registry + coverage-gap map

**The gap.** Bystanders use an AED in only about **7%** of public cardiac arrests. 911 dispatchers can only direct callers to AEDs they know about, and PulsePoint says millions of AEDs remain unregistered. PulsePoint's "Anyone Can Register" program (launched December 2025) now lets volunteers add AEDs to the national registry that feeds 911 dispatch.

**What AI unlocks.** Finding likely AED sites (gyms, schools, offices, churches) from public building and business lists, mapping coverage gaps against foot traffic and population, drafting outreach to building owners, and writing grant applications for new devices.

**Sample bullet.**
> Registered [410] previously unlisted AEDs in [City] into PulsePoint's 911-linked national registry; AI-assisted gap analysis identified [15] high-traffic "AED deserts," and I secured $[18,000] in grants to place [8] new devices.

---

## Honorable mentions

- **Lead service lines.** Water utilities must submit updated lead-pipe inventories by **Nov 1, 2027** and resolve "unknown" lines by 2037. EPA guidance allows AI-based prediction models if the state approves them. This is high-impact, but you'd need a utility partner.
- **Verified translation for an underserved language.** AI drafts, community reviewers check, and you measure the error rate (AI translation is much weaker in languages like Haitian Creole and Somali).
- **Cash-price guide for uninsured patients.** AI-written code can parse hospitals' huge price-transparency files to find the cheapest imaging and lab prices in your region for free-clinic referrals.

## How to choose

- **Want the largest measurable dollars or care for patients?** Pick #1 or #2.
- **Want something that changes policy?** Pick #3 or #5, and partner with a newsroom or faculty member.
- **Want research credentials as well as impact?** #3, #5, #6 and #7 all turn into publications.
- **Want patient contact?** #1, #2, #4 and #6.
- **Timeline from mid-October 2026:** #4 is deadline-driven (Jan 1, 2027). #9's first deadline is April 2027. #1 and #2 can produce results within 8–12 weeks of starting.

## Ground rules

1. Patient information goes only into tools that are appropriate for it (the partner organization's tools or ones with a HIPAA business associate agreement), always with consent. Never paste it into a consumer chatbot.
2. Hand-check a random sample of anything AI coded or extracted, and report the error rate.
3. A qualified person reviews everything patient-facing (clinician, attorney, certified translator).
4. Every number on your application must be real.

---

## Sources

- KFF, Medicare Advantage prior authorization 2024: https://www.kff.org/medicare/medicare-advantage-insurers-made-nearly-53-million-prior-authorization-determinations-in-2024/
- KFF, ACA claims denials 2024: https://www.kff.org/private-insurance/claims-denials-and-appeals-in-aca-marketplace-plans-in-2024/
- KFF, ACA claims denials 2023: https://www.kff.org/private-insurance/claims-denials-and-appeals-in-aca-marketplace-plans-in-2023/
- Counterforce Health coverage: https://www.wect.com/2025/07/25/ai-tool-that-helps-patients-battle-insurance-claim-denials-got-its-start-wilmingon ; https://www.nbcchicago.com/consumer/how-ai-is-helping-patients-fight-back-against-denied-health-insurance-claims/3835599/?amp=1
- Dollar For: https://triagecancer.org/dollar-for-charity-care ; https://kffhealthnews.org/podcast/an-arm-and-a-leg-podcast-charity-care-nonprofit-dollar-for-medical-bills/
- Dollar For student chapter (UT Austin): https://thedailytexan.com/2022/11/14/student-organization-eliminates-30000-in-austin-medical-debt-raises-awareness-for-hospital-charity-care/
- IRS, financial assistance policies (501(r)): https://www.irs.gov/charities-non-profits/financial-assistance-policies-faps
- Lown Institute, Fair Share Spending 2025: https://lowninstitute.org/projects/hospital-fair-share-spending/
- Medical-debt relief randomized trials: https://siepr.stanford.edu/publications/working-paper/effects-medical-debt-relief-evidence-two-randomized-experiments
- UVA lawsuits investigation (KFF Health News): https://kffhealthnews.org/news/uva-health-system-sues-patients-virginia-courts-garnishment-liens-bankruptcy/
- UVA policy change: https://kffhealthnews.org/courts/uva-will-cut-back-on-lawsuits-against-patients-in-wake-of-khn-investigation/
- NC court-records report: https://www.northcarolinahealthnews.org/2023/08/18/treasurer-hospital-bills-become-medical-debt-nightmares-north-carolinians/
- NC medical-debt relief program: https://www.kff.org/medicaid/north-carolinas-effort-to-relieve-medical-debt/ ; https://www.healthcaredive.com/news/north-carolina-medicaid-debt-relief-incentive-program/722893/
- SNAP application-assistance trial (J-PAL): https://www.povertyactionlab.org/evaluation/snap-take-evaluation
- Benefits Data Trust closure: https://route-fifty.com/management/2024/07/nonprofits-abrupt-closure-puts-access-public-benefits-risk/397968 ; https://technical.ly/civic-news/benefits-data-trust-shutdown-trooper-sanders/
- Medicaid work requirements: https://www.kff.org/medicaid/an-early-look-at-policy-decisions-as-states-get-ready-to-implement-work-requirements/
- Arkansas 2018 study: https://hsph.harvard.edu/news/coverage-losses-substantial-confusion-in-arkansas-following-implementation-of-medicaid-work-requirements/
- Ghost networks, Senate Finance: https://www.techtarget.com/healthcarepayers/news/366603542/Medicare-Advantage-Provider-Directories-Are-Inaccurate-Study-Finds ; https://risehealth.org/insights-articles/ma-plan-directories-haunted-by-ghost-mental-health-networks-senate-finance-committee-study-finds
- FCC AI-voice ruling: https://huntonak.com/privacy-and-information-security-law/fcc-issues-declaratory-ruling-that-tcpa-applies-to-ai-generated-voice-calls
- TrialGPT (NIH): https://www.nlm.nih.gov/news/AI_algorithm_volunteers_clinical_trials.html ; https://www.fiercebiotech.com/cro/ai-model-matches-patients-clinical-trials-fast-human-only-slight-dip-accuracy
- Cancer trial enrollment (Fred Hutch / Unger JNCI 2019): https://www.fredhutch.org/en/news/releases/2019/02/research-shows-structural-barriers-are-the-biggest-reason-for-low-participation-in-clinical-trials.html ; https://www.healio.com/news/hematology-oncology/20240503/substantial-contributions-more-than-20-of-patients-participate-in-cancer-research
- FDAAA TrialsTracker: https://research.cuanschutz.edu/crs/clinical-research-support/clinical-research-administration/clinicaltrials.gov-support/tips-of-the-week-archive/tip-of-the-week-april-2-2020/the-fdaaa-trialstracker-live-and-public-information-on-unreported-clinical-trial-results ; https://journalforclinicalstudies.com/tool-names-shames-hidden-drug-trials/
- Doximity free tools for free clinics: https://www.doximity.com/freeclinics ; https://www.fiercehealthcare.com/ai-and-machine-learning/doximity-jumps-ai-scribe-market-offering-free-tool-doctors
- Ambient AI scribe trials: https://www.medrxiv.org/content/10.1101/2025.07.10.25331333.full.pdf ; https://www.healthday.com/healthpro-news/general-health/ai-based-ambient-scribes-may-reduce-physician-documentation-time-burnout ; https://www.medicine.wisc.edu/news/12162025-department-faculty-lead-new-research-ambient-ai-use-improve-healthcare-practitioner-well-being
- Free clinics (NAFC): https://www.directrelief.org/2026/09/nafc-25-years-free-charitable-clinics-direct-relief/
- ADA Title II deadline extension: https://www.jdsupra.com/legalnews/department-of-justice-delays-compliance-2688927/ ; https://www.duanemorris.com/alerts/doj_extends_ada_title_ii_digital_accessibility_deadlines_one_year_0426.html
- PulsePoint "Anyone Can Register": https://www.pulsepoint.org/news/pulsepoint-and-zoll-accelerate-growth-of-national-emergency-aed-registry-helping-more-communities-locate-and-use-devices-when-seconds-count
- Bystander AED use 7%: https://kffhealthnews.org/news/article/cpr-aed-cardiac-arrest-bystander-training-intervention-saves-lives
- EPA lead service line inventory tips (2026): https://www.epa.gov/system/files/documents/2026-08/508_0813inventorytips_clean.pdf
