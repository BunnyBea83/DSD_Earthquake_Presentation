# Data Science Development - Earthquake Presentation

**Course:** AD450 H11C 31420 — Data Science Development
**Instructor:** Ix Procopios   
**Authors:** Bea Sauve, Elton Nichols, Joe Klinck, Kainen Osborne
**Date:** March 2026

---

## Overview

This repo was designed to hold and store development of earthquake research project. 
All observations, data refinement, and alayses are conducted on [this](https://www.kaggle.com/datasets/warcoder/earthquake-dataset?select=earthquake_data.csv) dataset, aquired from Kaggle.com.

### About the Data Set

- [Link](https://www.kaggle.com/datasets/warcoder/earthquake-dataset?select=earthquake_data.csv) to original data set.   
- Original CSV files and combined CSV files are located in the `data` folder. 

#### Earthquake Key Terms

- NST (Number of Stations): The total number of seismic stations used to determine the earthquake's location (hypocenter). Generally, a higher number of stations leads to a more accurate calculation of where the earthquake started.
- CDI (Community Internet Intensity Map): Also known as "Did You Feel It?" (DYFI). This value represents the maximum intensity reported by the public through online questionnaires. Unlike instrumental data, this is based on human observation and subjective experience.
- MMI (Modified Mercalli Intensity): The maximum estimated or measured intensity at the epicenter. While magnitude measures the energy released (size), MMI measures the shaking effects at a specific location. It ranges from I (not felt) to XII (total destruction).
- Alert: A color-coded flag from the PAGER (Prompt Assessment of Global Earthquakes for Response) system. It estimates the severity of the impact based on population exposure:
  - Green: Low likelihood of casualties or damage.
  - Yellow: Significant regional impact (potential for some casualties/damage).
  - Orange: National-level alert (significant casualties/damage).
  - Red: International-level alert (high casualties and widespread damage).
- Sig (Significance): A number (typically 0–1000) that describes how "significant" the event is based on a combination of magnitude, PAGER alert level, maximum MMI, and the number of felt reports. Higher numbers indicate a more impactful event.
- Net (Network ID): A short code identifying the specific seismic network that contributed the primary data for the event (e.g., us for the National Earthquake Information Center, uw for the Pacific Northwest Seismic Network, or ci for Southern California).
- Dmin (Minimum Distance): The horizontal distance from the epicenter to the nearest seismic station, measured in degrees ($1^\circ \approx 111$ km).
  - Why it matters: If the nearest station is very far away (high dmin), the estimate of the earthquake's depth is usually less accurate.
- Gap (Azimuthal Gap): The largest angular separation (in degrees) between neighboring stations as seen from the epicenter.
  - Interpretation: A "gap" of $180^\circ$ means all stations are on one side of the earthquake. A smaller gap (closer to $0^\circ$) means the earthquake is well-surrounded by sensors, resulting in a much more reliable location fix.
- MagType (Magnitude Type): The specific method or scale used to calculate the earthquake's size. Common types include:
  - mw / mww: Moment Magnitude (the most common for large quakes).
  - ml: Local Magnitude (the original "Richter" scale, used for smaller, local events).
  - mb: Body-wave Magnitude.
  - md: Duration Magnitude (determined by how long the shaking lasts on the seismogram).

---

## Repository Structure

```
Project_3_Analysis_Profit_Forecasting/
├── data/
│   ├── earthquake_1995-2023.csv         # Data set of earthquake data from 1995-2023
│   ├── earthquake_data.csv              # Data set of earthquake data from 2001-2023
│   └── merged_earthquake_data.csv       # Combined data sets
│
├── README.md                               # Project overview (this file)
└── CONTRIBUTING.md                         # Contribution guidelines and team roles
```

---

## Use of Repository

* Student Contrubutions:
  * To observe contributions performed by by a specific student, access their respective Jupyter Notebook or file containg their name.  
  * Additional contrubutions may be observed in the [CONTRIBUTING.md](CONTRIBUTING.md)

* Access Data Sets
  * All raw and modified CSV files may be accessed in the data folder

* Review Team Presentation
  * The Slide Deck, [insert slide name]() , contains the final presentation of the teams analysis on Earthquakes
  * Access the slide deck to observe our presentation

---
## Team

| Name | Username |
|------|------|
| Bea Sauve | bunnybea83 |
| Elton Nichols | oi12bu |
| Joe Klinck | jklinck |
| Kainen Osborne | kosborne00 |

See [CONTRIBUTING.md](CONTRIBUTING.md) for a full breakdown of individual contributions.

---

## License

This project was produced for academic purposes as part of AD_450 at [North Seattle Community College]. Not intended for commercial use.