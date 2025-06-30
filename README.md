# Circadian Rhythm and Well-being Analysis

A comprehensive analysis of sleep patterns, chronotypes, and their impact on mental well-being.

---

## 📋 Table of Contents
- [Objective](#objective)
- [Dataset](#dataset)
- [Key Findings](#key-findings)
  - [1. Participant Distribution Across Chronotypes](#1-participant-distribution-across-chronotypes)
  - [2. Circadian Misalignment (Social Jetlag)](#2-circadian-misalignment-social-jetlag)
  - [3. Relationships Among Variables](#3-relationships-among-variables)
  - [4. Mental Health Scores by Chronotype](#4-mental-health-scores-by-chronotype)
  - [5. Prediction of Anxiety](#5-prediction-of-anxiety)
  - [6. Anxiety and Social Jetlag by Chronotype](#6-anxiety-and-social-jetlag-by-chronotype)
  - [7. Mood Variation Across the Week](#7-mood-variation-across-the-week)
  - [8. Partial Correlation Analysis](#8-partial-correlation-analysis)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)
- [Usage](#usage)
- [License](#license)

---

## 🎯 Objective

This project aims to analyze the relationships between various circadian rhythm parameters (chronotype, sleep timing, sleep duration, and social jetlag) and mental well-being indicators (mood, stress, and anxiety scores) within the studied population.

---

## 📊 Dataset

- **Participants:** 9,000 individuals
- **Collected Variables:**  
  - Chronotype (Early Bird, Intermediate, Night Owl)  
  - Sleep Timing and Duration  
  - Social Jetlag  
  - Mood, Stress, and Anxiety Scores

---

## 🔍 Key Findings

### 1. Participant Distribution Across Chronotypes
- **Intermediate:** 45.33%
- **Early Bird:** 28.22%
- **Night Owl:** 26.44%

### 2. Circadian Misalignment (Social Jetlag)
- **Mean Social Jetlag:** 0.35 hours
- **>2 Hours Social Jetlag:** 0%

### 3. Relationships Among Variables (Correlation Matrix)
- **Mid-Sleep Time:** 
  - Stress (0.70)
  - Anxiety (0.69)
  - Mood (-0.24)
  - Sleep Duration (0.39)
- **Social Jetlag:**
  - Stress (0.26)
  - Anxiety (0.31)
- **Mood:**
  - Stress (-0.28)
  - Anxiety (-0.27)
- **Stress & Anxiety:**
  - Correlation (0.70)

### 4. Mental Health Scores by Chronotype
- **Anxiety Mean:**  
  - Night Owls: 7.29  
  - Early Birds: 3.16  
- **Stress Mean:**  
  - Night Owls: 7.24  
  - Early Birds: 3.12  
- **Mood Mean:**  
  - Early Birds: 5.25  
  - Night Owls: 4.41  

### 5. Prediction of Anxiety
- **Lag Correlation between Sleep Start Time and Anxiety:** 0.75
- **Regression Predictors:**
  - Mid Sleep: 0.926
  - Social Jetlag: 0.655
  - Interaction Term: -0.006

### 6. Anxiety and Social Jetlag by Chronotype
- Night Owls show consistently higher ranges and medians.

### 7. Mood Variation Across the Week
- Lowest on Monday
- Peak around Thursday/Friday
- Slight decrease on weekends

### 8. Partial Correlation Analysis
- **Mid Sleep and Anxiety (controlling for Sleep Duration):** 0.75

---

## 🧩 Conclusion

The analysis demonstrates a significant relationship between circadian rhythm characteristics and mental well-being. Night Owls consistently exhibit higher anxiety and stress levels and lower mood scores. Later sleep timing strongly associates with increased anxiety and stress and decreased mood. 

---

## 💡 Recommendations

- **Chronotype-Specific Interventions:** Tailor mental health strategies, especially for Night Owls.
- **Promote Consistent Sleep Schedules:** Later sleep onset predicts increased anxiety.
- **Address Social Jetlag:** Minimize weekday-weekend schedule discrepancies.
- **Further Investigate Mid-Sleep Time:** Explore mechanisms behind strong associations.
- **Longitudinal Studies:** Establish causality.
- **Incorporate Other Lifestyle Factors:** Diet, physical activity, social support.
- **Personalized Recommendations:** Align sleep patterns with individual chronotype.

---
