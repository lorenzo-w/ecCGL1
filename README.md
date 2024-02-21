# ecCGL1

The process for enzyme-constrained model construction.

## About

The pipeline was written and tested on Linux. The core libraries essential for the pipeline including: cobra, plotly (draw figures), and related packages.

## Installation

Install dependencies using pip:

```shell
pip install --update .
```

## Steps to reproduce the analysis in the publication

Download all data and analysis code from github (directlt download or use git clone).

 ```shell
cd /file path/project save path/
git clone https://github.com/tibbdc/eciCW773.git
 ```

 All results can be reproduced by executing the Jupyter Python notebooks:

+ 01_model_calibration.ipynb
  + Model Calibration.

+ 02_construct_ecCGL1.ipynb
  + Construction of ecCGL1.
  
+ 03_CDF_kcat_and_mw.ipynb
  + Cumulative distribution of kcat and molecular weights.
  
+ 04_PhPP_analysis.ipynb
  + Phenotype phase plane (PhPP) analysis.
  
+ 05_FVA.ipynb
  + Comparative flux variability analysis.
  
+ 06_trade-off.ipynb
  + Overflow metabolism simulation.
  
+ 07_metabolic_engineering_targets.ipynb
  + Metabolic engineering targets prediction.
  