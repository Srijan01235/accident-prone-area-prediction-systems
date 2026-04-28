##Accident-Prone Area Prediction System

Accident-Prone Area Prediction System is a machine learning project that predicts highly accident-prone areas in a city using historical crash data, weather conditions, and road-structure features.

The goal of this project is **not route recommendation**. Instead, it focuses on identifying **high-risk accident zones** and visualizing them on an interactive map.

---

## Project Overview

Road accidents are not randomly distributed across a city. Certain areas become more dangerous due to factors such as:

- past accident history
- time of day
- weather conditions
- road density
- intersection complexity
- road type

This project converts historical crash data into a grid-based machine learning problem. Each city zone is assigned a predicted accident-risk score, and the highest-risk zones are displayed on an interactive map.

---

## Problem Statement

The main question this project addresses is:

> Can we predict highly accident-prone city zones using historical crash records, weather conditions, and road-network structure?

The system predicts a risk score between `0` and `1` for each city zone.

```text
0.00 → Low risk
1.00 → Very high risk
