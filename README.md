# DSD_Earthquake_Presentation

Repo designed to hold and store development of earthquake research project

## Key Terms

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
