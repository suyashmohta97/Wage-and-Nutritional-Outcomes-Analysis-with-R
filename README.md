# Wage-and-Nutritional-Outcomes-Analysis-with-R
Analyzed the impact of minimum wage changes on calorie consumption and nutritional quality using a difference-in-differences approach.

![image](https://github.com/user-attachments/assets/d04b89a8-f5c7-4fe2-828e-66f2d06197d1)


## Project Background

This project analyzes the impact of minimum wage changes on consumer behavior, specifically focusing on calorie consumption and basket scores (a measure of nutritional quality). The study uses a difference-in-differences (DiD) approach to assess the effects on treated and untreated groups over time.

## Problem Statement

Previous research has suggested that changes in minimum wage policies can influence consumer purchasing behavior, particularly in food choices. This study investigates:

Whether minimum wage increases affect calorie consumption.

The impact on basket scores as a proxy for nutritional quality.

How these effects vary across regions and time.

## Key Questions

How does a minimum wage increase affect calorie consumption?

Does basket score behavior differ between treated and untreated groups?

Are there observable parallel trends between groups before treatment?

## Data Overview

The dataset includes detailed records across multiple states with attributes such as:

ID: Unique identifier for each observation

Group: Indicates whether the observation belongs to the Minimum Wage or Control group

Year & Month: Time periods for tracking pre- and post-treatment outcomes

Calories: Number of calories consumed in each observation

Basket Score: A measure of nutritional quality

## Methodology

Data Cleaning & Preparation: Created treatment period and group identifiers.

Descriptive Analysis: Summarized data across key variables.

Parallel Trends Analysis: Examined pre-treatment trends to assess validity of the DiD approach.

Difference-in-Differences (DiD) Analysis: Measured treatment effects on calories and basket score.

Model Evaluation: Evaluated significance of key coefficients to confirm causal relationships.

## Key Findings & Insights

### 1. Impact of Minimum Wage on Calories

The DiD model revealed that while calorie consumption initially decreased in the treatment group, the impact was not statistically significant.

![image](https://github.com/user-attachments/assets/6e2fcb3f-62c5-45c9-8fcd-017000a37e04)


### 2. Impact on Nutritional Quality (Basket Score)

The DiD model highlighted a small but positive improvement in basket scores for the treatment group post-treatment.

![image](https://github.com/user-attachments/assets/b78f7041-5aac-4be6-a19f-409deab97e0b)


### 3. Parallel Trends Analysis

Parallel trends were confirmed before the treatment period, validating the DiD approach.

![image](https://github.com/user-attachments/assets/64d9accd-f269-4867-8f40-4e00d99a1a4f)


### 4. Staggered Difference-in-Differences Analysis

Additional analysis incorporating staggered treatment periods showed consistent patterns, reinforcing key findings.

![image](https://github.com/user-attachments/assets/acc1bd07-6174-47dd-85e2-2ed2db77abf3)


## Conclusion

The analysis found minimal evidence of a significant reduction in calorie consumption following minimum wage increases. However, there was some improvement in basket scores, suggesting a slight shift toward better nutritional choices. The study underscores the complexity of linking economic policy to consumer behavior.

## Recommendations

Conduct further research with a longer observation period to capture delayed consumer responses.

Incorporate household income data to improve the model’s explanatory power.

Evaluate other dietary metrics such as sugar content and food category preferences for a comprehensive analysis.
