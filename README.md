# AnalystLab_Africa_Week7

# HealthConnect — Week 7 Analytics Testing & Refinement

## 📌 Project Overview

Week 7 of the AnalystLab Africa HealthConnect Experience Lab focused on
testing, refinement and end-to-end validation of the Data Analytics outputs
developed during Week 6.

The objective was to verify KPI calculations, validate important analytical
findings, test dashboard outputs, identify analytical weaknesses and refine
the final recommendations.

---

## 🎯 Objectives

- Validate core Power BI KPIs
- Test analytical findings against the underlying dataset
- Test important dashboard filters and calculations
- Identify analytical errors and weaknesses
- Refine dashboard visualisations and interpretation
- Reassess business recommendations
- Document limitations and remaining analytical issues
- Prepare validated findings for cross-track collaboration

---

## 📊 Key Validated Results

| Metric | Result |
|---|---:|
| Total Appointments | 5,000 |
| No-Show Appointments | 2,423 |
| No-Show Rate | 48.46% |
| Cancelled Appointments | 263 |
| Cancellation Rate | 5.26% |
| Reminder Coverage | 72.68% |

---

## 🔎 Analytical Validation

### Reminder Status

- Reminder: No → 51.39% no-show rate
- Reminder: Yes → 47.36% no-show rate

The difference was validated as an observed association and was not
interpreted as proof of causation.

### Distance to Clinic

- Less than 5 km → 46.40%
- 5–9 km → 46.50%
- 10–19 km → 49.50%
- 20+ km → 57.29%

The 20+ km group showed a relatively high observed no-show rate.

### Previous No-Show History

No-show rates generally increased across higher previous-no-show groups,
although small groups require caution when interpreting percentages.

---

## 🧪 Testing & Refinement

Testing identified several areas requiring attention:

- Missing waiting-time values
- Missing distance values
- Small segment sizes
- Association versus causation
- Dashboard interpretation and labelling

Dashboard refinements included clearer visual titles, improved explanatory
notes and more cautious interpretation of analytical findings.

---

## 💡 Validated Recommendations

1. Evaluate and strengthen the appointment reminder process.
2. Consider previous no-show behaviour for future risk segmentation.
3. Investigate potential accessibility barriers for long-distance patients.
4. Improve waiting-time and distance data completeness.
5. Explore future predictive modelling for appointment no-shows.

---

## 🤝 Cross-Track Contribution

The Analytics track identified candidate variables that may support the
planned Data Science no-show prediction use case:

- Previous no-shows
- Previous appointments
- Reminder status
- Distance to clinic
- Waiting time
- Appointment type
- Age group
- Booking lead days

These variables are candidate modelling features and were not treated as
confirmed predictors.

---

## ⚠️ Limitations

- The analysis is observational.
- Associations do not establish causation.
- Some variables contain missing data.
- Some segments contain relatively few records.
- No predictive model was developed or validated within this Analytics work.
- Cross-track Data Science integration remained an area for further work.

---

## 🚀 Week 8 Direction

Future work will focus on:

- Final dashboard integration
- Improved data quality
- Supporting Data Science modelling
- Validating predictive outputs when available
- Strengthening cross-track collaboration
- Moving from descriptive analysis toward decision support

---

## 🛠️ Tools

- Power BI
- DAX
- Excel
- Data Analysis

---

