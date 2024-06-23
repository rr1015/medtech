---
share_link: https://share.note.sx/wqfv22w9#cDpAy8kHO5ypDKnTohpiHQcdcQlvy2DYTynbTaEvFN0
share_updated: 2024-06-18T18:59:19+08:00
notetoolbar: Study
---

> [!scroller] Table of Contents
> ```table-of-contents
> ```

# Quality Management Systems
- A process-oriented, coordinated and organized system of activities that encompasses the **totality of all functions** involved in achieving quality and maximum customer satisfaction.
- Designed to **detect errors** and prevent them from occurring and from recurring, however, it does **not guarantee an error-free laboratory.**

## 12 ESSENTIAL ELEMENTS
- **Organization**
- **Personnel**
	- job qualifications, training, orientation
	- credential requirements (certifications - ASCPi)
	- competency (assessed regularly - 6months/annual) - KPI
- **Equipment and instrument management**
	- purchasing, inventory, calibrations
- **Purchasing** and **inventory**
- **Process control**
	- quality control
- **Information management**
	- LIS (data security) - requisition, data entry, data reports
- **Documents** and **records**
	- review, storage, retention of records
- **Occurrence** management
	- complaints of patients
- **Assessment**
	- internal and external, audits
- **Process improvement**
- **Customer service**
- **Facilities and safety**
- #mcl/list-grid 

# Quality Improvement
- System or process interventions aimed at **raising product quality**
- **CQI** - Continuous Quality Improvement %%(cycle, not a dead end process)%%

# Quality Assurance
- Proactive systematic activities to **provide confidence** that the quality requirements will be met
- QA activities are designed to **prevent defects** and **identify system variations or barriers** to quality

# Quality Control
- Process and procedures used to **detect analytical errors ==before the release== of patient test results**
- Measures **accuracy**, **precision** and **reproducibility** of a test system over time and under various operating conditions.


|                                                             |                                                                                                                                                                                                                                                                                                                                    |
| ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <mark class="red">Internal</mark> QC<br><br>INTRAlaboratory | - **Electronic**, **internal** and **procedural** controls contained within the test system that **ensures the reliability** of the test system<br>- Allows **identification of analytic errors ==within a week cycle==**<br>- Detects **changes in performance between the ==present operation== and =="stable" operation==**<br> |
| <mark class="red">External</mark> QC<br><br>INTERlaboratory | - **Commercial** controls used to **verify accuracy and reliability** of patient test results<br>- It is important in **maintaining long term accuracy** of analytical methods<br>- Involves **proficiency testing** programs<br><br>- NEQAS                                                                                       |


# PT Programs

- Participants receive <mark class="red">3 surveys per year</mark>, each survey consisting of **5 samples**
	- Blind samples
- The laboratory performs the indicated testing and reports results to the **surveying agency**
%%card%%
---
- $ PT Grading
	- <mark class="red">Commutable</mark> Samples #mcl/list-grid 
		- can be traced to a reference method (so preferred)
		- comparing results with a true value
		- ~ mean & SD of **reference method**
	- <mark class="red">Noncommutable</mark> Samples
		- ~ mean & SD of **peer group** (participating laboratories using the same methodology)
- ~ **Satisfactory** performance on a PT survey is achieved if <mark class="red">at least 80%</mark> of the sample results are graded as acceptable
	- 4/5 acceptable samples 
	- Acceptable: w/in 2SD
	- NI: 2-3SD
	- ! Unacceptable: >3SD

# STATISTICAL QUALITY CONTROL


| MEASURES OF CENTRAL TENDENCIES (indicators of ACCURACY)                                                                                |                                   |
| -------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- |
| Statistical term for **average**; sum of all results divided by the number of results.                                                 | <mark class="red">Mean</mark>     |
| **Middle data** after the data have been **ranked in order**; divides the distribution of **data points into upper and lower halves.** | <mark class="red">Median</mark>   |
| The **most frequently occurring** observation/value in a data set; the point where **most values lie**.                                | <mark class="red">Mode</mark>     |
| The **average of the highest and lowest values** in a data set.                                                                        | <mark class="red">Midrange</mark> |



| MEASURES OF SPREAD/DISPERSION (indicators of PRECISION)                                                                                                                                                                                                        |                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| Simply the **largest value in the data minus the smallest value**, which represents the **extremes of data** one might encounter.                                                                                                                              | <mark class="red">Range</mark>                                                |
| Square root of the sum of the squared differences of each data point from the mean divided by n-1 for samples; indicates the **amount of difference among the individual data** points or a **good estimate of dispersion** or how the values are distributed. | <mark class="red">Standard Deviation</mark>                                   |
| SD of a **set of data points divided by the mean** result expressed as **percentage** or as a **decimal** fraction.                                                                                                                                            | <mark class="red">Coefficient of Variation</mark><br><br>- index of precision |
| Average of the squared distances of all values from the mean; **SD squared**                                                                                                                                                                                   | <mark class="red">Variance</mark>                                             |

| tools for COMPARATIVE STATISTICS                                                                                                                |                                   |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- |
| This is used to determine whether there is a statistically significant difference **between the ==mean== of two groups** of data.               | <mark class="red">t - test</mark> |
| This is used to determine whether there is a statistically significant difference **between the ==standard deviation== of two groups** of data. | <mark class="red">f - test</mark> |

# QUALITY CONTROL CHARTS


|                                                        |                                                                                                                                                                                                                                                                                                                       |
| ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <mark class="red">GAUSSIAN CURVE</mark>                | ![[Pasted image 20240423142651.png]]<br><br>Normalized frequency distribution; symmetrical<br>**<mark class="red">Actual/assay values</mark>** plotted on the **X-axis**<br>**<mark class="red">Frequency</mark>** plotted on the **Y-axis**<br><br>**Confidence range** (2SD range) - 5% of true values fall outside |
| <mark class="red">SHEWHART LEVEY-JENNINGS CHART</mark> | ![[Pasted image 20240423142841.png]]<br><br>Most common QC chart utilized in the laboratory<br>**<mark class="red">Control values</mark>** plotted on the Y-axis<br>**<mark class="red">Date of analysis</mark>** plotted on the X-axis                                                                               |

# WESTGARD RULES


|                                      |                                                |
| ------------------------------------ | ---------------------------------------------- |
| <mark class="red">Random</mark>      | **12s**<br>**13s**<br>**R4s**                  |
| <mark class="red">Systematic</mark>  | **22s**<br>**41s**<br>**10x**                  |
| ![[Pasted image 20240423143047.png]] | Accept the run (**warning rule** only)         |
| ![[Pasted image 20240423143105.png]] | detects **imprecision**                        |
| ![[Pasted image 20240423143119.png]] | detects **random** error                       |
| ![[Pasted image 20240423143128.png]] | detect **imprecision** and **systematic** bias |
| ![[Pasted image 20240423143138.png]] | detects **systematic** bias                    |
| ![[Pasted image 20240423143146.png]] | detects **systematic** bias                    |

# HOW TO DEAL WITH A CONTROL THAT IS OUTSIDE THE ACCEPTABLE RANGE

|                                                                                                                                                                       |                                                                                                                                                          |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Hold patient results** until problem is resolved                                                                                                                    | - If a control value is inaccurate, patient results might also be inaccurate.                                                                            |
| **Rerun the control** (only **once**)                                                                                                                                 | - The inaccurate control value might have been due to a **random error**                                                                                 |
| If the control is still out, run a **new vial of control** or another with a **different lot number**                                                                 | - The error might be due to an **outdated**, **improperly stored** or **contaminated** control.                                                          |
| If the control is still out, look for and **correct any problems**, then run control                                                                                  | - Consider the **reagents** (low, outdated, improperly stored or contaminated), **preventive maintenance** (overdue), **mechanical** problems, **clots** |
| If the control is still out, **recalibrate** and then run control                                                                                                     | - Calibration might be **erroneous**                                                                                                                     |
| Get **assistance** if control is still out                                                                                                                            | - Contact **supervisor** or **service representative**. They may be able to determine the problem                                                        |
| Once the problem is resolved, **document the corrective action** done                                                                                                 | - This will provide a record for **future reference** and to determine and **avoid repetitive** problems                                                 |
| **Evaluate all patient results** during the rejected run and compare it with the last run with acceptable QC. Repeat the tests and issue corrected reports as needed. | - This to ensure **accuracy** and **reliability** of the reported results.                                                                               |


# DIAGNOSTIC EFFICIENCY

|                                                    |                                                                                                                                                                                  |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DIAGNOSTIC <mark class="red">SENSITIVITY</mark>    | Ability of a test to **detect disease** and is expressed as the proportion of persons **with disease in whom the ==test is positive==.**                                         |
| DIAGNOSTIC <mark class="red">SPECIFICITY</mark>    | Ability to detect the **absence of disease** and is expressed as the proportion of persons **without disease in whom the ==test is negative==.**                                 |
| <mark class="red">POSITIVE</mark> PREDICTIVE VALUE | Chance of an individual **having a given disease** or condition if the test is abnormal. Indicates the **certainty that a positive result is correct.**                          |
| <mark class="red">NEGATIVE</mark> PREDICTIVE VALUE | Chance an individual **does not have a given disease** or condition if the test is within the reference interval. Indicates the **certainty that a negative result is correct**. |

> [!NOTE]
> - SeNsitive methods → used for screening test
> 	- ↓ False N results (to detect people w/ diseases but were neg results)
> 	- Dis: ↑ False P (ppl w/o dss but pos results), fixed by confirmatory tests
> - SPecific methods → confirmatory
> 	- ↓ False P results
> 	- Dis: ↑ False N 

# LABORATORY MATHEMATICS



|                                                              |                                                                                                                                                                                                                                                                                                                                   |
| ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <mark class="red">PROPORTIONALLY EQUIVALENT SOLUTIONS</mark> | - NO CHANGE in concentration                                                                                                                                                                                                                                                                                                      |
| <mark class="red">DILUTION EQUATIONS</mark>                  | - change in concentration<br>- ↑ dilution = ↑ volume, ↓ concentration                                                                                                                                                                                                                                                             |
| <mark class="red">RATIO</mark>                               | Ratios can be used to express **part-per-part** or **part-per-whole**, and are written with a **colon between figures.**                                                                                                                                                                                                          |
| <mark class="red">DILUTION</mark>                            | - A dilution can be expressed as a **fraction of specimen volume** divided by the **sum of specimen volume and diluent**. The resulting fraction is the dilution (or dilution factor).<br><br>**Dilution Series**: <br>- When a diluted solution is diluted again, the final dilution is the product of its dilution factors.<br> |


- Examples
	- If a 5.0 dL soln contains 4.5 mg of bilirubin, how much bilirubin would there be in a 2.0 dL soln?
		- PPE key word - would there be in
	- What volume of a 0.5 M glucose solution can be made from a 100 mL of a 3M glucose stock solution?
		- Dilution key word - made from



# ANALYTICAL TECHNIQUES

- $ <mark class="red">SPECTROPHOTOMETRY</mark>
	- involves the **measurement of transmitted light** by a solution to **determine the concentration of the light-absorbing substances** in the solution.
- ![[Pasted image 20240424115616.png]]

# COMPONENTS

|                                          |                                                                                                                                                                                             |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <mark class="red">Light Source</mark>    | Provides **polychromatic light**; must generate sufficient energy to measure the analyte of interest. <br> - Differs depending on spectrophotometric work. <br> - If visible: Tungsten lamp |
| <mark class="red">Entrance Slit</mark>   | **Minimizes stray light** and prevents the entrance of scattered light into the monochromator system.                                                                                       |
| <mark class="red">Monochromator</mark>   | **Isolates the specific wavelength** needed for the measurement. <br> - Aka Wavelength selector. <br> - Bilirubin: 450 nm. <br> - Biuret T, protein determination: 560 nm                   |
| <mark class="red">Exit Slit</mark>       | Allows only a **narrow fraction of light** to reach the cuvet.                                                                                                                              |
| <mark class="red">Cuvet</mark>           | **Holds the solution** whose concentration is to be measured.                                                                                                                               |
| <mark class="red">Photodetector</mark>   | **Detects and converts** transmitted light into photoelectric energy.                                                                                                                       |
| <mark class="red">Read out device</mark> | Displays the **output** of the detection system.                                                                                                                                            |

# QUALITY CONTROL
|                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| --------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Wavelength <mark class="red">Accuracy</mark>  | - implies that a **photometer** is measuring at the wavelength that it is set to. Can be assessed easily using **special glass-type optical filters**.<br>  <br>- sp. the function of **monochromator**<br>  - Sp glass-type optical filters (Didymium filter, Holmium oxide filter)<br>  - **Didymium f** (broad absorption peak, <mark class="red">600nm</mark>)<br>  - **Holmium oxide f** (multiple sharp absorption peaks, <mark class="red">360 nm</mark>) |
| Wavelength <mark class="red">Linearity</mark> | - is defined as the ability of a photometric system to **yield a linear relationship** between the radiant power incident upon its detector and the concentration. Can be determined using **optical filters** or **solutions** that have known absorbance values for a given wavelength.                                                                                                                                                                        |





## Other Analytical Techniques

|                                                              |                                                                                                                                                                                                                                                           |
| ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <mark class="red">Flame Emission Photometry</mark>           | - Measures **light ==emitted==** by **easily excited atoms** (e.g., **sodium**, **potassium**, **lithium**)<br>  - Obsolete<br>  - Internal standards: **Cesium**, **Lithium**                                                                            |
| <mark class="red">Atomic Absorption Spectrophotometry</mark> | - Measures **light ==absorbed==** by **ground-state atoms** (unexcited)<br>  - Suitable for analytes **not easily excited by flame** (e.g., **Calcium**, **Magnesium**)<br>  - Used for **trace metals**<br>  - Light source: Hollow Cathode Lamp for AAS |
| <mark class="red">Fluorometry</mark>                         | - Atoms **absorb light of a ==specific== wavelength** and **emit light of ==longer== wavelength**<br>  - Used for **drugs**, **hormones**<br>  - Sensitive & Specific                                                                                     |
| <mark class="red">Turbidimetry</mark>                        | - Measures **reduction in light transmission** by particles in suspension<br>  - Used for **proteins in ==urine== and ==CSF==**                                                                                                                           |
| <mark class="red">Nephelometry</mark>                        | - Measures **light at an angle** from light source<br>  - Measures **antigen-antibody reactions**                                                                                                                                                         |
| <mark class="red">Potentiometry</mark>                       | - Measures **electrical potential** due to activity of **free ions**<br>  - Used for **pH** and **pCO2** (Severinghaus electrode) determinations<br>  - Ion selective electrode                                                                           |
| <mark class="red">Amperometry/ Polarography</mark>           | - Measures **current flow** produced by **oxidation** reaction<br>  - Used for **pO2** (Clarke electrode), **glucose**, **chloride**, and **peroxidase determinations**<br>  - Also known as **Polarography**                                             |
| <mark class="red">Coulometry</mark>                          | - Involves measurement of the **quantity of electricity needed** to convert analyte to a different **oxidation state**<br>  - Used to measure **chloride ions** in **serum**, **plasma**, **CSF**, and **sweat** samples                                  |
| <mark class="red">Voltammetry</mark>                         | - Involves measurement of the **resulting current** after a potential is applied to an **electrochemical cell**<br>  - Used to measure **heavy metals** (e.g., Lead)                                                                                      |
