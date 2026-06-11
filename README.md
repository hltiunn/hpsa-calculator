# HPSA Designation Calculator

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Developed by the [Mullan Institute for Health Workforce Equity](https://gwhwi.org) at the George Washington University Milken Institute School of Public Health.

**🔗 Live Tool: https://hltiunn.github.io/hpsa-calculator/**

---

## What Is This?

An interactive calculator that lets users explore how including Nurse Practitioners (NPs) and Physician Associates (PAs) in the population-to-provider ratio would change **Health Professional Shortage Area (HPSA)** designations.

Under current federal regulation (42 CFR Part 5), only physicians (MDs/DOs) are counted when determining whether an area qualifies as an HPSA. This tool allows you to adjust:

- **NP/PA FTE equivalency** — how much of a physician FTE each NP or PA should count as
- **Threshold ratios** — the population-to-provider ratio that triggers HPSA designation
- **Full-time and panel assumptions** — reflecting different workforce survey data

## Why Does It Matter?

HPSA designations drive billions in federal funding: National Health Service Corps loan repayment, Medicare physician bonuses, rural health clinic subsidies, and GME funding. The methodology was developed in the 1970s when NPs barely existed. Today there are 461,000+ NPs, yet they remain excluded from the formula.

Wittkower et al. (2026) found that including NPs would eliminate **~80% of current HPSA designations** under conservative assumptions.

## Literature Presets

The tool includes one-click presets from:

| Source | NP Weight | Key Finding |
|--------|-----------|-------------|
| Wittkower et al. (MCRR, 2026) | 0.66 | 80.2% of counties lost HPSA at 3,000:1 |
| Wittkower et al. — Full Additive | 0.825 | 85.2% lost designation |
| Paragon Health Institute (2024) | 1.0 | Tioga/Potter County example |
| Morgan et al. (JAAPA, 2021) | 0.88 | NP+PA combined productivity ratio |

## Data Sources

### Tier 1: Government / Regulatory
- 42 CFR Part 5, Appendix A (designation criteria)
- HRSA Shortage Designation Management System Manual (scoring methodology)
- HRSA HPSA Primary Care File — [data.hrsa.gov/data/download](https://data.hrsa.gov/data/download)

### Tier 2: Peer-Reviewed Literature
- Wittkower, Bradley & Plemmons (2026). *Medical Care Research and Review*. DOI: [10.1177/10775587261442035](https://doi.org/10.1177/10775587261442035)
- Morgan et al. (2021). *JAAPA*.
- Mayo-Smith et al. (2022). *JAMA Network Open*.
- Martsolf et al. (2022). *Journal for Nurse Practitioners*.

### Tier 3: Research Organizations
- Paragon Health Institute (2024)
- AANP Workforce Survey (2024)
- HRSA National Sample Survey of Registered Nurses (2022)
- NCCPA Statistical Profile (2025)

## Technical Details

- Pure HTML + CSS + JavaScript — no dependencies, no build step
- Works offline after loading
- Mobile-responsive

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

**Suggested citation:**

> Mullan Institute for Health Workforce Equity. (2026). HPSA Designation Calculator. George Washington University. https://github.com/hltiunn/hpsa-calculator
