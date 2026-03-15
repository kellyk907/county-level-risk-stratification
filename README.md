County-Level Risk Stratification for Managed Care Optimization
An independent public health research project designing a geographic risk segmentation model that integrates chronic disease burden and social determinants of health (SDOH) to identify structural care risk patterns across 2,957 U.S. counties — using CDC PLACES data to inform precision managed care deployment.
🔗 View the live dashboard ← county-level-risk.netlify.app
🗺️ View interactive county map in Looker Studio https://lookerstudio.google.com/s/pLErHKw_EuA

Objective
Design a geographic risk segmentation model integrating chronic disease burden and social determinants of health (SDOH) to identify structural care risk patterns across U.S. counties — enabling managed care organizations to move from uniform national intervention strategies to precision, geography-informed deployment.

Methodology
Chronic Burden Domain (60% weight)

Aggregated chronic disease prevalence measures: diabetes, COPD, obesity, hypertension
Standardized to percentile-based 0–100 score using CDC PLACES data

SDOH Risk Domain (40% weight)

Aggregated social determinant indicators: food insecurity, housing instability, transportation access, social isolation
Standardized to percentile-based 0–100 score

Composite Risk Model
Composite Risk Score = 0.6(C) + 0.4(S)
C = Chronic Burden Percentile Score
S = SDOH Risk Percentile Score
Risk-Tier Segmentation
TierThreshold% of CountiesHighTop 30% composite score29.93%MediumMiddle 40%39.47%LowBottom 30%30.61%

Key Findings
MetricValueHigh-risk counties29.9% of all U.S. countiesChronic–SDOH correlationr ≈ 0.50 (moderate positive)Mean domain divergence22.6 percentile pointsSevere misalignment (>30pts)28% of counties
Key insight: Risk is not randomly distributed — it clusters geographically and diverges structurally, revealing measurable opportunities for targeted managed care intervention.

Dashboard Features

Risk tier distribution chart — county breakdown across High / Medium / Low composite risk tiers
Composite model architecture — visual breakdown of 60/40 chronic/SDOH weighting
Interactive scatter plot — chronic burden vs. SDOH divergence, color-coded by risk tier with hover tooltips
Regional clustering analysis — high-risk concentration by U.S. region with dual-axis visualization
Operational implications — three strategic pillars for managed care deployment
Next phase roadmap — four-phase scaling framework
Linked Looker Studio map — full county-level geographic visualization across all 2,957 counties


Operational Relevance
Geographic Care Targeting

Prioritize high composite-risk counties for care management expansion
Deploy community-based interventions in structurally aligned high-burden regions
Inform market-level resource allocation decisions

Structural Misalignment Detection

Identify counties where social vulnerability outpaces clinical burden
Detect potential access gaps or underdiagnosed populations
Target preventive outreach before chronic escalation

Value-Based Strategy Alignment

Support value-based contract prioritization
Inform provider network adequacy planning
Enable region-specific intervention models instead of uniform deployment


Next Phase: Scaling the Model
PhaseFocus01 — Claims & Utilization IntegrationValidate composite score against actual utilization; quantify ROI of geographic targeting02 — Predictive Layer DevelopmentTransition from descriptive segmentation to predictive modeling with longitudinal trends03 — Market-Level DrilldownMSA/plan-level segmentation; Medicare Advantage & Medicaid penetration overlay04 — Intervention Tracking FrameworkPre/post outcome tracking; care gap closure monitoring by geography

Data Sources

CDC PLACES: Local Data for Better Health — Primary data source
County Health Rankings & Roadmaps — University of Wisconsin Population Health Institute
CDC/ATSDR Social Vulnerability Index (SVI) — SDOH domain reference
CMS Medicare Geographic Variation — Utilization benchmark reference
KFF — Medicaid Managed Care — Policy context


Skills Demonstrated

Public health data analysis (CDC PLACES)
Composite index construction & percentile normalization
Geographic risk segmentation methodology
SDOH integration into clinical risk models
Data visualization (Chart.js, Looker Studio)
Program evaluation & operational translation
Managed care strategy alignment


About the Author
Kelly Kroeper · MPH, Certified in Public Health (CPH) · Bilingual (English/Spanish)
Public health and nonprofit professional with 15+ years supporting vulnerable children, youth, and families. Background in program design, trauma-informed care, staff development, and data-driven program improvement. Independent researcher focused on translating complex public health data into actionable insights for mission-driven and managed care organizations.
🔗 www.linkedin.com/in/kroeperk

Independent research project · 2026 · Data: CDC PLACES · Kelly Kroeper MPH, CPH
