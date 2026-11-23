# ML-Based Network Intrusion Detection on CIC-IDS2017

## Project Overview
This repository contains a baseline network intrusion detection system (IDS) built using a Random Forest classifier. The goal of this project is to evaluate how well a standard machine learning model can distinguish between benign network traffic and various attack types (such as DDoS, PortScan, and Web Attacks) using flow-based statistical features.

The pipeline handles data loading, feature scaling, model training, and rigorous evaluation—specifically focusing on **macro-F1** rather than standard accuracy, due to the severe class imbalance present in real-world network traffic. The analysis highlights that while volumetric attacks are detected almost perfectly, low-volume, semantically subtle attacks (like XSS and SQL Injection) remain a significant challenge for tree-based models.
