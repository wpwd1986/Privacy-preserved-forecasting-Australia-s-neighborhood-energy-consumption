# Privacy-preserved-forecasting-Australia-s-neighborhood-energy-consumption

Python implementation for paper Privacy-Preserved Optimal Energy Trading, Statistics and Forecasting for a Neighborhood Area Network


## Dataset

- Ausgrid solar home electricity data 2012-2013 (Due to the space limitation, a Zip file is uploaded, please Unzip the file the get the csv file)


## Generating privacy-preserved data
```
Privacy_Preserved_Ele_Data_Processing.ipynb

Obtain the processed privatized aggregate electricity consumption

- Privatized aggregate electricity consumption with Bin and Laplace mechanism.
    Data/Processed/dataset_Bined_Noise_Accu_Elec_Final.csv
- Privatized aggregate electricity consumption with Bin mechanism only.
    Data/Processed/dataset_Bined_Accu_Elec_Final.csv
- Accurate aggregate electricity consumption with Bin and Laplace mechanism.
    Data/Processed/dataset_Extact_Accu_Elec_Final.csv
```

## Start training

```
Privacy-preserved-forecasting.ipynb
```

