# Capstone-Q1

## Data Access:
- From the Sixth Coupled Model Intercomparison Project (CMIP6) is combined from research labs across the world. All ~ 30 terrabytes of the publically available data can be accessed [here](https://esgf-index1.ceda.ac.uk/projects/esgf-ceda/), and has been archived [here](https://registry.opendata.aws/cmip6/) on the cloud.
- To access the data we used: [Casper](https://arc.ucar.edu/docs) data analysis cluster at the National Center for Atmospheric Research (NCAR) which has all the data available.
- This is how we Explored and Processed the data found in ```explore_data.ipynb``` and ```data_process.ipynb```
    - ```explore_data.ipynb``` provides some guidance how to navigate data, and exploratory visuals and models.
- For all baseline models we used data from ClimateBench found here: https://zenodo.org/records/7064308
    - Which contains validation and test data.  

## Baseline Replication
- Download data from here: https://zenodo.org/records/7064308
    - Download ```test.tar.gz``` and ```train_val.tar.gz``` and decompress them into 1 folder.
    - Upload the files onto CASPER
        - Our default folder is ./dataset
    - Download ```utils.py``` from this repo

### Models
- Gaussian Process
    - download balls
- Random Forests
    - download balls
- Another model ()
    - TBD (no balls) 

## Checkpoints
### Checkpoint 11/7
- Paper Replication Progress
    - Data Exploration and visualizations - ```explore_data.ipynb```
    - Processing output data - ```datap_rocess.ipynb```
    - Models - TBD
    - Report - Abstract, introduction (Overview, prior works, description of data).

### Checkpoint 11/24
- TBD


Watson-Parris, D., Rao, Y., Olivié, D., Seland, Ø., … “ClimateBench v1.0: A benchmark for data-driven climate projections”. Journal of Advances in Modeling Earth Systems 14, e2021MS002954: https://doi.org/10.1029/2021MS002954