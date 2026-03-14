 ## Analysis of TNF-alpha production in THP-1 cells induced by LPS	
### Problem: fluctuating value of absorabances in starndard and samples
<br> **Table 1**
<br> _Original Data from Analysis of TNF-alpha production in THP-1 cells induced by LPS_
|Standard | Absorbance |Condition |  Absorbance  |
|:--------|:----------:|:---------|:------------:|
|2k       |   0.0630   |Control 1 |    0.1719    |
|1k       |   0.0464   |Control 2 |    0.1988    |
|500      |   **0.0724**   |Control 3 |    **0.9121**    |
|250      |   **0.0723**   |Control 4 |    0.1839    |
|125      |   0.0590   |LPS 1     |    0.2451    |
|62.5     |   **0.0757**   |LPS 2     |    0.6183    |
|31.3     |   **0.0714**   |LPS 3     |    0.3046    |
|0        |   **0.0844**   |LPS 4     |    0.4548    |

<br> Note. Absorbance was measured at O.D. 450nm
<br> ✅ Standard: should be downward-sloping
<br> ✅ LPS: should be much higher than the controls

Table 1 shows original experiment data. In standards, the absorbance should be decreasing as serial dilution was conducted. Notably, negative control (0 pg/mL) yielded a higher absorbance (0.9844) than the most concentrated standard (2000 pg/ml, 0.0630), confirming significantly low signal-to-noise ratio, which indicates high background. From ELISA troubleshooting guide from R&D SYSTEMS, insufficient washing causes high background. Each well should be washed with 400 µL of water buffer and washing process should be repeated three times. Removal of the liquid after every washing, pipette tip not getting into the contact with the well wall or floor to avoid cross-contamination are essential for a good performance.
<br> Beyond insufficient washing, fluctuating data from all samples indicates cross-contamination. During washing process or aspiration of antibody cocktails, residues from higher-concentration-well might entered the lower ones, causing cross-contamination.


<br> To solve the problem (fluctuating data from all samples/standards), one could increase number of washes or add a 30-second-soak step inbetween every washing process. Most importantly, highly accurate pipetting skill is required while conducting the experiment.

### References
R&D SYSTEMS. (2019). ELISA Troubleshooting Guide1: Common Questions, Tips & Tricks | R&D Systems. R&D Systems; R&D Systems. https ://www .rndsystems.com/resources/protocols/troubleshooting-guide-elisa-development#HighBackground
