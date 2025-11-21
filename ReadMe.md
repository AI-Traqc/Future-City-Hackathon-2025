# Hackathon Dataset README

## 1. Overview

This README provides a concise description of the datasets and documents used in the hackathon.  
Two challenges are defined in the official challenge document (PDF).  
The datasets listed here support **Challenge 2**, which focuses on the analysis and calibration of urban air-quality measurements.

---

## 2. Included Files

### 2.1 Challenge Document (PDF)

- Contains the full descriptions of **Challenge 1** and **Challenge 2**.  
- Defines goals, evaluation criteria, and expected outputs for both tasks.  
- Challenge 2 explicitly requires the datasets listed below.

---

## 3. Datasets for Challenge 2

### 3.1 syntetische_daten_heilbronn_2021_2023

- Synthetic dataset representing simulated smart-city air-quality conditions for 2021–2023.  
- Designed for:
  - Initial exploration  
  - Pipeline development  
  - Algorithm testing without calibration requirements  
- Provides a clean sandbox before working with real sensor data.

### 3.2 hhn_daten_vergleichskampagne_20241115-20250205

- Real-world raw data from the UrbanAirLab project at Heilbronn University (HHN).  
- Project page: https://www.hs-heilbronn.de/de/UrbanAirLab  
- Measurement period: **15 Nov 2024 – 05 Feb 2025**.  
- Content:
  - Two HHN sensor boxes  
  - Reference data from the LUBW station (co-located during the same period)  
- Important:
  - **!!! Warning!!!** Columns `NO`, `NO2`, `O3`, `CO` contain **!!! DO NOT USE or be Replace with Syntetic Data**.  
  - These readings must be converted or calibrated using the LUBW reference measurements.  
  - Raw values must not be interpreted as physical pollutant concentrations.

---

## 4. Purpose in the Hackathon

- **Challenge 1**: Conceptual or analytical task (see challenge PDF).  
- **Challenge 2**: Practical data analysis challenge using the datasets above. Typical tasks include:
  - Cleaning and preprocessing  
  - Calibrating raw HHN sensor data  
  - Comparing synthetic and real datasets  
  - Evaluating data quality and sensor performance  

---

## 5. Additional Reference Datasets 

It is **recommended** that Participants extend their analysis using publicly available air-quality datasets, for example:

- OpenAQ Global Platform: https://openaq.org  
- London Datastore Air Quality: https://data.london.gov.uk  
- NYC Open Data Environmental Datasets: https://data.cityofnewyork.us  
- EEA Air Quality Hub: https://www.eea.europa.eu/themes/air/air-quality  

These sources can be used for benchmarking or external validation.

---