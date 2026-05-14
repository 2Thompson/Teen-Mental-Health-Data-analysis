# Teen Social Media Usage & Mental Health Analysis

## Project Overview

This comprehensive data analysis project explores the relationship between social media usage patterns and mental health indicators among teenagers. Using a rich dataset containing information on social media habits, sleep patterns, physical activity, and mental health metrics, this analysis provides actionable insights for parents, educators, policymakers, and mental health professionals.

## Key Research Questions

1. How do social media usage patterns differ by gender and age?
2. Which social media platforms are most time-consuming and potentially problematic?
3. What is the relationship between pre-sleep screen time and sleep duration?
4. How do mental health indicators (stress, anxiety, depression risk) vary by platform choice?
5. Does physical activity moderate the relationship between social media use and mental health?
6. Which platforms pose the highest composite risk to teen well-being?

## Dataset Description

### Source
The dataset (`Teen_Mental_Health_Dataset.csv`) contains synthetic/aggregated survey data on teen social media usage and mental health indicators.

### Variables Included
| Variable | Description | Type |
|----------|-------------|------|
| `age` | Age of teen (years) | Numeric |
| `gender` | Gender (male/female) | Categorical |
| `daily_social_media_hours` | Average daily social media usage | Numeric (hours) |
| `platform_usage` | Primary social media platform | Categorical |
| `screen_time_before_sleep` | Screen time in hour before bed | Numeric (hours) |
| `sleep_hours` | Total daily sleep | Numeric (hours) |
| `physical_activity` | Daily physical activity level | Numeric/Categorical |
| `stress_level` | Self-reported stress (1-10) | Numeric |
| `anxiety_level` | Self-reported anxiety (1-10) | Numeric |
| `depression_risk` | Depression risk level | Categorical (low/medium/high) |
| `academic_performance` | Academic performance indicator | Categorical |
| `social_interaction` | Social interaction frequency | Categorical |

### Data Quality
- **No missing values** across all columns
- Clean, well-structured format
- Suitable for statistical analysis and visualization

## Features and Analysis

### 1. Data Exploration
- Dataset structure inspection
- Missing value detection
- Data type verification

### 2. Social Media Usage Patterns
- Usage analysis by gender and age
- Platform preference and popularity
- Heavy vs. light user segmentation

### 3. Screen Time Before Sleep
- Overall distribution analysis
- Demographic breakdowns (gender, age, platform)
- Risk categorization (Low/Medium/High)
- Correlation with sleep duration

### 4. Mental Health Indicators
- Stress levels by platform
- Anxiety levels by platform
- Depression risk assessment

### 5. Physical Activity Analysis
- Relationship between physical activity and social media use
- Health outcomes comparison across activity levels
- Gender × Activity level interactions

### 6. Composite Risk Assessment
- Multi-metric risk scoring
- Platform ranking by risk level
- Normalized composite scores

## Key Findings

### Gender Differences
- Significant differences exist in total usage hours between genders
- Platform preferences vary substantially by gender
- Screen time before sleep patterns differ between males and females

### Age Effects
- Social media usage patterns change across adolescent development
- Pre-sleep screen time tends to increase with age for some platforms
- Age-group specific patterns identify targeted intervention opportunities

### Platform Impact
- **Most time-consuming platforms**: Identified through average daily hours
- **Highest risk platforms**: Determined through composite risk scoring
- Platform choice correlates with different mental health outcomes

### Pre-Sleep Screen Time
- Direct negative correlation with sleep duration
- Higher pre-sleep screen time associated with:
  - Reduced total sleep hours
  - Higher stress levels
  - Increased anxiety
  - Greater depression risk

### Physical Activity as Protective Factor
- Higher physical activity associated with:
  - Lower social media usage
  - Better sleep quality
  - Reduced stress and anxiety
  - Lower depression risk

## Visualizations Included

| Figure | Description |
|--------|-------------|
| Bar Charts | Gender comparisons, platform rankings |
| Scatter Plots | Age vs usage, screen time vs sleep |
| Heatmaps | Platform usage by age |
| Box Plots | Distribution comparisons |
| Histograms | Screen time distribution |
| Pie Charts | Platform popularity |
| Stacked Bar Charts | Risk category distributions |
| Faceted Charts | 3D analysis (Platform × Gender × Age) |
| Risk Dashboards | Composite risk scores |

## Requirements

### Python Version
- Python 3.8 or higher

### Required Packages
```python
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
