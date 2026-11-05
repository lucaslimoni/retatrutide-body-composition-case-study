# Retatrutide and Body Composition: A Longitudinal Self-Reported Case Study

> **Version:** 0.3.0 (2026-11-05) · **Status:** preliminary, retrospective and ongoing self-report (N=1). **Not peer reviewed; not a clinical trial; not medical advice.** Retatrutide is an investigational compound; neither this report nor its exposure history is a recommendation to use it.

## Abstract
An adult resistance-trained participant reports initiating use of a product sold as retatrutide on **2026-09-14**, with a reported starting and current regimen of **2.5 mg once weekly**. The participant clarified on **2026-10-29** that **154.5 kg** was measured at a nutritionist visit on **2026-09-29**, not on October 29. The product was identified as **Thera**. Historical nutrition/body-composition data are reported for January–April and **2026-08-31** (pre-exposure), and **2026-09-29** (post-initiation); underlying reports have not been independently checked. The participant retrospectively reported reduced appetite, greater energy, less post-cardio sleepiness, and headaches and other symptoms of uncertain temporal association. A participant-reported post-initiation nutrition assessment is now documented, but the underlying report, laboratory confirmation of compound identity, systematic symptom diary and controlled comparison are unavailable. **No causal efficacy or safety conclusions can be drawn.**

## Participant and provenance
- Author/participant: **Lucas Limoni** (GitHub account `lucaslimoni`); identifying personal medical details and source records should only be published following an additional privacy review.
- Experienced resistance trainee and former powerlifting athlete; reports heavy strength training and substantial cardio participation. Specific concurrent program, diet and workloads by date are incompletely documented.
- Sources: participant's conversation-based self-reports and previously supplied body-composition measurements. Underlying clinical reports have not been independently reviewed for this release.
- All historical retrospective values should be regarded as **participant-reported**; blank cells signify unavailable data, not zero.

## Timeline and body composition
**Crucial separation:** five historical assessments below occurred **before** retatrutide began. The **2026-09-29** value is a participant-reported measurement from a nutritionist visit **after** initiation. There is no measured weight immediately before the first reported administration.

| Date | Phase | Weight (kg) | Body fat (%) | Fat mass (kg) | Lean mass (kg) | Data type |
|---|---|---:|---:|---:|---:|---|
| 2026-01-15 | Pre-exposure | 157.0 | 23.53 | 36.95 | 120.05 | Historical assessment reported |
| 2026-02-18 | Pre-exposure | 155.4 | 19.86 | 30.87 | 124.53 | Historical assessment reported |
| 2026-03-18 | Pre-exposure | 152.9 | 17.20 | 26.29 | 126.61 | Historical assessment reported |
| 2026-04-22 | Pre-exposure | 152.9 | 16.78 | 25.66 | 127.24 | Historical assessment reported |
| 2026-08-31 | Pre-exposure | 157.9 | 22.36 | 35.31 | 122.59 | Retrospective nutrition assessment summary |
| 2026-09-14 | First exposure reported | — | — | — | — | No same-day measurement |
| 2026-09-29 | Post-initiation | 154.5 | 18.82 | 29.07 | 125.43 | Retrospective nutrition assessment summary |
| 2026-11-04 | Post-initiation | 150.9 | 17.61 | 26.57 | 124.33 | Participant-provided nutrition assessment image |

**31 August to 29 September (29 days):** reported weight 157.9 → 154.5 kg (**−3.4 kg**); fat fraction 22.36% → 18.82% (**−3.54 percentage points**); estimated fat mass 35.31 → 29.07 kg (**−6.24 kg**); estimated lean mass 122.59 → 125.43 kg (**+2.84 kg**). Waist 120 → 115 cm (**−5 cm**), abdominal circumference 130 → 120 cm (**−10 cm**), sum of skinfolds 152 → 124 mm (**−28 mm**, measurement protocol unverified). This 29-day interval includes **14 days before the first exposure**. Measurement variability and confounding prevent attribution to retatrutide. Numeric body-composition changes are assessment-derived estimates, **not proof of actual fat or muscle changes**.

**Nutritionist appointment completed:** **2026-11-04**. The participant supplied an image of the anthropometric report on 2026-11-05. The original report itself has not been uploaded to this public repository to avoid exposing unnecessary personal information.

## Retatrutide exposure (documentation only; not dosage guidance)
- First reported date: **2026-09-14**.
- Starting regimen reported: **2.5 mg/week**. Current regimen reported on **2026-10-29**: **2.5 mg/week**, product label/brand named **Thera**.
- Retrospectively retrieved administration chronology: **2026-09-14 about 23:00** (first), **2026-09-21 about 09:00** (second, as recorded in an earlier summary), and **2026-09-27** (third, Sunday inferred from an earlier account). The second reported time and third date should be cross-checked against the participant's original diary; this is not a prospectively verified injection log. The participant has separately reported intentions to maintain Monday evening dosing; these differ from some reconstructed dates/times and **must not be treated as confirmations of actual administration**.
- Other administration dates, missed/shifted doses, route, exact formulation, dilution, vial labeling, batch number, product source, certificate of analysis, actual drug identity, measured concentration and independently confirmed delivered amount remain **unverified**.
- A stated mg amount is a participant-reported *nominal* dose; it is **not** verification that the administered material contained that quantity of retatrutide.

## Retrospective self-reported experiences
These observations were recalled during earlier conversations and are **not** daily prospectively scored outcomes:
- **Perceived changes:** diminished hunger, sometimes forgetting to eat; increased energy/positive mood; reduced sleepiness after morning cardio; cardio perceived as easier; perception of a smaller abdomen (the reported 31 Aug and 29 Sep nutrition measurements provide a separate, not independently verified comparison).
- **Potential adverse symptoms:** morning headaches; feeling mentally 'spaced out' before lunch; transient stomach discomfort after sweet popcorn. Associations and severity were not clinically adjudicated. Some headaches were reported to subside after eating.
- **Unknown:** actual onset/duration per symptom, standardized appetite scoring, glucose values, lab outcomes, and later persistence or resolution.
- **Confounders:** sustained training and dietary changes; sleep and hydration; supplement or medication exposure (including **BPC-157 beginning 2026-10-28** as independently self-reported in a separate case study). These exposures should be reconciled by date; the fact that BPC-157 started later means it cannot explain September observations.

## Data quality of recovered diary
Details on 31 Aug / 29 Sep composition and the first three applications were retrieved from prior conversation summaries rather than a direct audit of the original clinical reports or complete contemporaneous diary. They are marked as **retrospective summary**, with ambiguous timestamps identified explicitly. Do not manufacture missing weekly exposures or extrapolate a treatment effect.

## Methods and future recording
This is a descriptive, single-participant longitudinal self-observation. The record is organized into:
- `data/body_composition.csv` — historical measurements including the Aug/Sep comparison, with phase and provenance.
- `data/exposures.csv` — only reported exposure anchors; **not** a manufactured weekly application log.
- `data/symptoms.csv` — retrospectively recalled symptoms, with uncertain dates marked explicitly.
- `data/weekly_tracking_template.csv` — empty template for optional future observations, without encouraging continued exposure.
- `OPEN_QUESTIONS.md` — verification needs and limitations.

For future comparisons, record measured body weight under comparable conditions, appetite and well-being, exact symptom dates, treatment changes, and training/diet context; any laboratory or clinical data should be interpreted with a qualified clinician.

## Limitations and safety
This uncontrolled, non-blinded N=1 self-report is vulnerable to recall bias, expectancy effects, measurement variability and major confounding. Different body-composition methods can vary substantially. The November post-initiation body-composition report is available as a participant-provided image, but measurement accuracy and repeatability have not been independently verified; there are no controlled tests and no evidence here for efficacy, dose-response, durability or safety. Retatrutide is investigational and should not be treated as a validated self-medication protocol.

## Ethics, consent and reuse
The participant asked to prepare and publish this preliminary case study in their public GitHub repository. This is not institutional ethics approval or consent for unrelated sharing of private health records. Before attaching any clinical records, lab results, addresses, photographs or batch labels, remove personal identifiers and review them individually. No treatment instructions are offered.

## Companion case
A separate public self-report on bilateral epicondylitis and a product labeled BPC-157: [bpc157-epicondylitis-case-study](https://github.com/lucaslimoni/bpc157-epicondylitis-case-study). It is a distinct case and should not be used as evidence of retatrutide effects.

## Participant follow-up — 2026-10-29 (self-report)

- The current reported weekly routine is Sunday at 16:00, administered near the umbilicus; this is **not** confirmation that every previous Sunday included an administration. The nominal weekly regimen remains participant-reported as 2.5 mg.
- Participant reports a long-standing **1,900 kcal/day dietary plan** for more than one year, predating exposure. Actual intake and adherence have not been measured. Typical meal timing is approximately one hour before strength training.
- Participant describes markedly decreased appetite and meal capacity, sometimes aversion toward high-fat food, next-day abdominal discomfort after such meals, and one isolated episode of upper-central abdominal pain.
- Several episodes of intense throat burning after workouts occurred during the preceding week, then resolved without medication or change in routine. A reflux mechanism is possible but unconfirmed, and exertion-associated symptoms merit medical assessment.
- Cardio routine changed from two 60-minute sessions to two 40-minute sessions per day on a treadmill, with reported speed 5 km/h and 0% incline. Mean heart rates are recalled as approximately 115 bpm formerly and 112 bpm more recently, not under matched conditions. The participant did not perform cardio this week and intended to resume subsequently; resumption is not verified.
- Participant reports markedly less tiredness during and after cardio and increased motivation to run, due to both ease of walking and perceived energy. **No running has been undertaken.** A specific contribution of glucagon-receptor activity remains speculative.

These are unblinded self-reports with possible effects of shorter activity duration, training adaptation, diet, measurement variation and other factors. They do not establish safety, causation or treatment benefit.

## Cross-exposure symptom observation — 2026-10-30; status reviewed 2026-11-05

The participant reported eating a hot dog on **2026-10-29** and experiencing **no usual next-day stomach discomfort or malaise on 2026-10-30**. This meal preceded the *third reported* BPC-157 administration, but occurred after earlier reported administrations, while the participant also reported retatrutide exposure. A single episode cannot establish the safety of the meal, the effects of either substance, or any protective interaction. No systematic re-challenge, symptom scale, gastrointestinal diagnosis, or independent observation was performed.

On 2026-11-05, the participant additionally reported near-absence of bilateral elbow pain and continued daily BPC-157 exposure. These are relevant **concomitant-exposure confounders**, not evidence of a beneficial retatrutide–BPC-157 combination. The 2026-11-04 nutritionist assessment is now documented below based on the image provided by the participant.

## Nutritionist follow-up — 2026-11-04 (source: report image supplied 2026-11-05)

The latest report states height **1.68 m**, body weight **150.90 kg**, fat fraction **17.61%**, fat mass **26.57 kg**, lean mass **124.33 kg**, BMI **53.47**, waist **110 cm**, abdomen **115 cm**, hip **137 cm**, shoulder **162 cm**, chest **142 cm**, and skinfold sum **115 mm**. This is an actual documented appointment rather than a planned future measurement. The case report does **not** establish biochemical markers, imaging-based muscle mass, or the accuracy of the estimation equations.

### September-to-November comparison (36 days)

| Measure | 2026-09-29 | 2026-11-04 | Change |
|---|---:|---:|---:|
| Body weight | 154.50 kg | 150.90 kg | -3.60 kg |
| Estimated body-fat percentage | 18.82% | 17.61% | -1.21 percentage points |
| Estimated fat mass | 29.07 kg | 26.57 kg | -2.50 kg |
| Estimated lean mass | 125.43 kg | 124.33 kg | -1.10 kg |
| Waist | 115 cm | 110 cm | -5 cm |
| Abdomen | 120 cm | 115 cm | -5 cm |
| Sum of skinfolds | 124 mm | 115 mm | -9 mm |

Estimated lean mass is **not equivalent to skeletal muscle mass**: hydration, glycogen, anthropometric measurement variability and calculation methods may affect it. Likewise, apparent changes in fat mass do not prove a medication effect. Comparisons of derived body-composition results assume similar methods and assessor conditions, which have not been independently verified.

### Training and diet context / change in cardio exposure

The participant explicitly reports **substantially reducing cardio during the preceding month, intentionally to observe what happened**, while continuing resistance training, the existing stated **1,900 kcal/day diet plan**, and retatrutide exposure. Specific completed weekly cardio minutes, nutritional adherence, and exercise loads were not measured; previous reports described a reduced usual plan of two 40-minute treadmill sessions per day, with a temporary week without sessions. A deliberate change in one behavior **does not create a controlled experiment**: changes in energy intake, activity, body water, measurement conditions and other factors remain possible confounders. BPC-157 was also reported as introduced on **2026-10-28**; thus concomitant exposure exists for the final days of the interval.

### Full anthropometric report, 2026-11-04

| Measurement | Value |
|---|---:|
| Height | 1.68 m |
| Weight | 150.90 kg |
| Shoulder / chest | 162 / 142 cm |
| Waist / abdomen / hip | 110 / 115 / 137 cm |
| Right / left thigh | 75 / 75 cm |
| Right / left calf | 45 / 45 cm |
| Right / left relaxed arm | 50 / 50 cm |
| Right / left flexed arm | 58 / 58 cm |
| Right / left forearm | 38 / 39 cm |
| Abdominal / suprailiac / subscapular skinfold | 31 / 12 / 21 mm |
| Thigh / triceps / mid-axillary / chest skinfold | 12 / 11 / 16 / 12 mm |
| BMI | 53.47 kg/m² |
| Waist-to-hip ratio reported | 0.80 |
| Arm muscular area / arm fat area | 172.39 / 26.55 (units not supplied) |

**Interpretation boundaries:** this remains an uncontrolled, non-blinded self-report of an investigational product. There is no verified mechanism, efficacy or safety inference from the observed trend. Do not attempt to replicate the exposure or restrict nutrition for the purpose of this case report.
