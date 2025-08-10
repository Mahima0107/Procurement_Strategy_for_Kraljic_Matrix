# Procurement_Strategy_for_Kraljic_Matrix

Summary: This project analyzes a synthetic procurement dataset using the Kraljic Matrix framework to classify items based on supply risk and profit impact. Led a procurement strategy initiative to enhance supplier segmentation and sourcing efficiency through the implementation of the Kraljic Matrix—an analytical framework that categorizes purchases across two key dimensions: profit impact (strategic importance) and supply risk (market complexity) .
The goal is to assist strategic decision-making by:
-  Segmenting products into Kraljic quadrants
-  Identifying high-risk and high-impact items
- Analyzing environmental and geopolitical factors
- Building a predictive model to auto-classify new items¶

###  Dataset Details : 
* In this dataset There are 11 columns and 1000 rows.
* Algorithm Used: K Nearest Neighbors , Naive Bayes , Logistic Regression , Support Vector Machine , Linear Regression , Gradient Boosting , Random Forest , Adaboost Algorithms .
* Libraries: scikit-learn, pandas, matplotlib, seaborn 

## 🔑 Key Features of the Realistic Kraljic Matrix :
- Synthetic yet Realistic:
  Designed to mimic real-world procurement behavior using built-in biases and patterns like supplier dependencies, geopolitical risk factors, and sustainability considerations 
- Rich Attribute Set:
Supply Risk & Profit Impact scores to drive item categorization across the four Kraljic quadrants.
Additional variables such as cost, environmental scores, and supplier relationships to support deeper strategic analysis 
- Actionable Structure: Tailored to enable exercises in:
Segmentation into Non-Critical, Leverage, Bottleneck, and Strategic categories.
Strategy testing for each quadrant—like risk mitigation, supplier consolidation, negotiation, and sustainability integration.
- Compact and Usable:
A well-structured CSV dataset (~1,000 records) for easy import into tools like Python, Excel, or BI platforms

## 🔍 Model Accuracy :
* Naive Bayes and Linear Regression both achieved 100% accuracy, suggesting good (Excellent) model fit, signaling perfect classification on this dataset—but such results warrant careful scrutiny for potential overfitting.
* Gradient Boosting and Random Forest followed closely at 99% accuracy, demonstrating exceptionally strong predictive power and reliability.
* Logistic Regression performed well with 94% accuracy, marking it as a robust yet simpler alternative.
* K-Nearest Neighbors (KNN) achieved 85% accuracy, hinting at moderate performance that may suffer in more complex patterns.
* Support Vector Machine (SVM) posted the lowest performance among classifiers at 80% accuracy, indicating possible challenges in capturing non-linear boundaries or high variance in features.
* AdaBoost lagged significantly at 54%, suggesting poor model fit, instability, or misconfiguration relative to other ensemble methods.

## 🔍 Project Goal :
Enable data-driven procurement optimization through strategic segmentation—using profit impact and supply risk—to tailor sourcing approaches, enhance supplier management, reduce costs, and mitigate supply disruptions.

## Potential Use Cases :
Segmentation Analysis: Classify products into Kraljic quadrants.
Risk Assessment: Identify high-risk items (e.g., single-source dependencies).
Sustainability Analysis: Correlate environmental impact with supply risk.
Predictive Modeling: Train models to auto-classify procurement items.

## 📌 Conclusion :
The Kraljic Matrix helps organizations make smarter, strategic sourcing decisions—boosting efficiency, reducing risks, and strengthening supply chain resilience. Let me know if you'd like help framing this for various audiences or fields. 
* Successful Kraljic-based procurement projects integrate:
- Strategic collaboration for high-risk, high-impact items,
- Smart leverage of buying power in low-risk areas, and
- Innovative, tech-enabled risk management.
This trio forms the backbone of practical, high-performing procurement strategies in real organizations.
