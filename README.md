# Exoplanet Habitability Analyzer

**Field**: Astrobiology, Planetary Science, Computational Modeling  
**Tools**: Python, Pandas, Matplotlib, NumPy  
**Why I Do Research**: I was always intrigued by Enrico Fermi's famous paradox, which states the possibility that extraterrestrial life exists but we are unable to find it. By using real scientific data and specific calculations and data processing, this project will reveal how rare Earth's environment might be, and why life as we know it could be so precious.<br>
**Questions to Consider**:
1. Why is life rare? How rare is it?
2. How might extraterrestrial environments shape the evolution of life?
3. Is the current definition of life universal? Could there be life outside that is still life but behaves differently from life on Earth?
---

## Abstraction
This project analyzes real exoplanet data and ranks planets by potential habitability using criteria like temperature, atmosphere, stellar flys, and size. In this project, we define a **custom habitability score (HS)**, inspired by Earth similarity index models and data sets. The data and the research in this experiment is inspired by the Earth Similarity Index data.

---

## Scientific Method

**Question**: Which known exoplanets most likely support human-compatible life?<br>
**Hypothesis**: Given current exoplanet discoveries, only a small fraction (likely <5%) of known exoplanets meet the minimum physical and biological conditions necessary for human life,  
**Experiment**: Design a scoring model, analyze data from NASA's Exoplanet Archive, and more data
**Conclusion**: Drawn after data analysis

---

## Score Criteria (Tentative)

| Factor            | Target Value (Earth-Based) |
|-------------------|----------------------------|
| Temperature       | 273K–373K (liquid water)   |
| Gravity           | 0.5g – 2g                  |
| Stellar Flux      | ~1 (Earth = 1)             |
| Radius            | 0.5R – 2R                  |
| Orbital Zone      | Habitable zone only        |

Each planet will be given a score from 0 to 1 based on how closely it matches Earth.

---

## Sample Results Snapshot
[Insert when available]

---

## Medical and Astrobiological Angle

- Understand biological limits (what humans need to survive)
- Explore what “human-ready” means in terms of gravity, pressure, temperature, and radiation
- **Space colonization, astronaut health**, and **emergency life sciences**
- Understand the limitations of the current definition of life
- Apply natural selection in extraterrestrial environments

---

## Files

- `/src`: Python scripts to process and score data
- `/data`: CSVs (NASA Exoplanet Archive or other)
- `/notebooks`: Jupyter notebook for analysis + visuals
- `/media`: Graphs and plots
- `paper.md`: Write-up in research-paper format

---

## Future Goals
- Add a radiation exposure risk model
- Include AI to predict potential biosignatures
- Visualize the top 10 most habitable exoplanets on a star map
- Find trends in the habitability of exoplanets from different angles (e.g., locations, compositions, impact from other celestial bodies, etc.)

---

## References

- NASA Exoplanet Archive: https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PSCompPars
- Earth Similarity Index (Schulze-Makuch et al.)
- The Human Body in Space (NASA): https://www.nasa.gov/humans-in-space/the-human-body-in-space/

---

Made with 💙 by [Claire]
