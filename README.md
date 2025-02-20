# Noise differences between electric and conventional cars at low speeds

This repository contains the **report, scripts, and data** related to my master’s thesis at DTU. 
The study investigates how noise characteristics differ between **electric and conventional vehicles** at low speeds, focusing on **loudness, annoyance, and spectral differences.**

## Contents
  -	📄 **Report**: [Link to PDF](https://github.com/SSD85/Thesis/blob/main/report.pdf) -> Download raw file *(hosted via Git LFS)*
  -	🖥 **Scripts**: Python scripts for data processing and analysis *(coming soon)*
  -	📊 **Data**: Measurement data will be made available on Zenodo *(to be added)*

## **Post-project analysis update**  
The report includes **282 data points from 1 of 3 microphones**, using **T-tests** for statistical analysis. 
However, after revisiting the data, it became clear that T-tests were inaccurate because **noise characteristics within each vehicle introduce within-subject correlation** 
(violating the assumption of independent data points).  

After the project period:  
- **All data were exported from the DAQ software** and re-analyzed.  
- **Mixed Effects Models** were used instead of T-tests.  

### **Key findings from updated analysis:**  
- **Overall (15-50 km/h):** EVs increase noise at a slightly lower rate than ICEs, but they are **not significantly quieter** overall.  
- **Speed-Specific Models:**  
  - No significant difference at **15-20 km/h**.  
  - Significant differences at **30-50 km/h**.  
- **Electric vs. Petrol (excluding diesel):**  
  - At **40 km/h only**, Electric cars are **significantly quieter (~1.3 dB(A))** than petrol cars.  

➡️ The **figure in** `EV_vs_ICE_interaction_effect.png` **is based on 829 data points from 3 microphones at 7.5 m distance.**  

## How to use
  1.	Clone the repository:

```sh
  git clone https://github.com/yourusername/your-repo.git
```
  2. If the report doesn’t download, install Git LFS and pull large files:
```sh
  git lfs install
```
```sh
  git lfs pull
```
  3.	Run analysis scripts (instructions will be provided once added).

## Citing this work

If you use this work, please cite:
Sascha Siri Dahl, “Noise differences between electric and conventional cars at low speeds,” MEng Thesis, Technical University of Denmark, 2025.

## Contact & Discussion

For questions or collaboration, feel free to reach out via [LinkedIn](https://linkedin.com/in/sascha-siri-dahl-ssd) or open an issue on this repository.
