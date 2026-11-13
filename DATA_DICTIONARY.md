# Data dictionary and interpretation

## data/body_composition.csv

- `date`: nutrition assessment date (ISO 8601), not publication date.
- `phase`: pre-exposure or post-initiation classification, **not** causation.
- `weight_kg`: body weight reported in assessment.
- `body_fat_percent`: estimated fat percentage; method and inter-assessor consistency may be unverified.
- `fat_mass_kg`: assessment-derived estimated fat mass.
- `lean_mass_kg`: derived lean mass, **not directly measured skeletal muscle mass**.
- `source_type`: origin of the value (retrospective summary or participant-supplied report image).
- `notes`: historical context, measurement uncertainty and other anthropometry.

## data/exposures.csv

- `date`, `event`: reported administration or regimen anchor, **not a complete injection calendar**.
- `product_label`, `reported_nominal_mg`, `reported_frequency`: participant-reported, not independently validated.
- `actual_administered_mg_verified`: blank unless confirmed independently; cannot infer from label.
- `source_type`, `notes`: reconstruction uncertainty and provenance.

## data/symptoms.csv

- `date_or_period`: may be approximate, non-ISO period for retrospective symptoms.
- `symptom_or_observation`, `direction`, `measurement`: qualitative outcomes or reported numeric values; nonvalidated symptom scores should not be invented.
- `source_type`, `notes`: context and causal caveats.

## data/weekly_tracking_template.csv

An optional **blank** reporting template, not evidence of observed measurements or an instruction to continue investigational exposure.

## data/anthropometry_comparison_2026-09-29_2026-11-04.md

Side-by-side values from participant-supplied assessment images; no claim that assessors used standardized identical procedures or that isolated regional changes represent specific tissue gains/losses.
