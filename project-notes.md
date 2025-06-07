# Project Notes — Consumer Confidence & GDP

## Overview
- Can we confidently use consumer confidence to predict GDP across distinct economies?
Key Points of Investigation
- How significant is this effect?
- What are the lagging effects? How long does it lag beyond actual GDP growth?
- How does this effect differ from country to country? From rich to poor?
- Limitations. Are there confounding variables?
- What is the reliability of confidence measurements? Are the surveys a correct sample of the population?
- **Initial Focus:** Australia (quarterly data)
- **Later Comparison:** A non-OECD developing economy

## Key Variables
- Consumer Confidence Index (CCI)
- Real GDP Growth (%)
- Unemployment & Inflation (for controls)

## Data Sources
- [OECD Consumer Confidence](https://data.oecd.org/leadind/consumer-confidence-index-cci.htm)
- [OECD GDP Growth](https://data.oecd.org/gdp/quarterly-gdp.htm)

## Tasks + Notes
- [ ] Download CCI + GDP data (Australia)
- [ ] Clean and align quarterly data
- [ ] Explore correlation and lagged trends
- [ ] Run regressions: GDP_t = f(CCI_t-1)
- [ ] Visualise results
- [ ] Write summary of findings and dissussion/interpretation of findings.

## Questions to Explore
- Does CCI lead GDP by 1 quarter or more?
- Is the relationship consistent over time?
- How does this compare to a developing country?

## Roadblocks / Learnings
- ...
