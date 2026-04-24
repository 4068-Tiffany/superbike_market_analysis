# 1. Business Understanding

## 1.1 Business Overview

The superbike industry is characterized by intense competition between Japanese and European manufacturers. While brands like Kawasaki have built a reputation on raw performance and "Ninja" branding, consumers and stakeholders lack an objective, data-driven way to compare engine tuning and efficiency across different brands and engine displacements. This project evaluates how these engineering philosophies translate into real-world performance metrics.

## 1.2 Problem Statement

Motorcycle technical specifications are often presented in inconsistent formats (mixing HP and PS units, or including RPM data in string format), making direct comparison difficult. Furthermore, traditional metrics like "Total Horsepower" favor larger engines, masking the true engineering efficiency of a brand. Without a normalized metric like Horsepower per CC (Efficiency), it is impossible to determine which brand truly maximizes its engine technology.

## 1.3 Business Objectives

Main Objective: To perform a comparative performance analysis of major superbike brands (Kawasaki, BMW, Honda, Suzuki, Yamaha) to identify the "Efficiency King" across various engine classes.

### 1.3.1 Specific Objectives:

Clean and normalize technical specifications from a raw motorcycle dataset using Regex and type conversion.

Identify and isolate data anomalies and physical impossibilities (outliers) that skew market analysis.

Quantify the correlation between engine size (CC) and performance efficiency.

Determine which brand provides the highest "tuning density" (HP/CC) in the Entry-level and Superbike categories.

### 1.3.2 Research Questions

Does Kawasaki maintain a higher efficiency rating in entry-level bikes (under 400cc) compared to its rivals?

Is there a point of diminishing returns where increasing engine displacement (CC) leads to a decrease in overall engine efficiency?

How closely matched are the top-tier "Liter Bikes" (1000cc) across different manufacturers in the 2026 market?

# 2. Data Understanding

## 2.1 Data Source and Scope

The dataset used is bikes_data.csv, containing recent technical specs (2022–2026) for five major companies: BMW, Honda, Kawasaki, Suzuki, and Yamaha. It includes fields for Model, Year, Horsepower, and Number of CC.
