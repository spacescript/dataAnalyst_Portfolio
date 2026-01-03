# dataAnalyst_Portfolio

# Semiconductor Sensor Variability Analysis

## Business Problem
Semiconductor manufacturing involves monitoring 590+ sensor readings per wafer. Which sensors show concerning variability that could impact quality control?

## Data Source
- SECOM dataset (UCI Machine Learning Repository)
- 1,567 wafer observations
- 590 sensor features
- 6.64% failure rate

## Analysis Process
**Data Cleaning:**
- Removed 130 features with >50% missing values
- Retained 464 features with sufficient data coverage

**Feature Analysis:**
- Calculated variance, standard deviation, and range for all features
- Ranked features by variability
- Created actionability framework for manufacturing context

## Key Findings
- Feature_163 shows highest variance (42.9M), indicating extreme measurement instability
- 12 features identified with high variability requiring monitoring attention
- Variance analysis provides foundation for targeted sensor calibration

## Tools Used
- Excel: Data cleaning, statistical calculations
- Power BI: Dashboard visualization, DAX measures

## Limitations
- Analysis focuses on variability, not predictive modeling
- Actionability scores are illustrative framework
- Real implementation would require domain expert input on sensor criticality

## Next Steps
- Compare sensor distributions between PASS/FAIL wafers
- Develop classification model for defect prediction
- Validate findings with manufacturing engineering team